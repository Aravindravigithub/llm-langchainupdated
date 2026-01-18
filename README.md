# 🚀 LangChain V1 Implementation & Updates

This project covers the core concepts and advanced workflows introduced in LangChain Version 1 (V1), focusing on structured outputs, agentic workflows, and LLM orchestration.

---

## 🏗️ Core LangChain V1 Concepts
* **Virtual Environments:** Setting up isolated Python environments to manage dependencies specific to the V1 framework.
* **AI Agents:** Building intelligent agents that leverage LLMs to determine action sequences and execution order.
* **LLM Model Integration:** Connecting and configuring various Large Language Models (OpenAI, Anthropic, Hugging Face) within the V1 ecosystem.
* **Invoking & Batch Streaming:** Implementing techniques for single-query execution (invoking) and real-time data handling (streaming/batching).
* **Tool Implementation:** Extending LLM capabilities by integrating external tools like web search, calculators, and custom APIs.

## 📊 Structured Output Methods
To ensure machine-readable responses, the following data validation methods are implemented:
* **Pydantic:** Leveraging Python's data validation library to enforce strict schemas.
* **TypeDict:** Utilizing a lightweight approach for defining dictionary structures.
* **Data Classes:** Using native Python classes to organize and store returned information.

## ⚙️ Advanced Middleware & Workflows
* **Message Types:** Management of `System`, `Human`, and `AI` messages within conversation chains.
* **Summarization Middleware:** Logic for automatically condensing long-form conversations or extensive documents.
* **Human-In-The-Loop:** Designing interactive workflows where human intervention can review or approve agent actions before execution.
