# Awesome-LLM-Evaluation-Testing

## Top LLM Evaluation & Testing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Prompt Regression Testing, RAG Evaluation & Agent Observability*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Evaluation & Testing**. These tools measure output quality, detect hallucinations, catch prompt regressions, evaluate RAG pipelines, red-team for safety vulnerabilities, and monitor agent behavior in production.



**Examples** include Patronus AI, DeepEval, Ragas Cloud, TruLens, Confident AI, Braintrust, Galileo, Arthur AI, Fiddler AI, and Scale AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, CI/CD integration, and transparent evaluation pipelines — ideal for AI engineers, researchers, and teams building vendor-neutral evaluation infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Patronus AI](https://www.patronus.ai/)**  

  Automated LLM evaluation and testing platform with proprietary evaluator models for hallucination detection, safety, and RAG quality.



- **[Ragas Cloud](https://www.ragas.io/)**  

  Managed evaluation service for RAG pipelines built on the open-source Ragas framework, with hosted dashboards and continuous monitoring.



- **[Confident AI](https://www.confident-ai.com/)**  

  Cloud platform for DeepEval with evaluation result logging, LLM tracing, dataset management, and production monitoring .



- **[Braintrust](https://www.braintrust.dev/)**  

  Enterprise AI evaluation platform with code-defined eval pipelines, CI/CD integration that blocks sub-threshold changes, and no per-seat pricing .



- **[Galileo](https://galileo.ai/)**  

  AI evaluation and guardrails platform with named agentic metrics (Tool Selection Quality, Action Completion, Reasoning Coherence) powered by Luna-2 small models at sub-200ms latency .



- **[Arthur AI](https://www.arthur.ai/)**  

  Model monitoring and evaluation platform with fairness, bias, and performance tracking across the ML lifecycle.



- **[Fiddler AI](https://www.fiddler.ai/)**  

  AI observability and explainability platform for model monitoring, drift detection, and governance .



- **[Scale AI](https://scale.com/)**  

  Data labeling and model evaluation platform with human-in-the-loop feedback for LLM quality assurance.



## Open-Source GitHub Projects



- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  

  **The leading developer-first CLI and library for LLM evaluation and red teaming** — 8,700+ stars, MIT licensed. Declarative YAML configs, 100% local evals (prompts never leave your machine), model comparison across GPT/Claude/Gemini/Llama, CI/CD integration, and vulnerability scanning for prompt injection and jailbreaks .



- **[DeepEval](https://github.com/confident-ai/deepeval)**  

  **Pytest-style unit testing framework for LLM outputs** — G-Eval, hallucination, answer relevancy, faithfulness, contextual precision/recall, and RAGAS metrics running locally. Red-team 40+ safety vulnerabilities, benchmark on MMLU/HellaSwag/TruthfulQA, and create custom metrics .



- **[Ragas](https://github.com/explodinggradients/ragas)**  

  **Research-backed RAG evaluation toolkit** — objective metrics (faithfulness, answer relevance, context precision/recall), intelligent test data generation, and seamless LangChain/LlamaIndex integration .



- **[TruLens](https://github.com/truera/trulens)**  

  **OpenTelemetry-native evaluation and tracing framework** — RAG Triad metrics (groundedness, answer relevance, context relevance), agentic evaluators, and export to any OTLP backend (Jaeger, Grafana Tempo, Datadog). Completely free and self-hosted .



- **[Giskard](https://github.com/Giskard-AI/giskard)**  

  Open-source AI quality testing for bias detection, robustness testing, and explainability across ML models and LLM applications .



- **[OpenLIT](https://github.com/openlit/openlit)**  

  OpenTelemetry-native LLMOps platform with evaluation, observability, and guardrails for LLM applications .



- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Open-source LLM observability and evaluation platform with managed LLM-as-judge, annotation queues, and prompt experiments. MIT licensed and self-hostable .



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  

  Open-source LLM tracing and evaluation with OpenTelemetry trajectory-span analysis and Trajectory Mapping for agent loop detection .



- **[Laminar](https://github.com/lmnr-ai/lmnr)**  

  Open-source AI agent observability with trace workflows, agent run replay, and anomaly detection .



- **[Inspect](https://github.com/UKGovernmentBEIS/inspect_ai)**  

  UK AI Safety Institute framework for LLM evaluations supporting ReAct, Deep Agent, and custom multi-agent architectures with first-class tool use .



- **[Litmus](https://github.com/ivkond/litmus)**  

  Terminal UI for running LLM agent coding scenarios across Claude Code, Codex, Aider, and Cursor Agent, with LLM-judge scoring across 20 agent and 20 model criteria .



- **[JudgeArena](https://github.com/OpenEuroLLM/JudgeArena)**  

  Swappable-judge evaluation framework supporting MT-Bench, AlpacaEval, Arena-Hard, and m-Arena-Hard with vLLM self-hosted judges and provider-agnostic LangChain backends .



- **[EvalForge Lite](https://github.com/thejaredchapman/evalforge-lite)**  

  Lightweight side-by-side model comparison across OpenRouter, Bedrock, Vertex AI, and Microsoft Foundry with automatic grading, policy gating, and MCP server integration for Claude .



- **[Clean-Evals](https://github.com/datathere/clean-evals)**  

  Local evaluation workflow with blind human review, judge calibration, leaderboards, and per-case heatmaps. SQLite-based, no database server required .



- **[Vectory](https://pypi.org/project/vectoryai/)**  

  Proof-grounded evaluation for agents — scores traces on policy adherence, proof obligations, checker results, and pathologies like premature planning or retrieval thrashing. Designed for release gating .



### Additional Strong Open-Source Options



- **[Agentevals](https://github.com/langchain-ai/agentevals)** — LangChain's trajectory matching for agent evaluation (strict, unordered, superset, subset modes) with LLM-judge evaluator .

- **[Traceloop / OpenLLMetry](https://github.com/traceloop/openllmetry)** — OpenTelemetry-native LLM application monitoring and evaluation .

- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)** — Runtime guardrails framework for fact-checking and grounding .

- **[Vectara HHEM-2.1](https://huggingface.co/vectara/hallucination_evaluation_model)** — Open-weights cross-encoder hallucination detection model for RAG groundedness .

- **[G-Eval](https://github.com/nlpyang/geval)** — Research implementation of G-Eval metric now integrated into DeepEval and other frameworks .



**Frameworks for building custom systems**: Combine **Promptfoo** for CI/CD prompt regression testing, **DeepEval** for unit-style assertions, **Ragas** for RAG-specific metrics, and **TruLens** for OpenTelemetry-based tracing. For agent evaluation, layer in **Agentevals** for trajectory matching and **Vectory** for release gating. For self-hosted observability, pair with **Langfuse** or **Arize Phoenix**.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- LLM evaluation requires careful metric selection: RAG-focused metrics (faithfulness, context relevance) differ from agentic metrics (plan adherence, tool efficiency) and from safety metrics (toxicity, bias) .

- Self-hosted evaluation solutions require API keys for judge models (OpenAI, Anthropic, local Ollama) and proper prompt engineering for LLM-as-judge reliability.

- No single evaluation framework covers all use cases — production teams typically combine local unit tests (DeepEval/Promptfoo) with production tracing (TruLens/Langfuse) and periodic red-teaming.



---



**Made for AI engineers, ML researchers, evaluation scientists, and platform teams.**  

Let's make LLM evaluation more open, rigorous, and vendor-neutral.
