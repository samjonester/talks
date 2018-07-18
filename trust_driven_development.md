# Trust Driven Development

## Abstract

Tests help you trust that YOUR code works and can be changed, but where do you draw the line?

Do you trust that databases store things, or you can make HTTP requests? When should we test these things?

Use TRUST as a metric to determine the value of tests at the boundaries of your application.

## Details

Trust Driven Development is a chance for reflection. It is based on the concept that classic Test Driven Development allows us to think deeply about the design of our code.

Trust Driven Delelopment allows us to analyze the boundaries of our applications. We can purposefully design and test integration points between our code and the dependencies it relies on.

The audience will be rallied around a series of unfortunate tests. During this section, we will think deeoly about what value these tests are providing, and whether they are worth their cost.

After analyzing each testing scenario, the audience is guided towards higher value solutions. They are shown techniques to isolate dependencies where there is high trust to avoid high-cost low-value testing scenarios. Then they will be shown techniques to properly test dependencies where there is low trust.

The types of dependencies that the audience will be helped to analyze, ordered by degrees separation follow:
- Libraries that have become the primitives in our system
- Libraries that act as clients to stable external integrations
- Home-grown external integrations

A focus will also be given to the volatility of an integration point. This is an interesting discussion point because we don't trust this integration point, though its test might not deserve a place in our development test suite. This point will bend the audiences mental model of testing strategies beyond "run these before merging" style tests.
