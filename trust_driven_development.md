# Trust Driven Development

## Abstract

Tests help you trust that YOUR code works and can be changed, but where do you draw the line?

Do you trust that databases store things, or you can make HTTP requests? When should we test these things?

Use TRUST as a metric to determine the value of tests at the boundaries of your application.

## Details

Trust Driven Development is a chance for reflection. It is an evolution on the concept that Test Driven Development helps us to design our code.

Trust Driven Delelopment allows us to think deeply about the boundaries of our applications. We can purposefully design and test integration points between our code and the dependencies it relies on.

The audience will be rallied around a series of unfortunate tests. We will talk about the cost and the value that is created by each specific test at the boundary of an application. We will ask ourselves whether or not this test should be written and left to run in our test suite for all of eternity.

After analyzing each testing scenario, the audience is guided towards higher value solutions. They are shown techniques to isolate dependencies where there is high trust to avoid high-cost low-value testing scenarios. Then they will be shown techniques to properly test dependencies where there is low trust.

The types of dependencies that the audience will be helped to analyze, ordered by degrees separation follow:

- Libraries that have become the primitives in our system
- Libraries that act as clients to stable external integrations
- Home-grown external integrations
- A focus will also be given to the volatility of an integration point. This is an interesting discussion point because we shouldn't trust this integration point, though a test serves a different purpose than regression tests to prevent breaking the application as code changes. This point will bend the audiences mental model of testing strategies beyond "run these before merging" style tests.

## Notes
I am a software consultant who has seen many test suites. When teams that I work with have gained a solid grasp of the fundamentals of testing code, this opens up discussion points about how to optimize a test suite. The goal of a test suite is to provide the most value for regression safety, flexibility for change, design guidance, with the least amount of maintainence and execution cost to the team. One surprisingly high-cost area is at the boundaries of an application. I often have the opportunity to coach teams to be smarter about the way they write tests for code that has external integrations (libraries, file-systems, databases, http integrations...). Trust is a primal word that I like to use to prompt thoughtfulness about the tradeoffs of these tricky tests.
