# Presentations

Here you can find the slides and material of the different talks that I gave.

List of talks:

* sizeof
  
  Lightning talk about the sizeof operator in C++. It shows that to figure out the size of a type is not a trivial task.

  This talk was presented in:
  * C++ User Group Munich on February 5th, 2018
    [Event](https://www.meetup.com/MUCplusplus/events/246748183/) - [Youtube](https://www.youtube.com/watch?v=BWdX6yXFj_Y) - [Slides](./20180205%20-%20MUC++%20Lighting%20Talk%20-%20sizeof.pdf)

* Dependency Management in C++
  
  Proper handling of dependencies in a software development project can make the difference between success and failure. A lot of actors need to be aware of these dependencies: the developer, the compiler, the linker, the build system, the runtime system and so on (even the legal department). This takes special importance in projects that need to scale, not only in the runtime phase but also in the development phase.

  In this presentation, we will go through the different types of dependencies and how they can affect each phase of the project. We will go from the generic point of view with everyday life examples to the singularities of C++ including concepts that are generic for all software development projects. In the last part of the presentation, we will see how Modules introduced in C++20 could change the current scenario regarding dependencies. After this presentation, the audience will have the tools to have a better understanding of the dependencies in their projects.

  Some of the concepts that we will go through are: direct vs transitive dependency, full dependency vs dependency by name, dependency graph, compilation vs runtime dependency.

  This talk was presented in:
  * C++ User Group Munich on October 17th, 2019
    [Event](https://www.meetup.com/MUCplusplus/events/265496392/)
  * code::dive 2019 on November 20th, 2019
    [Event](https://codedive.pl/2019/dependency-management-in-c) - [Youtube](https://youtu.be/dJpAppmRWVI) - [Slides](./20191120%20-%20code%20dive%202019%20-%20Dependency%20management%20in%20C++.pdf)

* Introduction to Bazel to build C++ and Python

  Yet another build system? Why should you learn a new one?

  {Fast, Correct} - Choose two

  that's the motto of Bazel. In this talk I will give an introduction to the open-source build and test tool developed by Google. The first major release was published by the end of 2019. What is so special about Bazel? It is fast, reliable, multi-platform, scalable and extensible. Everything extracted using a high-level build language similar to Python called Starlark. During the talk I will show you how to define libraries, binaries and tests for C++, as well as for Python. In addition I will show you how to combine both languages in a project and how to set up a build toolchain. At the end of the talk I will give you some ideas on extensions that can be added to fit your project and requirements.

  This talk will be presented in:
  * code::dive 2020 on November 20th, 2019
    [Event](https://codedive.pl/2020/introduction-to-bazel-to-build-c-and-python) - [Conference registration](https://register.codedive.pl/register/participant) - [Youtube (live streaming - Stage 1 - 15:15 - 16:15 CET)](https://youtu.be/SUnaA-HYshY) - [Slides](./20201118%20-%20code%20dive%202020%20-%20Introduction%20to%20Bazel%20to%20build%20C++%20and%20Python.pdf)
