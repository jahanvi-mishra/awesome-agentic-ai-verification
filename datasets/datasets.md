# Datasets and Benchmarks

This file contains datasets and benchmarks that can be used to evaluate
agentic AI systems, reasoning, tool use, reliability, and security.

## 1. AgentBench

Link: https://github.com/THUDM/AgentBench

AgentBench is a benchmark for evaluating LLMs as agents across different
interactive environments. It includes tasks involving operating systems,
databases, knowledge graphs, games, web shopping, and web browsing.

Why relevant:
It can be used to study whether an agent can complete multi-step tasks
correctly and where failures occur during interaction with an environment.

## 2. SWE-bench

Link: https://www.swebench.com/

SWE-bench evaluates AI systems on real-world software engineering issues
collected from GitHub repositories.

Why relevant:
It is useful for testing long multi-step agent workflows because an agent
has to understand an issue, modify code, use tools, and produce a working
solution.

## 3. WebArena

Link: https://webarena.dev/

WebArena is a realistic web environment for evaluating autonomous agents.
It provides interactive websites and tasks that agents have to complete.

Why relevant:
It is useful for studying errors during web browsing, tool calls, state
changes, and multi-step decision making.

## 4. GAIA

Link: https://huggingface.co/gaia-benchmark

GAIA is a benchmark for general AI assistants. Its tasks require reasoning,
web browsing, tool use, and sometimes multiple steps to reach an answer.

Why relevant:
GAIA can be used to evaluate whether an agent can successfully combine
different capabilities instead of only generating a single text response.

## 5. AgentDojo

Link: https://github.com/ethz-spylab/agentdojo

AgentDojo is an environment for evaluating attacks and defenses against
LLM agents that interact with external tools and untrusted data.

Why relevant:
It is especially relevant to verification checkpoints because it can be
used to test whether an agent detects malicious inputs and prevents unsafe
tool actions.

## Summary

Number of datasets and benchmarks included: 5

These benchmarks cover different parts of agentic AI evaluation, including
general agent behavior, software engineering, web interaction, reasoning,
tool use, and security.
