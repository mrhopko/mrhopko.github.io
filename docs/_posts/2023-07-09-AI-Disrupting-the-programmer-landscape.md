---
layout: post
title:  "AI Disrupting the Programming Industry"
date:   2023-07-09 09:38:39 +0100
categories: AI, Programming, Future
---

## Coding in Layers

Today, programmers write detailed instructions in large coding projects to tell a dumb machine what we want it to do. Programmers tend to specialise in different layers of the computation stack. From hardware, chip design, Low-level (C, CUDA) to High-level (Python, JavaScript) languages to specialised abstractions like SQL or GUI based tools. Programmers use these layers to differentiate themselves and find jobs. 

## AI Pair-Programming

Pair-programming tools such as GitHub’s co-pilot and AWS' Code Whisperer support (but do not replace) programmers. The tools are great when they have many good examples provided to them in their training data. In my own experience, they are excellent for Python, less so for Rust and Scala. Interestingly, they offer no support for GUI tools. While these tools offer a more productive IDE experience, that alone does not feel transformative. A programmer cannot easily transition between layers using these tools. These tools will not disrupt the job market. 

For the programmers job market to be disrupted, the way that we program or what we program will need to change. Either programmers need to be able to transition between layers, or the layers themselves become obsolete.

## Phase 1: Transitioning between computation layers with the help of AI agents

Today, a programmer focuses on building a codebase at some layer of the computation stack that tells a dumb(ish) machine precisely what to do. When an agent can accept instructions from one layer and implement a program in another, how programmers work with computers changes. 

Prompt engineering is the art of trying to coax an LLM into doing what you want. Another layer may eventually exist that formalises how we interact with our agents. I provide the agent with a project adhering to a certain structure. The agent interprets the structure and writes the instructions for the dumb(ish) machine using the layer of my (or its) choice.

This phase changes the distribution of programmers required between the layers of the tech stack. The capabilities of a programmer will change, along with the types of projects they can create and the pace of development.

There will still need to be an industry of programmers who can build the tools that the agents leverage and guide the agents to the correct path. Programmers will still be able to differentiate themselves by operating at the different layers, offering alternatives when agents don’t make the grade or enhancing agent output. The standard to compete will be higher, as will the value of these individuals.

What will change mostly, is the volume of code being written. A 2 week development sprint now takes an hour. The volume of startups balloons. Software is no longer a market differentiator.

The long tail of problems that AI agents can’t handle will mean this phase drags on with the promise of a perfect agent just over the horizon.

## Phase 2: Layers become obsolete 

Phase 2 starts when the AI agents can build their own tools, their own programming languages, their own layers. In the way that AlphaZero started afresh, ignoring the human approach to chess, the AI agents start solving the problem of programming themselves to the point where programming is purely a thing that AI agents do. They reveal patterns and alternatives that reach beyond our understanding. We use AI to explain what the agents are doing and to put guardrails in place. 

After phase 2, programming has become a thing that machines do. In the same way that computation has been ‘solved’ using computers, programming is solved using programmers (the name we give to the intelligence responsible for building everything we use).

## But when is the future?

I may be in denial, and I'll most certainly be wrong, but I believe Phase 1 is still some years away. Each week that passes, I feel less sure about my position however.

GPT4 and it's plugins is still the strongest system out there, and (I don't think) it can do what is described in phase 1. Microsoft's stake in OpenAI and ownership of Github put it in a dominating position.

GPT Code interpreter shows how capable LLMs can be at solving small problems. I don't know if a model can hold in memory both the microscopic view of code and for example the business context, the users, the security risks, ... A good programmer doesn't just write code, they creatively identify and address real world problems using the tools available while being aware of the context that the solution must eventually thrive in. 

Phase 2 and beyond is a plausible fantasy dreamed up by a geek who loves sci-fi novels. 

While I have no authority with which to claim this has any bearing on reality, it was fun to write.
