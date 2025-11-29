# Agent Class

A learning repository exploring AI agent architectures using simple math problems as examples. This project demonstrates how agents work using LangGraph, focusing on core concepts like tool calling, state management, memory, and planning.

## Overview

This repository uses simple math problems as a practical way to understand and experiment with agent behavior. By starting with straightforward examples, it's easier to reason about how agents:
- Make decisions
- Call tools
- Maintain state and memory
- Plan multi-step solutions
- Handle asynchronous operations

## Structure

```
math-class/
├── 01_langgraph_adder.ipynb                          # Basic agent with tool calling
├── 02_langgraph_math_problem_with_memory_async_tools.ipynb  # Async tool execution
├── 03_langgraph_math_problem_with_memory.ipynb           # Agent with planning capabilities
└── 04_langgraph_math_problem_planner.ipynb       # Agent with state persistence
```

## Key Concepts Demonstrated

- **Tool Calling**: How agents invoke external functions
- **State Management**: Using LangGraph's StateGraph and MessagesState
- **Memory/Checkpointing**: Persisting conversation state across interactions
- **Conditional Routing**: Decision-making in agent workflows
- **Asynchronous Execution**: Handling async tool calls
- **Planning**: Multi-step problem solving

## Getting Started

1. Install dependencies:
```bash
make install
```

2. Explore the notebooks in the `math-class/` directory, starting with `langgraph_adder.ipynb`

## Dependencies

- LangGraph: Agent orchestration framework
- LangChain: LLM tooling and abstractions
- OpenAI: LLM provider
- LiteLLM: Multi-provider LLM interface

## Why Math Problems?

Simple math problems provide an ideal learning environment because:
- Results are deterministic and verifiable
- Problems can scale in complexity
- Easy to trace agent reasoning
- Clear success/failure criteria
- Minimal domain knowledge required
