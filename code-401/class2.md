# Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

**Explain middleware, answer as though I were a non-technical recruiter.**

It is software that takes a request, processes it, and passes it on to the next piece of middleware.

**Express the most popular __ __ ____.**

Node web framework

**Express is “unopinionated.” What does that mean?**

It has fewer restrictions on the best way to glue components together to achieve a goal, or even what components should be used. They make it easier for developers to use the most suitable tools to complete a particular task, albeit at the cost that you need to find those components yourself.

From [Express/Node introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

**What is a module and why is modularity useful to us as developers?**

A module is a JS file that you can import to otherr code using `require()`.  It is important because it allows you to organize your code into manageable parts. 

## What is NPM?

**What version of npm are you running on your machine?**

9.4.0

**What command would you type to install a library/package called ‘jshint’ into your node project?**

`npm install jshint`

## What is TDD?

**Explain why tests are important. Please explain as though I were your non technical elder.**

Tests allow you to write more efficient code by writing just enough code to get a unit test to pass. You can refactor the code until it passes.

**What are three expected benefits of testing**

1. Many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
2. The same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
3. Although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

From [TDD](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

**Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.**

Typical individual mistakes include:

- Forgetting to run tests frequently
- Writing too many tests at once
- Writing tests that are too large or coarse-grained
- Writing overly trivial tests, for instance omitting assertions
- Writing tests for trivial code, for instance accessors

Typical team pitfalls include:

- Partial adoption – only a few developers on the team use TDD
- Poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time
- Abandoned test suite (i.e. seldom or never run) – sometimes as a result of poor maintenance, sometimes as a result of team turnover

From [TDD](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

## CI/CD

**What are three benefits of Continuous Integration?**

1. Ensure everyone's changes integrate
2. Catch Bugs
3. Reduce merge conflicts

**What is the difference between Continuos Delivery and Continuous Deployment?**

Continous delivery allows you to develop to release at any time. Continuous Deployment is an extension to this that allows you to deploy new features immediately.

**Explain how GitHub fits into this process assuming the listener comes from a non-technical background**

GitHub looks at work a developer does and copies it on their servers once a certain amount of checks are complete.


## Reflection

**What are your learning goals after reading and reviewing the class README?**

I need to solidify creating APIs. I think this class will be a mix of review with new elements sprinkled in. I just need to keep working with this and it will stick.

## Things I want to know more about

How to collaborate better on GitHub. There are a lot of resources tht GitHub has that we have not used yet.

[Back to Home](../README.md)