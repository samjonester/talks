# Title

JavaScript Is Too Convenient

# Abstract

Are in-line objects and anonymous functions depriving your code of important names? Are they too noisy, making it difficult to understand the purpose of a function? Analyze the real cost of these conveniences, and write nicer code.

# Description

Conveniences we love in JavaScript are discouraging us from writing concise, descriptive code. In-line objects and anonymous functions deprive us of descriptive domain names for the actions we are performing and the objects we use to perform them. They add noise that distracts from the purpose of a function.

This is especially true in tests, which should help us feel the code we write. These conveniences encourage us to create functions that do too much and require complex test setup.

"JavaScript is Too Convenient" will encourage you to write more focused code with good names. We can make our code nicer for new team members, and our future selves by examining the purpose of our code, amplifying the signal, and reducing the noise.

# Notes

The two most important things we can do to make code more accessible to new team members and our future selves are to leave good notes in the form of names, and remove noise that distracts from the purpose of our code. These two goals are at odds with two of the most popular conveniences in JavaScript, in-line objects and anonymous functions. This talk highlights that competition by providing the ability to decide whether their use is harmful in your code. It presents alternative approaches as a spectrum from the simple activity of naming in-line anonymous functions, all the way to extracting pieces of functionality into well named collaborating modules. I argue that we spend the majority of our time as developers reading code, so let's make our code nicer to read!


