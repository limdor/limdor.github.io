---
layout: page
title: WG21 Papers
permalink: /wg21papers/
---

This is the list of papers to improve C++ that I am interested in and I track their status closely:

| Paper | Authors | Github Issue | Status |
| --- | --- | --- | --- |
| [Thread attributes](https://wg21.link/p2019) | Corentin Jabot | [Issue](https://wg21.link/p2019/github) | R7 with prposed SG16 changes approved by LEWG and forwarded to LWG. |
| [Adding an Undefined Behavior and IFNDR Annex](https://wg21.link/p3075) |  Shafik Yaghmour | [Issue](https://wg21.link/p3075/github) | Superseded by P3596. |
| [Core safety profiles for C++26](https://wg21.link/p3081) | Herb Sutter | [Issue](https://wg21.link/p3081/github) | Consensus against inclusion for C++26 but in favor for a whitepaper. Abondoned according the author. |
| [A framework for systematically addressing undefined behaviour in the C++ Standard](https://wg21.link/p3100) | Timus Doumler<br>Joshua Berne | [Issue](https://wg21.link/p3100/github) | R5 version needs to be updated and presented again in EWG for a case-by-case wording review. |
| [Controlling Contract-Assertion Properties](https://wg21.link/p3400) | Joshua Berne | [Issue](https://wg21.link/p3400/github) | R1 seen in SG21. R3 to be seen by EWG. |
| [A Safety Profile Verifying Initialization](https://wg21.link/p3402) | Marc-André Laverdière<br>Christopher Lapkowski<br>Charles-Henri Gros | [Issue](https://wg21.link/p3402/github) | R3 seen in SG23 and polled to forward it to EWG. |
| [Profiles syntax](https://wg21.link/p3447) | Bjarne Stroustrup | [Issue](https://wg21.link/p3447/github) | SG23 liked the syntax. Currently github issue is closed. |
| [Stop the Bleeding but, First, Do No Harm](https://wg21.link/p3498) | Gabriel Dos Reis<br>Thomas Wise<br>Zachary Henkel | [Issue](https://wg21.link/p3498/github) | Informational only. |
| [You shall not pass char* - Safety concerns working with unbounded null-terminated strings](https://wg21.link/p3566) | Marco Foco<br>Joshua Krieghauser<br>Alexey Shevlyakov<br>Giuseppe D'Angelo | [Issue](https://wg21.link/p3566/github) | R0 was seen by SG23 and forwarded to LEWG. R1 was seen by LEWG and requested further work. SG16 also wants to see the paper. |
| [C++ Profiles: The Framework](https://wg21.link/p3589) | Gabriel Dos Rios | [Issue](https://wg21.link/p3589/github) | R2 version seen in EWG and encouraged more work. |
| [Undefined Behavior and IFNDR Annexes](https://wg21.link/p3596) | Joshua Berne<br>Timur Doumler<br>Jens Maurer<br>Shafik Yaghmour | [Issue](https://wg21.link/p3596/github) | It is in CWG. |
| [Dealing with pointer errors: Separating static and dynamic checking](https://wg21.link/p3611) | Bjarne Stroustrup | [Issue](https://wg21.link/p3611/github) | Informational only. |
| [A principled approach to safety profiles](https://wg21.link/p3649) | Jonathan Müller | [Issue](https://wg21.link/p3649/github) | Informational only. |
| [cstring_view](https://wg21.link/p3655) | Peter Bindels<br>Hana Dusíková<br>Jeremy Rifkin<br>Marco Foco<br>Alexey Shevlyakov | [Issue](https://wg21.link/p3655/github) | Multiple direction polls taken. To be seen again by LEWG. |
| [Initial draft proposal for core language UB white paper: Process and major work items](https://wg21.link/p3656) | Herb Sutter<br>Gasper Azman | [Issue](https://wg21.link/p3656/github) | R1 seen by EWG and agreed on the strategy proposed. |
| [Making Safe C++ happen](https://wg21.link/p3700) | Peter Bindels | [Issue](https://wg21.link/p3700/github) | More worked was encouraged after seeing R0 in SG23 and EWG. |
| [What are profiles?](https://wg21.link/p3704) | Bjarne Stroustrup | [Issue](https://wg21.link/p3704/github) | Informational only. |
| [Safer StringViewLike Functions for Replacing char* strings](https://wg21.link/p3711) | Marco Foco | [Issue](https://wg21.link/p3711/github) | No consensus to dedicate more time. |
| [Subsetting](https://wg21.link/p3716) | Peter Bindels | [Issue](https://wg21.link/p3716/github) | More worked was encouraged after seeing R0 in SG23. |
| [A gentle introduction to pointer authentication](https://wg21.link/p3751) | Oliver Hunt<br>John McCall | [Issue](https://wg21.link/p3751/github) | Informational only. |
| [A type-safety profile](https://wg21.link/p3984) | Bjarne Stroustrup | [Issue](https://wg21.link/p3984/github) | R0 was seen and SG23 and polled showing support. |
| [A proposed plan for profiles in C++](https://wg21.link/p4186) | Peter Bindels | [Issue](https://github.com/cplusplus/papers/issues/2742) | |

This is the list of papers to improve C++ that I am involved as an author:

| Paper | Authors | Github Issue | Status |
| --- | --- | --- | --- |
| [is_*_type should imply is_type](https://wg21.link/p3781) | Xavier Bonaventura | [Issue](https://wg21.link/p3781/github) | Discussed in [SG20 Telecon on October 2025](https://github.com/cplusplus/papers/issues/2391#issuecomment-3488201783). Rejected by [LEWG in Kona meeting](https://github.com/cplusplus/nbballot/issues/760#issuecomment-3707439116). |
| [mdspan.at()](https://wg21.link/p3383) | Stephan Lachnit<br>Xavier Bonaventura | [Issue](https://wg21.link/p3383/github) | Approved for C++26. Available in the [latest C++ draft](https://eel.is/c++draft/mdspan.mdspan.members). |
| [Allow `[[nodiscard]]` in type alias declarations](https://wg21.link/p3245) | Xavier Bonaventura | [Issue](https://wg21.link/p3245/github) | Rejected (I have no plan to continue purusing this paper. After initial feedback it was seen that cost/benefit is not worth it.) |
