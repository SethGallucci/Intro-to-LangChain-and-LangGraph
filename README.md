# Intro to LangChain and LangGraph

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19taxlzrhxdoPcLxNEeGID5jZvYN4IIcP?usp=sharing)

A beginner-friendly, surface-level introduction to LangChain and LangGraph designed to run in Google Colab.

This notebook walks through the core ideas behind modern LLM application development using practical, progressively more advanced examples. It is intended for learners who want to understand how prompt pipelines evolve into structured workflows, graphs, agents, and stateful systems.

*Note:* This notebook was part of a presentation. As such, you may find explanation in the notebook to be sparse. Regardless, for those who are at least moderately versed in Python, it's a useful starting point for experimenting with LangChain and LangGraph.

## Quick-Start

1. Open in Google Colab  
2. Add your Groq API key  
3. Run cells top to bottom  
4. Experiment with examples

## What You'll Learn

### LangChain Basics

Learn how to build simple LLM pipelines using:

- Prompt templates
- Model invocation
- Output parsing
- Structured responses with Pydantic
- Chaining components together

Examples progress through:

1. **Basic Pipe:** text in, text out
2. **Structured Output:** forcing reliable schemas
3. **Parallel Execution:** combining multiple branches of work

### LangGraph Basics

Move beyond linear chains into graph-based workflows with:

- Shared state
- Nodes
- Directed edges
- Conditional routing
- Loops
- Memory
- Human-in-the-loop systems

Examples include:

1. **Basic Graph:** simple state transitions
2. **Loops:** demonstrated with the Collatz Conjecture
3. **Human-in-the-Loop Agent:** review and approval flow

## Applied Mini Projects

The notebook finishes with more open-ended examples showing how these tools can be used in real systems:

### US State Guessing Game

An interactive graph-based game where the model asks questions to infer of which U.S. state the user is thinking.

### Medical Exam Grader

A prototype workflow combining retrieval and evaluation logic to score answers using a small medical knowledge corpus.

## Why This Notebook Exists

Many tutorials jump straight into complex agents or production systems. This notebook is intended for users who already know Python and want a practical introduction to LangChain and LangGraph. It focuses on:

- What LangChain is good at
- When LangGraph becomes useful
- How workflows become more structured over time
- How to think in nodes, state, and routing

## Requirements

You will need:
- Access to Google Colab.
- A Groq API key (https://console.groq.com/keys)

## How to Run

1. Open the notebook in Google Colab
2. Run the setup cells (packages may take some time to install)
3. Add your Groq API key
4. Execute cells top to bottom, at your own pace
5. Modify prompts and examples to experiment


## Intended Audience

This notebook is ideal for:

- Beginners learning LLM tooling
- Students exploring AI orchestration frameworks
- Anyone wanting practical intuition before deeper study

## Notes

This notebook is intentionally introductory. It prioritizes simplicity and clarity over production-grade patterns and engineering best practices.

If you want to build real systems afterward, next topics to explore include:

- Tool calling
- Retrieval-Augmented Generation (RAG)
- Persistent memory
- Multi-agent systems
- Evaluation pipelines
- Deployment