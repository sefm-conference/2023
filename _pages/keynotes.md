---
layout: page
title: Keynotes
permalink: /keynotes/
order: 3
---

## [Burcu Kulahcioglu Ozkan](https://burcuku.github.io/home/), TU Delft

<img src="{{ site.baseurl }}{% link assets/burcu.jpg %}" class="imageSpeaker" align="right"/>

**Randomized Testing of Distributed Systems**

Distributed systems are prone to concurrency bugs due to the nondeterminism in the interleavings of the concurrent events in an execution. Detecting and diagnosing concurrency bugs in distributed systems is critical since unforeseen interleavings of concurrent messages, network, or process faults can result in unexpected, erroneous system behavior. However, concurrency bugs are hard to detect as they are triggered only in some subtle interleavings of the events.

Random testing is a practical way of searching for bugs in large distributed systems. While naïve random stress testing is unlikely to discover bugs that rarely occur, recent randomized testing algorithms offer effective testing methods. They provide theoretical guarantees on detecting bugs based on combinatorial results and borrowing ideas from formal methods and verification. In this talk, we will overview the key ideas in randomized testing techniques for detecting concurrency bugs in distributed systems.

## [Reiner Hähnle](https://www.informatik.tu-darmstadt.de/se/gruppenmitglieder/groupmembers_detailseite_30784.en.jsp), TU Darmstadt

<img src="{{ site.baseurl }}{% link assets/reiner.jpg %}" class="imageSpeaker" align="right"/>

**Context-aware Trace Contracts**

The behavior of concurrent, asynchronous procedures depends in general on the call context, because of the global protocol that governs scheduling. This context cannot be specified with the state-based Hoare-style contracts common in deductive verification. Recent work generalized state-based to trace contracts, which permit to specify internal behavior of a procedure, such as calls or state changes, but not its call context. In this talk we discuss a program logic of context-aware trace contracts for specifying global behavior of asynchronous programs. We also provide a sound proof system that addresses two challenges: To observe the program state not merely at the end points of a procedure, we introduce the novel concept of an observation quantifier. And to combat combinatorial explosion of possible call sequences of procedures, we transfer Liskov's principle of behavioral subtyping to the analysis of asynchronous procedures.

Joint work with: Eduard Kamburjan (U Oslo), Marco Scaletta (TU Darmstadt)

## [Mira Mezini](https://www.stg.tu-darmstadt.de/main_stg/staff_stg/mira_mezini_1.en.jsp), TU Darmstadt

<img src="{{ site.baseurl }}{% link assets/mira.jpg %}" class="imageSpeaker" align="right"/>

**Safe and Secure Programming Abstractions for Decentralized Software**

Today’s computing infrastructure is massively distributed across geo-replicated clouds in the back-end and millions of increasingly powerful devices in the front-end. Applications running on this massively distributed infrastructure are different from traditional distributed applications – they often interact with their surroundingsand their execution flow is not determined by these unpredictable interactions. While today’s software architecture is centralized with data and computations mostly hosted in back-end clouds and front-end devices merely interfacing to the world, there is a call for decentralization, motivated by requirements for privacy, latency, availability (even for deployments with intermittent connectivity in the front-end), and made possible by increased resources in the front-end. But decentralization brings back long-standing challenges of distributed software on the table of application developers, which are amplified due to global distribution, the quest for decentralization, and the interactive nature of applications. At the same time, our programming methods are not up to these challenges, leaving complexity on the shoulders of application developers to manage. 

In this talk, I will present ongoing work on the REScala project, which aims to close this gap. REScala – a library-based extension of the Scala language - advances the state of scientific knowledge in the area of programming foundations for distributed interactive learning applications. It makes decentralization and interactivity first-class programming principles. Computations running on individual nodes of the computing infrastructure have their local view on data and execution, but these views are composable by-design with guaranteed safety and security properties. Moreover, the views have native time-changing capabilities, whichenables them to jointly evolve in time and space.