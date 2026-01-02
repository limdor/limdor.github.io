---
layout: page
title: Talks
permalink: /talks/
---

{% capture dynamic_memory_allocation_description %}
A program is nothing else than a bunch of instructions modifying chunks of memory based on some inputs to produce some outputs. When these chunks of memory are defined at runtime, we call it dynamic memory allocation. In C++ there are multiple situations where dynamic memory allocation is performed. A user can allocate dynamic memory explicitly in different ways, but dynamic memory allocation can also happen implicitly. There are multiple features of C++ that require dynamic memory allocation, but this is not always necessarily clear to the user. This might become a problem in certain fields. In safety critical systems some guidelines forbid the use of dynamic memory allocation.

In this talk we will analyse certain features of the C++ library to see if they dynamically allocate or not. We will also learn what are the challenges with dynamic memory allocation in safety critical systems and what alternatives do we have. By the end of the talk you will have gained the knowledge to dynamically allocate memory in safety critical systems in a safer way.
{% endcapture %}

{% include talk.html
    title="Dynamic memory allocation challenges in safety critical systems"
    description=dynamic_memory_allocation_description
    youtube_video_id="B54oCS4qdU8"
%}

{% capture coverage_description %}
Code coverage is one of the metrics to be considered when you want to deliver high quality software. At the same time, having 100% code coverage does not guarantee you anything.

In this talk we will explain why you should consider code coverage and what does it mean and does not mean to reach 100%. We will talk about baseline coverage, the different types of code coverage, and what is required by the ISO 26262 standard used in automotive.

We will also get into the typical code coverage workflow, tracing the journey from raw source code through the process of instrumentation. We'll explore the types of data collected, as well as the intermediate files produced during this phase.

Our exploration will include a review of various coverage tools, specifically gcov, gcovr, lcov, and llvm-cov, and we'll examine their connection to the Abstract Syntax Tree (AST).

Additionally, we will highlight several corner case scenarios, including:

* Branches introduced by compiler optimizations
* The implications of const, constexpr, and consteval
* Templates
{% endcapture %}

{% include talk.html
    title="Everything you need to know about code coverage in C++ (presentation done together with Jorge Pinto Sousa)"
    description=coverage_description
    youtube_video_id="LDtZpE0aKyQ"
%}

{% capture static_analysis_description %}
During software development we have to deal with findings every day. Compilation errors, feedback from code reviews, a code coverage report, etc.

In this talk you will learn how to deal with findings. In particular, we will focus on static analysis and we will see examples of tooling reporting MISRA C++ violations.

This talk will be divided in two parts. The first part will be about findings in a generic way, the second part will be about MISRA.

MISRA provides coding guidelines for developing safety critical system. We will take real findings of MISRA C++violations and we will see how to deal with them. You will also learn about the MISRA Compliance document and how to document deviations.

By the end of the talk, you will know how to deal with the feedback that you receive every day and also how to provide it.
{% endcapture %}

{% include talk.html
    title="How to deal with static analysis findings: MISRA"
    description=static_analysis_description
    youtube_video_id="ApUc7VEfKkw"
%}

{% capture introduction_to_bazel_description %}
Yet another build system? Why should you learn a new one?

{Fast, Correct} - Choose two

that's the motto of Bazel. In this talk I will give an introduction to the open-source build and test tool developed by Google. The first major release was published by the end of 2019. What is so special about Bazel? It is fast, reliable, multi-platform, scalable and extensible. Everything extracted using a high-level build language similar to Python called Starlark. During the talk I will show you how to define libraries, binaries and tests for C++, as well as for Python and Rust. In addition I will show you how to combine languages in a project and how to set up a build toolchain. At the end of the talk I will give you some ideas on extensions that can be added to fit your project and requirements.
{% endcapture %}

{% include talk.html
    title="Introduction to Bazel"
    description=introduction_to_bazel_description
    youtube_video_header="Presentation at NDC Techtown 2025 (Updated version of the code::dive edition)"
    youtube_video_id="R_EyoO3YGxk"
    youtube_video_additional_header="Presentation at code::dive 2020 (Outdated and without Rust)"
    youtube_video_additional_id="vEQQ9QOVpdU"
%}

{% capture dependency_management_description %}
Proper handling of dependencies in a software development project can make the difference between success and failure. A lot of actors need to be aware of these dependencies: the developer, the compiler, the linker, the build system, the runtime system and so on (even the legal department). This takes special importance in projects that need to scale, not only in the runtime phase but also in the development phase.

In this presentation, we will go through the different types of dependencies and how they can affect each phase of the project. We will go from the generic point of view with everyday life examples to the singularities of C++ including concepts that are generic for all software development projects. In the last part of the presentation, we will see how Modules introduced in C++20 could change the current scenario regarding dependencies. After this presentation, the audience will have the tools to have a better understanding of the dependencies in their projects.

Some of the concepts that we will go through are: direct vs transitive dependency, full dependency vs dependency by name, dependency graph, compilation vs runtime dependency.
{% endcapture %}

{% include talk.html
    title="Dependency Management in C++"
    description=dependency_management_description
    youtube_video_id="dJpAppmRWVI"
%}

{% capture sizeof_description %}
Lightning talk about the sizeof operator in C++. It shows that to figure out the size of a type is not a trivial task.
{% endcapture %}

{% include talk.html
    title="sizeof"
    description=sizeof_description
    youtube_video_id="BWdX6yXFj_Y"
%}
