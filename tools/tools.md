# Tools and Libraries

This file contains tools, libraries, and platforms that can be useful for
building, testing, evaluating, and verifying agentic AI systems.

## 1. LangChain

Link: https://github.com/langchain-ai/langchain

LangChain is a framework for developing applications using large language
models. It provides components for prompts, tools, agents, retrieval, and
workflow development.

Why relevant:
It can be used to build agentic workflows where different stages can be
tested and verified separately.

## 2. AutoGen

Link: https://github.com/microsoft/autogen

AutoGen is a framework for building applications involving multiple AI
agents and agent conversations.

Why relevant:
It is useful for experimenting with multi-agent systems and checking
communication, tool use, and task delegation between agents.

## 3. LlamaIndex

Link: https://github.com/run-llama/llama_index

LlamaIndex provides tools for connecting language models with external
data and building retrieval-augmented applications and agents.

Why relevant:
It can help in building systems where retrieved information needs to be
checked before being passed to later stages of an agent workflow.

## 4. LangGraph

Link: https://github.com/langchain-ai/langgraph

LangGraph is a framework for building stateful and multi-step agent
workflows.

Why relevant:
Its graph-based workflow structure makes it useful for adding checks
between different stages of an agent pipeline and handling failures or
recovery steps.

## 5. RAGAS

Link: https://github.com/explodinggradients/ragas

RAGAS is a framework for evaluating retrieval-augmented generation systems.
It provides metrics for evaluating aspects such as faithfulness, relevance,
and retrieval quality.

Why relevant:
It can be used to evaluate intermediate retrieval and generation stages
instead of checking only the final response.

## 6. OpenAI Evals

Link: https://github.com/openai/evals

OpenAI Evals is an evaluation framework for testing AI models and systems
using different evaluation criteria and test cases.

Why relevant:
Evaluation frameworks such as this can be used to create repeatable tests
for detecting errors and checking whether an agent behaves as expected.

## 7. Inspect AI

Link: https://github.com/UKGovernmentBEIS/inspect_ai

Inspect AI is an open-source framework for evaluating language models and
AI systems.

Why relevant:
It can be used to create structured evaluations and tests for AI systems,
which is useful when designing verification and reliability checks.

## 8. Local Model Calibration Kit

Link: https://github.com/charlesdvaught-hash/calibration-kit-public

A runtime verification checkpoint for local LLM code generation. It runs
as an OpenAI-compatible proxy between an agent harness and the inference
server, scoring each generation's likelihood of being wrong from per-token
logprob statistics calibrated per model on the user's own tasks, and
returns a verdict plus ranked recovery interventions before tests run.

Why relevant:
It is a concrete implementation of an intermediate verification
checkpoint: silent wrongness in generated code is flagged at generation
time rather than discovered downstream, and gate mode can regenerate
likely-wrong responses before they propagate. Methodology and calibration
evidence are public in the linked repository; full per-model evidence
reports are published at
https://charlesdvaught-hash.github.io/calibration-kit-public/

## Summary

Number of tools and libraries included: 8

These tools cover agent development, multi-agent systems, retrieval,
stateful workflows, evaluation, and reliability testing.
