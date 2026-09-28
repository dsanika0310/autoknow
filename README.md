# AutoKnow

## Enterprise GenAI Technical Knowledge Assistant for Automotive Engineering Teams

AutoKnow is an independent proof-of-concept exploring how retrieval-augmented
generation (RAG) can help engineering teams retrieve information from approved
technical documentation.

## Problem

Engineering organisations work with large volumes of technical documentation,
including manuals, specifications, procedures, and reference material.

Finding relevant information across multiple documents can be time-consuming,
and general-purpose language models may produce answers that are not grounded
in approved technical sources.

## Proposed Solution

AutoKnow retrieves relevant sections from a controlled technical-document
knowledge base and provides them to a language model to generate an answer.

Each answer should:

- use information from the provided documents;
- identify its supporting source;
- avoid answering when sufficient evidence cannot be found.

## Target Users

- Engineers
- Project coordinators
- Technical support teams
- New employees learning technical systems

## Project Goals

1. Build a small RAG-based technical knowledge assistant.
2. Return source-grounded answers.
3. Evaluate retrieval and answer quality using a predefined question set.
4. Explore the business value and risks of deploying this type of system
   within an enterprise engineering environment.

## Scope

This is an educational proof of concept using only publicly available or
synthetic technical documentation.

No confidential company information is used.
