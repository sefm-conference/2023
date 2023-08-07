---
layout: page
title: Keynote Speakers
permalink: /keynotes/
order: 3
---

## [Burcu Ozkan](https://burcuku.github.io/home/), TU Delft

<img src="{{ site.baseurl }}{% link assets/burcu.jpg %}" class="imageSpeaker" align="right"/>

**Randomized Testing of Distributed Systems**

Distributed systems are prone to concurrency bugs due to the nondeterminism in the interleavings of the concurrent events in an execution. Detecting and diagnosing concurrency bugs in distributed systems is critical since unforeseen interleavings of concurrent messages, network, or process faults can result in unexpected, erroneous system behavior. However, concurrency bugs are hard to detect as they are triggered only in some subtle interleavings of the events.

Random testing is a practical way of searching for bugs in large distributed systems. While naïve random stress testing is unlikely to discover bugs that rarely occur, recent randomized testing algorithms offer effective testing methods. They provide theoretical guarantees on detecting bugs based on combinatorial results and borrowing ideas from formal methods and verification. In this talk, we will overview the key ideas in randomized testing techniques for detecting concurrency bugs in distributed systems.

## [Reiner Hähnle](https://www.informatik.tu-darmstadt.de/se/gruppenmitglieder/groupmembers_detailseite_30784.en.jsp), TU Darmstadt

<img src="{{ site.baseurl }}{% link assets/reiner.jpg %}" class="imageSpeaker" align="right"/>

**Context-aware Trace Contracts**

The behavior of concurrent, asynchronous procedures depends in general on the call context, because of the global protocol that governs scheduling. This context cannot be specified with the state-based Hoare-style contracts common in deductive verification. Recent work generalized state-based to trace contracts, which permit to specify internal behavior of a procedure, such as calls or state changes, but not its call context. In this talk we discuss a program logic of context-aware trace contracts for specifying global behavior of asynchronous programs. We also provide a sound proof system that addresses two challenges: To observe the program state not merely at the end points of a procedure, we introduce the novel concept of an observation quantifier. And to combat combinatorial explosion of possible call sequences of procedures, we transfer Liskov's principle of behavioral subtyping to the analysis of asynchronous procedures.

Joint work with: Eduard Kamburjan (U Oslo), Marco Scaletta (TU Darmstadt)