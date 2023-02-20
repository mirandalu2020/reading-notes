# Pre-work Class Notes (301)

## ES6 Classes[^1]

### Modeling

Ex. model an animal

- attributes: hair color, height, weight, location
- behaviors: (methods, vers) walk(), speak(), drive()

> const Animal = function(name, legs) {
>   this.name = name;
>   this.legs = legs;
> }

> Animal.prototype.walk = function() {
>   this.isWalking = true;
}

> let puppy = new Animal('blake', 4);
> console.log(puppy)  //Animal {name:'blake', legs: 4}

> puppy.walk();
> console.log(puppy) //Animal {name:'blake', legs: 4, isWalking:true}

- add another method directly inside the constructor:

> const Animal = function(name, legs) {
>   this.name = name;
>   this.legs = legs;
>   this.isEating= function () {
>     this.isEating = true;
          }
> }
> puppy.eat();
> console.log(puppy); //Animal {name:'blake', legs: 4, eat: [function], isWalking:true, isEating:true}

- notice that eat is an attribute as a function, it is stored as a **First-class properties**, versus `walk()` is a prototype function (ike a blueprint)
- so ALL instances of a new Animal has access to the prototype method, but does not have to store it as a first-class property, that is, the behavior can be shared (more efficient)

- create a Dog constructor function that is like an Animal

> const Animal = function(name, legs) {
>   Animal.call(this, name, legs); //call the Animal constructor with `this`
> }

> Dog.prototype = Object.create(Animal.prototype); // let the Dog have access too ALL Animal prototypes

> let puppy = new Dog('blake', 4);
> puppy.walk();
> puppy.eat();
> console.log(puppy)   //Animal {name:'blake', legs: 4, eat: [function], isWalking:true, isEating:true}

- note that it is EXACTLY the same as an Animal, as Dog created itself from an Animal

>console.log(puppy instanceof Animal); //true
>console.log(puppy instanceof Dog); //true

- note that the broswer sees the puppy created from Dog as a new Dog, but have the prototypes of an Animal

### Reproduce the code above using a Class

> class Animal {
  constructor(name, legs) {
    this.name = name;
    this.legs = legs;
  }

  walk() {  //no need to tell JS that this is a function
    this.isWalking = true;
  }

  eat() {
    this.isEating = true;
  }
}

> let rosie = new Animal('rosie', 4);
> cosole.log(rosie) //Animal{ name:'rosie',legs:4}

- note that all the methods automatically become prototypes

> rosie.walk();
> rosie.eat();
> cosole.log(rosie) //Animal{ name:'rosie',legs:4, isWalking: true, isEating: true}

- note that we dont'see the methods as functions, all the methods are stored in the prototype

Make a new class from the Animal class

> class Dog extends Animal {
> }
> let rosie = new Animal('rosie', 4);
> rosie.walk();
> rosie.eat();
> cosole.log(rosie) //Dog{ name:'rosie',legs:4, isWalking: true, isEating: true}

- note that the new Dog extends from Animal, the class is Dog, but the prototyes are still Animal
- the Dog is a **sub-class** of an Animal

> class Dog extends Animal {
>    speak(){
>      console.log('Woof!');
>    }
> } //do not need to say `call`, the extend does it all
> rosie.speak();
> console.log(rosie) // Dog{ name:'rosie',legs:4, isWalking: true, isEating: true} Woof!

- note that the speak is unique to Dog, a subclass Bird of Animal can have a different way of speak. Now add another attribute that only Dog can have (but not other Animals)

> class Dog extends Animal {

>  constructor (name, legs, furType){
>  super(name,legs); //`super` says to use these attributes to create an instance, and then add everthing else to just this subclass
>  this.furType = furType;
}

>    speak(){
>      console.log('Woof!');
>    }
> }
> let rosie = new Animal('rosie', 4, 'Short Hair');
> rosie.walk();
> rosie.eat();
> rosie.speak();
> console.log(rosie) // Dog{ name:'rosie',legs:4, furType: 'Short Hair', isWalking: true, isEating: true} Woof!

 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://www.youtube.com/watch?v=9Yc5J3Ap9-4