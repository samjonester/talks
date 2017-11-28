# Do I Really Need To Test That!?

Format: Regular Session

Track: Developer Happiness

Tags:
  * beginner
  * intermediate

## Abstract

We all know that we should test, so why does it make us sad?

"It felt like my job was to keep the tests green. We thought we were doing everything right. We wrote tests, and lots of them. We had long, flaky builds, and little confidence in our suite." - Most Teams Everywhere.

I'm here to tell you that the test you're about to write is a trap! We tend to write large tests that fail in strange ways and erode our confidence.

This talk will show you how happy teams write tests.

## Details

_Do I Really Need To Test That!?_ is a talk about purposeful test design. Tests should be given even more design direction than production code. They tell a story about how and why the production code is shaped the way it is.

Too often that story is one of pain. Our test suite tells us that we should ignore our failed builds because, "Who wants to wait 4 hours for a new one?". We lose confidence in our suite. Each new change makes us break out into a cold sweat as we anticipate the number of tests that we'll need to rework.

We can rewrite the ending to that story by designing better tests around the most difficult areas of our applications, their boundaries. In _Do I Really Need To Test That!?_, we will critically analyze the value added by testing a database, the file system, and API integrations. We'll ask whether we should even write those tests in the first place. Then we'll learn strategies to do it better, if we decide that test is necessary.

A central topic discussed throughout the learning process is TRUST. Do you trust the integration point, and if so, what does that level of trust means for a test suite.

Using trust we will critique the following types of tests:

* Simple Inline Database Queries
* Aggregated Database Queries
* File Systems Integrations
* API Integrations

We will also learn these important strategies to rebuild trust in our tests:

* Focus on testing YOUR code
* How to determine whether value is added by a test
* Don't accidentally depend on database object validation
* Wrap integrations to create a smaller, less awkward, and fakeable API
* Centralize logic around integrations for easy future changes
* Strategies for integrating with volatile client APIs


## Pitch

_Do I Really Need To Test That!?_ is a fantastic addition to the RailsConf Developer Happiness Track. The value of our test suite has a dramatic influence on our day to day happiness. Unfortunately, Rails has a way of encouraging testing practices that ruin our future happiness. We can reclaim it by learning better strategies for testing the hardest parts of our applications.

RailsConf is the perfect venue for this talk. In the Rails community, many developers are currently leveling up and starting to question dogmas about testing. Although it's valuable to first learn to test "the Rails way", there is a time where these ideas should be questioned in order to continue growing. As these developers progress they begin using more purposeful code design practices. An important part of that process is learning to write tests that keep the team from feeling burnt out on testing.

I have helped write a gigantic, slow, flaky test suite. It had many tests that relied on the filesystem, on external integrations, and on a properly created and seeded database. This caused me to hate working on the application. I have first hand experience feeling the pain of poor tests. I also have had the fortune to have learned how to listen to my tests. I want to help relieve others of the pain I went through to get to this point.

## Bio

Sam Jones | @samjonester

I am extremely passionate about code design and testing. I believe that tests are a way to provide context, clarity, and design feedback. My favorite way to test and write code is through outside-in development. My favorite things to think about during that process are responsibilities and dependency management. I'd love to have a discussion about these topics with you. Find me at the conference!
