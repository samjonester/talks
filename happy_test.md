# Happy Test

## Abstract

We all know that we should test, so why does it make us sad?

"It felt like my job was to keep the tests green. We thought we were doing everything right. We wrote tests, and lots of them. We had long, flaky builds, and little confidence in our suite." - Most Teams Everywhere.

I'm here to tell you that the test you're about to write is a trap! We tend to write large tests that fail in strange ways and erode our confidence.

This talk will show you how happy teams write tests.

## Details
There are different types of tests that serve different purposes. _Happy Test_ introduces a way to define and organize tests by the purpose they serve. It also introduces the concept of using a test to feel it's code, allowing test pain to be a signal used to improve code design.

_Happy Test_ first rallies the audience together around shared bad test experiences. The bad experiences are used as learning tools to by connecting specific test suite pains to organizing a test suite with different types of tests (isolated unit tests, integration tests, end-to-end tests).

After the types of tests are introduced with their purpose, basic testing strategies for each type are shown. The strategies are centered around the ideas of focusing a test and its code, trusting the tests for your dependencies and integrations, analyzing the cost that testing decisions have on a test suite and the team maintaining it.

## Pitch
_Happy Test_ is a talk about purposeful test design. Tests should be given even more design direction than production code. They tell a story about how and why the production code is shaped the way it is.

Too often that story is one of pain. Our test suite tells us that we should ignore our failed builds because, "Who wants to wait an hour for a new one?". We lose confidence in our suite. Each new change makes us break out into a cold sweat as we anticipate the number of tests that we'll need to rework.

We can rewrite the ending to that story by designing better tests. By honing in on a couple key words - *focus*, *trust*, and *cost* - we can find the most value in our tests. By defining different types of tests with different purposes, we can get the most value out of our test suite.

## Bio
Sam Jones | @samjonester | https://samljones.com

I believe that empathy and openness should be a developer's sharpest tools. When I'm programming, I love code design, and testing. I also have a strong passion for learning and teaching.

I am a double agent at Test Double living in Philadelphia, PA. I am a cook and cyclist in my free time. I love craft beer and good coffee. I'm a Husband and Father.
