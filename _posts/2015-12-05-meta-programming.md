---
title: "What is Meta-Programming?"
subtitle: "A non-technical perspective"
categories: General
---
<em>(Note images and figures for better visual understanding to follow)</em>

In this article I want to share my search for understanding what `Meta-programming` means and its potentital for creating [Meta](/about/ "Computer that learns, thinks, decides, and acts").
<!--more-->
My initial approach in searching was to use `Meta-programming` as the keyword. These gave me the following defintions:

> Meta-programs are programs that manipulate other program. - - <cite>Martin Berger and Laurence Tratt; [Program Logics for Homogenous Meta-Programming](http://users.sussex.ac.uk/~mfb21/publications/lpar10/lpar10.pdf)</cite>

> Meta-programming is the generation or manipulation of programs, or parts of programs, by other programs, i.e. in an algorithmic way. - - <cite>Tim Sheard; [Accomplishments and research challenges in Meta-Programming](https://cs.uwaterloo.ca/~melsheik/thesis/thesis/node29.html)

> Metaprogramming is the act of writing code that operates on code rather than on data. This involves inspecting and modifying a program as it runs using constructs exposed by the language. - - <cite>[Rubymonk](https://rubymonk.com/learning/books/2-metaprogramming-ruby/chapters/32-introduction-to-metaprogramming/lessons/75-being-meta)</cite>

With these first definitions that I got, what I gather is that `Meta-Programming` is an approach that allows me to create an application that will manipulate not just data but also code. If this is anything like the typical data manipulation, then this means for me that I should be able to create, read, update, and delete programns (CRUD).

> Metaprogramming refers to a variety of ways a program has knowledge of itself or can manipulate itself. - - <cite>[DavGarcia](http://stackoverflow.com/questions/514644/what-exactly-is-metaprogramming/514697#514697)</cite>

> Metaprogramming is the writing of computer programs with the ability to treat programs as their data. It means that a program could be designed to read, generate, analyse or transform other programs, and even modify itself while running. - - <cite>[Wikipedia](https://en.wikipedia.org/wiki/Metaprogramming)</cite>

Upon further exploration, the following definitions made it more interesting in that it describes `Meta-programming` as having the capabiility to manipulate itself on the fly. While, the following defintions, *<u>technically</u>* suggests that it is possible to create [Meta](/about/ "Computer that learns, thinks, decides, and acts"), it is not yet apparent from a "conceptual" point of view what `Meta-programming` means and is potentially capable of. It also isn't clear to what degree manipulating programs/code will allow a computer to learn, think, decide, and act.

For the remainder of this article, I will look into the former and see what possibilities the conceptual defintion hold for `Meta-programming`.

* * *

### A Conceptual Definition

I started by first getting the definition for *"Computer Programming"* since it should be the more common of the two words (meta being the other). The following are defintions that I found and like.

> A computer is a simple device that knows how to remember things and how to look up those memories. At its core, that's all it does. It starts out with a blank slate of memory and relies on a human to tell it what to do with that memory.. A program is a set of instructions for managing that memory. - - <cite>[outspeaking.com](http://outspeaking.com/words-of-technology/what-is-programming.html)</cite>

> The purpose of programming is to find a sequence of instructions that will automate performing a specific task or solving a given problem. - - <cite>[Wikipedia](https://en.wikipedia.org/wiki/Computer_programming)</cite>

With these, it is made clear is that *Computers* alone can not learn, think, decide, and act. It needs human intervention to be able to perform a set of tasks or solve a problem. Following this, I looked up `Meta` and I came upon this interesting discussion from stackexchange about `Meta` being `self-referential`:

> It originally meant something like "after". Possibly the most prominent use of this sense is the title of Aristotle's Metaphysics, so called because it constitutes those things which are to be studied after one has learned physics.
This text wound up founding the discipline which we today call "metaphysics", and one way to describe what this subject encompasses is that it covers things at a level of abstraction above physics.
This sort of meaning became applied retroactively to the prefix, and we began building words in that sense, often by applying the root word to itself. Take for example metaknowledge, knowledge at a higher level of abstraction than standard knowledge, or knowledge about knowledge. Eventually, this reflexive sense became a new usage in its own right. - - <cite>[Malnormalulo](http://english.stackexchange.com/questions/245403/how-did-meta-come-to-mean-self-referential)</cite>

The above discussion leads to me to the idea that meta-programming is *<u>"making programs that program"</u>* (see also snippet from wiki on "Meta")
 
>  The modern sense of "an X about X" has given rise to concepts like "meta-cognition" (i.e. cognition about cognition), "meta-emotion" (i.e. emotion about emotion), "meta-discussion" (i.e. discussion about discussion), "meta-joke" (i.e. joke about jokes), and "metaprogramming" (i.e. writing programs that manipulate programs). - - <cite>[Wikipedia](https://en.wikipedia.org/wiki/Meta)</cite>

The key take away I got from this searching exercise is that appending `Meta` to `Programming` suggests that a layer of abstraction is added to the typical programming. I see this as a way that a program is able to elevate itself and look at programs as something that it can manipulate. It even suggests that a level of autonomy from human intervention can be gained. If previously, human intervention is needed for the program to do a task, the layer of abstraction suggests that __*even*__ just a program can create tasks for another program. I also see the current idea of `Meta` having a **self-referential** connotation to further support the idea that a computer will be able to learn, think, decide, and act on its **"own"**. Being self-referential, I imagine that computers would be able to look at its own capabilities and derive from it something different, and consequently repeat this process and evolve itself. 