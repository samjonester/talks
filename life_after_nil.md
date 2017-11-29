# Main Message

Ruby is late to the type system party. Let’s give Ruby something smart to say when it gets there. You’ll take a journey with Haskell’s type system. Along the way, you’ll learn how types can let you forget about nil, declaratively model your domain, and allow your compiler to drive your design.

# Description

How can ANYONE be productive in a language without if/else, while, or even classes? Let me show you! Haskell is proof that sometimes constraints can be liberating. There are murmurs that a type system will be coming to Ruby. Before that happens, you should get informed about what is hot in the current type system market. Haskell is known for it’s type system, but instead of describing it with dense language, let’s take a journey through code examples. Throughout our trip, we will avoid scary buzzwords like “monad” and “algebraic data type” because, honestly, what good is a formal definition when you don’t understand the power behind the concept.

We will compare solutions in Ruby to solutions in Haskell, and each stop on our trip will introduce a new mind blowing paradigm brought to you by Haskell’s type system. You will learn about type systems through a non-threatening story, and you’ll understand the value a type system can bring to your code. Key stops on our route will be “forget about nil”, “declaratively model your domain”, and “allow your compiler to drive your design”.

# Describe Your Presentation Approach

I believe that above all else a talk should be compelling. Content can be illuminating or technically correct, without telling a compelling story. Therefore I believe that it's better to provide illuminating ideas at a high, conceptual level. This technique sparks interest and exploration, rather than provides overwhelming depth. In my opinion, the best way to provide a compelling talk is through the following techniques:

* Simple Slides: There should be few words on slides, and they should be used to focus the audience on what your saying.
* Large Font: Font should be large for readability. This prevents the audience from focusing more on the slides than on your words.
* Many Slides: There should be many slides to keep the audience's attention. The activity will help to provide a sense that the talk is moving and fight boredom.
* Color / Design Contrast: There should be heavy color and design contrast to call attention to different sections, and highlight important main points. Heavy contrast dramatically improves readability, also.
* Repetition: Repetition should be used in a manner similar to storytelling. The goal is to encourage the concept to "stick" by building upon the last occurrence.
* Simple Small Code Examples: Long code examples are overwhelming and hard to parse during a talk. Simple code examples should be used instead. Contrast should be used to call out the important lines or phrases. An entire class / file shouldn't be necessary to provide context. That makes the example too difficult to hold in an audience member's head while trying to listen.

# What Should Audience Take Away

Life After Nil is a friendly display of a type system’s power. Matz said that types are coming to Ruby. We need to learn about types before they’re released. This talk isn’t intended to “sell people” on Haskell, nor is it a cliche “hello world in a new language”.

The audience will take away ideas for better design, and a mild appreciation for Haskell. This talk is really a talk about code design fundamentals using Haskell as the example language. Many talks I've seen about FP and especially Haskell show you ways to write non idiomatic Ruby to shoe-horn shiny FP things into your program. Life After Nil is different. The audience will learn actionable design techniques to improve the Ruby code they're writing, today. Haskell is merely an interesting comparison to help learn the ideas.

The design techniques covered in this talk are:

* The benefits of consistent return types. Haskell's Maybe data type is used to contrast and learn.
* How to declaratively model a domain by using types instead of primitives. And the benefits of controlling transitions within domain objects.
* How to use named domain concepts to break up work. How to compose functionality and transformations into larger concepts.
* How to design an API from the outside in for clean public and private APIs that are by design easy to interact with and test.
