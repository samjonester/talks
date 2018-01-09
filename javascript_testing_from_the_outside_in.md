# JavaScript Testing From The Outside In
## Abstract
Testing is about confidence. We want to know that what we build works and doesn't break the existing system. What about design feedback, though?

Outside in TDD will add another level of confidence to your code. The confidence that it is changeable!

## Description
TDD is becoming widely accepting in JavaScript today, causing the quality of our code to improve. JavaScript Testing From The Outside In defines TDD a bit differently than you're used to, though. According to this process, TDD stands for Test Driven DESIGN. Tests are the perfect place to understand how well the code in your system is designed. This upfront design feedback will lead to cleaner, more focused, and more easily changeable components.

We will start by looking at how to design a test suite. Then we will define the way that we would like to interact with our components by using our tests. Finally, we will implement our code using the design sketch we created with our test. Following this process allows our code to take shape organically, creating components that are easy to use and safe to change.


## Notes
There are two big schools of TDD. The Detroit school, popularized by XP pioneers. This school of testing defines the Red -> Green -> Refactor workflow. But honestly, who actually takes the time for a refactor when there is deadline pressure to ship. And if you did, how do you know what to refactor towards?

The alternate approach is the London approach, top-down approach, or (as I prefer) outside in TDD. This approach was made popular by the testing book "Growing Object Oriented Software Guided-by Tests". This approach allows code to be designed as it's needed, allowing us to write the code we wish we had! It eliminates the need for a final refactor, and with it, eliminates awkward internal APIs.

JavaScript Testing From The Outside In will focus on the latter. Allowing code to emerge naturally.

I work for Test Double, and we were founded on principles of good software design guided by test suites that embody confidence. We've got an entire public wiki on good testing practices (https://github.com/testdouble/contributing-tests/wiki/Test-Driven-Development). This workshop will be based on an outside in TDD exercise that I regularly perform with those new to TDD. It will be a little more advanced than usual since I've got time to extend into test suite hygiene as well.
