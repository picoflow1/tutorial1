---
title: 'Tutorial: Hotel Reservation'
nextPage: '[[1|Lesson 1: Introduction & Setup]]'
---

Over the past 2.5 years, we have been designing and implementing LLM-driven systems from first principles. Our early implementations directly leveraged vendor-provided SDKs and APIs. When LangChain introduced a generalized abstraction layer for LLM orchestration, we adopted it to streamline model integration and prompt management. Despite this, the orchestration of end-to-end business flows remained largely manual and application-specific. To address this, we incrementally developed an internal framework — a lightweight, homegrown version of an Agentic flow engine — continuously refining it as our understanding of Agentic patterns, prompt chaining, and contextual state management evolved. 


> [!Note]
> Our primary domain of expertise lies in building mechanisms that enable non-AI developers to transform conventional business workflows into AI-augmented pipelines. 
> 
> This is achieved by programmatically injecting LLM-based decision and interaction nodes into existing deterministic processes, allowing organizations to `Botify` legacy operations with minimal disruption to their underlying logic. 
>

In parallel, we have engineered some of the most sophisticated conversational agents in production today — capable of replacing traditional web or mobile interfaces by translating user intent directly into actionable operations. As the Agentic ecosystem matured, we conducted a systematic benchmarking of our internal library against industry-leading frameworks, notably LangChain and LangGraph. 
- The evaluation criteria included 
  - architectural modularity, 
  - abstraction clarity, 
  - traceability, observability, 
  - replay-ability, 
  - and developer friendliness. 

The resulting framework, Picoflow, diverges from LangGraph in both philosophy and architecture. Whereas LangGraph emphasizes graph-based task decomposition at a lower level of abstraction, Picoflow focuses a turnkey solution that allows a non-LLM developer to become productive with easy to comprehend, super modular, reusable and composable flow semantics optimized for JavaScript ecosystems. Despite these differences, both share the goal of enabling scalable, observable, and maintainable Agentic systems. 

> [!Note]
> Ultimately, Picoflow provides an opinionated, (battery included), production-ready orchestration framework that enables JavaScript developers to build complex, AI-native business applications with minimal friction and maximum productivity — achieving rapid productivity without sacrificing control or observability. 
> 
> Picoflow can be deploy to any docker environment.
>

A summarized high level comparison chart to LangGraph can be found here:
<a href="https://www.picoflow.io/comparison.html">Picoflow vs. LangGraph</a>


**A word about this tutorial**
> [!TIP]
> This tutorial is a demonstration of how to use Picoflow effectively.
> We created a databases of Hilton Hotels in Portland Oregon and south Washington areas. 
> Each hotel has a reasonable amount of attributes similar to the real hotel. 
> We also create a pricing engine that will reflect on a variety of conditions such as amenities choices, room types, holidays, weekends, distance from airport/city center, etc.  
>




Ready? Let's get started!
Head over to the first lesson by clicking the "Lesson 1: Introduction & Setup" link below.
