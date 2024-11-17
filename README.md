# Generative AI Agents and LangGraph Integration

This repository demonstrates practical implementations of Generative AI agents using LangGraph, LangChain, and Gemini APIs, along with Keras for embedding-based applications. The project focuses on equipping language models with the ability to execute tasks, perform real-time data retrieval, and integrate external tools for enhanced decision-making.

## Table of Contents

- [Introduction](#introduction)
- [Project Files](#project-files)
- [Key Concepts](#key-concepts)
- [Setup](#setup)
- [Usage Examples](#usage-examples)
- [References](#references)

## Introduction

Generative AI agents go beyond conventional language models by incorporating external tools and orchestrated cognitive architectures. They have the capability to interact with APIs, perform logic-based actions, and execute tasks autonomously. This repository offers sample code and explanations for building such agents.

## Project Files

1. **`building-an-agent-with-langgraph.ipynb`**: An example of creating a generative AI agent using LangGraph and LangChain. The agent can process complex queries and interact with external data sources.
2. **`function-calling-with-the-gemini-api.ipynb`**: Demonstrates using the Gemini API for function calling, highlighting techniques for integrating external functions in AI workflows.
3. **`Generative AI Agents.pdf`**: A comprehensive whitepaper detailing the architecture, capabilities, and applications of generative AI agents.

## Key Concepts

- **Generative AI Agents**: Intelligent systems that use models, tools, and cognitive architectures to autonomously solve tasks.
- **LangGraph & LangChain**: Libraries for constructing AI agents that perform sequential logic and call external APIs.
- **Function Calling**: Utilizing APIs like Gemini to extend model functionality and handle real-time data retrieval.
- **Cognitive Architectures**: Frameworks such as ReAct, Chain-of-Thought, and Tree-of-Thoughts that guide agent reasoning and decision-making.

## Setup

### Prerequisites

- Python 3.7+
- Libraries: `tensorflow`, `langchain`, `langgraph`, `vertexai`
- API Keys for Gemini and other tools (e.g., SerpAPI, Google Places API)

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/chirucs/Generative-AI-Agents.git
cd Generative-AI-Agents
pip install -r requirements.txt
```

## Usage Examples

### Building a LangGraph Agent

1. Open `building-an-agent-with-langgraph.ipynb`.
2. Follow the instructions to create and test an AI agent with tools for query execution and data retrieval.
3. Customize the agent by adding or modifying tools to suit your application needs.

### Function Calling with Gemini API

1. Load `function-calling-with-the-gemini-api.ipynb`.
2. Set up your API keys and explore how function calls can offload complex tasks from the model to client-side applications.

## References

- **Generative AI Agents Whitepaper**: Explores the theoretical foundations and practical implementations of AI agents.
- **LangChain Documentation**: For advanced use cases and integration techniques.
- **Gemini API**: Access documentation to understand how to set up and use function calls.

