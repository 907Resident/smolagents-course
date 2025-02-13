# Unit 01: Introduction to Agents

## Introduction

Through this course, will cover the specific model family know as Agents and how they work as well as how Agents make decisions through reasoning and planning. Additionally, this course will speak to how LLMs are the brain of the Agent. Furthermore, we will learn how tools and actions are used by the Agent to interact with its surrounding environment.

## What is an Agent?

Hugging Face created Alfred to demonstrate what an Agent is. It is defined as: an AI model capable of reasoning, planning, and interacting with its environment. There are two main components of an Agent: 1) The Brain (the LLM) and 2) The Body (Tools and Abilities).

## What type of tasks can an Agent do?

Agents can perform capabilities and tasks to complete actions using tools. The tools can be defined with constructions as simple as a pythonic function.

## What are LLMs?

Hugging Face provides the following definition for large language models (LLMs):

> An AI model that excels at understanding and generating human language.

These models are built using the [Transformer architecture](https://www.geeksforgeeks.org/architecture-and-working-of-transformers-in-deep-learning/), which resides in the family of deep learning.

This architecture rose into prominence through its key feature called _attention_. The attention mechanism is sort of like a spotlight on a stage. The attention mechanism shines on the performer of interest on the stage so that they are most visible among the rest of the components and people on stage. Together, the illuminated performer and the backlit actors and props are the input data into the model, but the spotlight serves as the attention mechanism ensuring that the most important information is clearly visible.

This mechanism, published by Google researchers in 2017, has fortified LLMs with the ability to process information from long sequences of unstructured data (i.e., text, audio, images). This growth from the memory fallible recurrent neural networks (RNNs) has enabled LLMs built with this architecture to be able to work with very long sequences of text.

There are three types of transformers:

1. Encoders
   - Consumes text (and other unstructured data) and churns out a dense representation of the text
   - These models are adept at providing a discretizing understanding of 
2. Decoders
   - Instead of generating a dense representation of the text, decoder transformers focus on generating a new token in a sequential fashion
   - This type of transformer is largely found underlying the AI chat applications that you may use
3. Seq2Seq