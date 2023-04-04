# Class Two Notes (401)

## Express, NPM, TDD, CI/CD

### Intro to Nodejs and Express[^1]

- Middleware are packages developed to address web development problems, they are the intermediate software the resolve things between the client/server.
- Express the most popular Node web framework. It is an "unopinionated" framework as it does not have the "right way" of structuring an application
- A module is a JavasScript libray/file that you can import into other code, it is useful as it makes code easier to manage, debug, and reusable.

### NPM[^2]

- My NPM version is 9.5.1
- You can use `npm install jshint`

### TDD (Test Driven Development)[^3]

- Test-driven Development is a style of programming in which includes coding, testing, and design. They are important as they can debug code on the run before deployment
- Benefits of testing include reductions in defect rates, reduction of effort in projects' final phases
- Pitfalls of TDD include: forgetting to run tests frequently, writing too many tests at once, only a few developers use TDD on a team, and poor maintenance of the test suite

### CI/CD

- Benefits of continuous integration allows the application to be running continously, and keep on service without interruption.
- Continuous delivery is a software practice where the code changes are prepared to be released, while continuous deployment is a continous release of code changes into the production environment.
- GitHub fits into this process by running the test automatically (if configured) before merging the individual branch to the dev branch, and same process before merging the dev branch to the main branch

## Things I want to know more about


 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction
[^2]:https://docs.npmjs.com/about-npm
[^3]:https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1)