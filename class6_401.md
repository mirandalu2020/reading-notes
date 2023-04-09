# Class Six Notes (401)

## Authentication

### Securing Passwords[^1]

- Turning the password into a string a code that is equivalent to the password itself by an algorithm
- **Bcrypt**: uses symmetric block cipher cryptographic algorithm (same method to encrypt and decript) the password, and introduces a "work factor." This makes attacking extremely slow because the work factor limits attacks by extending time allowed between each guess

### Basic Auth[^2]

- Basic Authentication is a method for an HTTP user agent (browser) to provide a user name and password when making a request.
- In the header of a Basic Auth request, the required properties include `Authorization: Basic <credentials>`
- Usernane abd oasswrid ub Basic Auth is encoded in Base64 and joined by a single colon.

### OWASP Auth Cheatsheet[^3]

- Authentication is the process that verifies the user is who it claims to be.
- An error message should be generic, so a potential attacker can not repeatedly trying to validate users with extra info

## Things I want to know more about


 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html
[^2]:https://en.wikipedia.org/wiki/Basic_access_authentication
[^3]:https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html
