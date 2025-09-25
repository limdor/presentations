# Presentations

Here you can find the slides and material of the different talks that I gave.

List of talks:

* Dynamic memory allocation challenges in safety critical systems

  A program is nothing else than a bunch of instructions modifying chunks of memory based on some inputs to produce some outputs. When these chunks of memory are defined at runtime, we call it dynamic memory allocation. In C++ there are multiple situations where dynamic memory allocation is performed. A user can allocate dynamic memory explicitly in different ways, but dynamic memory allocation can also happen implicitly. There are multiple features of C++ that require dynamic memory allocation, but this is not always necessarily clear to the user. This might become a problem in certain fields. In safety critical systems some guidelines forbid the use of dynamic memory allocation.

  In this talk we will analyse certain features of the C++ library to see if they dynamically allocate or not. We will also learn what are the challenges with dynamic memory allocation in safety critical systems and what alternatives do we have. By the end of the talk you will have gained the knowledge to dynamically allocate memory in safety critical systems in a safer way.

  This talk was presented in:
  * C++ User Group Munich on March 26th, 2025
    [Event](https://www.meetup.com/mucplusplus/events/306803049/)
  * ACCU 2025 on April 3rd, 2025
    [Event](https://accuconference.org/2025/session/dynamic-memory-allocation-challenges-in-safety-critical-systems) - [Slides](./20250403%20-%20ACCU%202025%20-%20Dynamic%20memory%20allocation%20challenges%20in%20safety%20critical%20systems.pdf)

* Everything you need to know about code coverage in C++ (presentation done together with Jorge Pinto Sousa)

  Code coverage is one of the metrics to be considered when you want to deliver high quality software. At the same time, having 100% code coverage does not guarantee you anything.

  In this talk we will explain why you should consider code coverage and what does it mean and does not mean to reach 100%. We will talk about baseline coverage, the different types of code coverage, and what is required by the ISO 26262 standard used in automotive.

  We will also get into the typical code coverage workflow, tracing the journey from raw source code through the process of instrumentation. We'll explore the types of data collected, as well as the intermediate files produced during this phase.

  Our exploration will include a review of various coverage tools, specifically gcov, gcovr, lcov, and llvm-cov, and we'll examine their connection to the Abstract Syntax Tree (AST).

  Additionally, we will highlight several corner case scenarios, including:

  * Branches introduced by compiler optimizations
  * The implications of const, constexpr, and consteval
  * Templates
  
  This talk was presented in:
  * using std::cpp 2024 on April 26th, 2024
    [Event](https://eventos.uc3m.es/105614/programme/using-std-cpp-2024.html) - [YouTube](https://youtu.be/LDtZpE0aKyQ) - [Slides](./20240426%20-%20using%20std%202024%20-%20Everything%20you%20need%20to%20know%20about%20code%20coverage%20in%20C%2B%2B.pdf)

* How to deal with static analysis findings: MISRA

  During software development we have to deal with findings every day. Compilation errors, feedback from code reviews, a code coverage report, etc.

  In this talk you will learn how to deal with findings. In particular, we will focus on static analysis and we will see examples of tooling reporting MISRA C++ violations.

  This talk will be divided in two parts. The first part will be about findings in a generic way, the second part will be about MISRA.

  MISRA provides coding guidelines for developing safety critical system. We will take real findings of MISRA C++violations and we will see how to deal with them. You will also learn about the MISRA Compliance document and how to document deviations.

  By the end of the talk, you will know how to deal with the feedback that you receive every day and also how to provide it.
  
  This talk was presented in:
  * Meeting C++ 2023 on November 13th, 2023
    [Event](https://meetingcpp.com/2023/Talks/items/How_to_deal_with_static_analysis_findings__MISRA.html) - [YouTube](https://youtu.be/ApUc7VEfKkw) - [Slides](./20231113%20-%20Meeting%20C%2B%2B%20-%20How%20to%20deal%20with%20static%20analysis%20findings.pdf)

* Introduction to Bazel to build C++ and Python

  Yet another build system? Why should you learn a new one?

  {Fast, Correct} - Choose two

  that's the motto of Bazel. In this talk I will give an introduction to the open-source build and test tool developed by Google. The first major release was published by the end of 2019. What is so special about Bazel? It is fast, reliable, multi-platform, scalable and extensible. Everything extracted using a high-level build language similar to Python called Starlark. During the talk I will show you how to define libraries, binaries and tests for C++, as well as for Python. In addition I will show you how to combine both languages in a project and how to set up a build toolchain. At the end of the talk I will give you some ideas on extensions that can be added to fit your project and requirements.

  This talk was presented in:
  * code::dive 2020 on November 18th, 2020
    [Event](https://codedive.pl/2020/introduction-to-bazel-to-build-c-and-python) - [Youtube](https://youtu.be/vEQQ9QOVpdU) - [Slides](./20201118%20-%20code%20dive%202020%20-%20Introduction%20to%20Bazel%20to%20build%20C++%20and%20Python.pdf)

* Dependency Management in C++
  
  Proper handling of dependencies in a software development project can make the difference between success and failure. A lot of actors need to be aware of these dependencies: the developer, the compiler, the linker, the build system, the runtime system and so on (even the legal department). This takes special importance in projects that need to scale, not only in the runtime phase but also in the development phase.

  In this presentation, we will go through the different types of dependencies and how they can affect each phase of the project. We will go from the generic point of view with everyday life examples to the singularities of C++ including concepts that are generic for all software development projects. In the last part of the presentation, we will see how Modules introduced in C++20 could change the current scenario regarding dependencies. After this presentation, the audience will have the tools to have a better understanding of the dependencies in their projects.

  Some of the concepts that we will go through are: direct vs transitive dependency, full dependency vs dependency by name, dependency graph, compilation vs runtime dependency.

  This talk was presented in:
  * C++ User Group Munich on October 17th, 2019
    [Event](https://www.meetup.com/MUCplusplus/events/265496392/)
  * code::dive 2019 on November 20th, 2019
    [Event](https://codedive.pl/2019/dependency-management-in-c) - [Youtube](https://youtu.be/dJpAppmRWVI) - [Slides](./20191120%20-%20code%20dive%202019%20-%20Dependency%20management%20in%20C++.pdf)

* sizeof
  
  Lightning talk about the sizeof operator in C++. It shows that to figure out the size of a type is not a trivial task.

  This talk was presented in:
  * C++ User Group Munich on February 5th, 2018
    [Event](https://www.meetup.com/MUCplusplus/events/246748183/) - [Youtube](https://www.youtube.com/watch?v=BWdX6yXFj_Y) - [Slides](./20180205%20-%20MUC++%20Lighting%20Talk%20-%20sizeof.pdf)
