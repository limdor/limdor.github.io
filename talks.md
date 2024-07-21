---
layout: page
title: Talks
permalink: /talks/
---

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
