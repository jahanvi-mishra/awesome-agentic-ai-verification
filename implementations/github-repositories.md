# GitHub Implementations

This file contains GitHub repositories related to agentic AI, AI agents,
evaluation, tool use, and verification.

## 1. AutoGen

Link: https://github.com/microsoft/autogen

AutoGen is a framework for creating applications using multiple AI agents.
Agents can communicate with each other and use tools to complete tasks.

Why relevant:
It is useful for studying multi-agent workflows and checking whether
communication and task delegation happen correctly.

## 2. LangGraph

Link: https://github.com/langchain-ai/langgraph

LangGraph is used to build stateful and multi-step agent workflows.

Why relevant:
Its graph-based workflow structure makes it suitable for implementing
verification checkpoints between different stages of an agent pipeline.

## 3. AgentBench

Link: https://github.com/THUDM/AgentBench

AgentBench is a benchmark and evaluation framework for testing LLMs as
agents in different environments.

Why relevant:
It can be used to evaluate agent performance on interactive and
multi-step tasks and identify where failures occur.

## 4. SWE-bench

Link: https://github.com/SWE-bench/SWE-bench

SWE-bench provides a benchmark for evaluating AI systems on real-world
software engineering problems from GitHub.

Why relevant:
It is useful for evaluating agents that need to reason, modify files,
use tools, and complete several steps before producing a solution.

## 5. AgentDojo

Link: https://github.com/ethz-spylab/agentdojo

AgentDojo is a framework and environment for evaluating security of
LLM agents that interact with tools and external information.

Why relevant:
It is directly related to agent security and can be used to test whether
verification mechanisms prevent unsafe or manipulated agent actions.

## 6. WebArena

Link: https://github.com/web-arena-x/webarena

WebArena provides realistic web environments for evaluating autonomous
agents.

Why relevant:
It can be used to test agents on browsing and multi-step web tasks and
observe failures during tool interaction.

## Summary

Number of GitHub implementations included: 6

These repositories provide practical implementations and evaluation
environments related to agent development, tool use, workflow management,
benchmarking, and security.
