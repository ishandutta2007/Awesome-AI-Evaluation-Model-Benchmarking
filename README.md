# Awesome-AI-Evaluation-Model-Benchmarking

# Top AI Evaluation & Model Benchmarking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Foundation Model Benchmarking, Autonomous Agent Evaluation Harnesses, RAG & LLM-as-a-Judge Metrics, CI/CD Regression Testing & Red-Teaming*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Evaluation & Model Benchmarking**. These tools benchmark open-weight and frontier LLMs across reasoning, coding, and tool-use tasks, run unit-test-style assertions on RAG and multi-step agent trajectories, and gate production deployments against quality regressions.

**Examples** include DeepEval, Ragas, Braintrust, LangSmith, Humanloop, Galileo, Arize Phoenix, HoneyHive, Patronus AI, Confident AI, and autonomous-ai/openharness (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for foundation model evaluation harnesses (`lm-evaluation-harness`, `LightEval`, `OpenCompass`, `EvalScope`), autonomous agent harnesses (`openharness`, `Inspect AI`, `SWE-bench`), Pytest-style LLM unit testing (`DeepEval`, `Promptfoo`, `Ragas`), and self-hosted evaluation & tracing suites (`Arize Phoenix`, `Opik`, `Langfuse`) — ideal for ML researchers, AI platform engineers, and QA teams building reproducible benchmarking pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Confident AI (DeepEval Cloud)](https://confident-ai.com)**  
  Managed cloud evaluation platform built around DeepEval offering collaborative dataset curation, hosted LLM-as-a-judge metrics, red-teaming, and automated CI/CD regression reports.

- **[Braintrust](https://braintrust.dev)**  
  Enterprise AI evaluation, prompt playground, and logging platform designed to benchmark model and prompt upgrades side by side and prevent regressions across releases.

- **[LangSmith (LangChain)](https://langchain.com)**  
  All-in-one cloud evaluation, dataset management, and observability platform enabling teams to run offline model benchmarks and online evaluators on agent trajectories.

- **[Galileo](https://rungalileo.io)**  
  Enterprise AI evaluation and observability suite featuring proprietary hallucination guardrails, agentic trajectory metrics, RAG attribution scoring, and automated error clustering.

- **[Humanloop](https://humanloop.com)**  
  Enterprise LLM evaluation and prompt management workspace combining human-in-the-loop annotation workflows, custom model graders, and versioned benchmark datasets.

- **[Arize AX / Arize Phoenix Cloud](https://arize.com)**  
  Enterprise AI observability and evaluation platform delivering OpenTelemetry span tracing, drift detection, and automated LLM evaluation pipelines.

- **[HoneyHive](https://honeyhive.ai)**  
  AI observability and evaluation platform built for compounding agent reliability through production trace curation, human feedback loops, and CI/CD regression gates.

- **[Patronus AI](https://patronus.ai)**  
  Automated AI evaluation and safety platform offering adversarial test generation, specialized hallucination detection models (Lynx), and enterprise compliance benchmarking.

- **[Vellum](https://vellum.ai)**  
  Cloud AI product development platform featuring quantitative multi-model evaluation matrices, prompt sandboxes, and versioned workflow deployments.

- **[Vals AI / Artificial Analysis](https://artificialanalysis.ai)**  
  Independent cloud benchmarking and model evaluation platforms tracking speed, latency, token pricing, and domain-specific accuracy across frontier and open models.


## Open-Source GitHub Projects

- **[autonomous-ai/openharness](https://github.com)**  
  Open-source autonomous AI evaluation and execution harness engineered for benchmarking multi-step agent capabilities, tool-use reliability, and reproducible task trajectories.

- **[LM Evaluation Harness (`EleutherAI/lm-evaluation-harness`)](https://github.com)**  
  Industry-standard open-source (`MIT`) model benchmarking framework from EleutherAI powering the Open LLM Leaderboard with 60+ academic tasks (`MMLU`, `GSM8K`, `ARC`, `GPQA`, `HellaSwag`).

- **[DeepEval (`confident-ai/deepeval`)](https://github.com)**  
  Leading open-source (`Apache-2.0`) Pytest-style LLM evaluation framework offering 40+ research-backed metrics for agent tool correctness, task completion, faithfulness, hallucination, and red-teaming.

- **[Ragas (`explodinggradients/ragas`)](https://github.com)**  
  Widely adopted open-source (`Apache-2.0`) evaluation and synthetic test-data generation toolkit specialized in measuring faithfulness, context precision, context recall, and answer relevancy.

- **[LightEval (`huggingface/lighteval`)](https://github.com)**  
  All-in-one open-source (`MIT`) model benchmarking suite from Hugging Face supporting distributed `vLLM`, `Transformers`, and `Nanotron` backends across hundreds of standardized benchmarks.

- **[OpenCompass (`open-compass/opencompass`)](https://github.com)**  
  Comprehensive open-source (`Apache-2.0`) LLM evaluation platform from Shanghai AI Lab supporting 100+ datasets across language, reasoning, math, coding, multimodal, and long-context capabilities.

- **[EvalScope (`modelscope/evalscope`)](https://github.com)**  
  Streamlined open-source (`Apache-2.0`) model evaluation and performance stress-testing framework from ModelScope supporting standard benchmarks, Arena-style battles, and inference throughput profiling.

- **[Inspect AI (`UKGovernmentBEIS/inspect_ai`)](https://github.com)**  
  Open-source (`MIT`) evaluation framework developed by the UK AI Security Institute (AISI) for benchmarking complex reasoning, sandboxed agent tool use, and safety capabilities.

- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com)**  
  Fast open-source (`MIT`) CLI and library for declarative model benchmarking, side-by-side prompt/model comparisons, CI/CD regression gating, and automated red-teaming.

- **[Arize Phoenix (`Arize-ai/phoenix`)](https://github.com)**  
  Open-source (`ELv2`) OpenTelemetry-native AI observability and evaluation suite featuring pre-built hallucination/relevance evaluators, trace waterfalls, and experiment tracking.

- **[Opik (`comet-ml/opik`)](https://github.com)**  
  Open-source (`Apache-2.0`) end-to-end LLM evaluation and tracing platform from Comet built for logging agent trajectories, managing evaluation datasets, and running LLM-as-a-judge metrics.

- **[Langfuse (`langfuse/langfuse`)](https://github.com)**  
  Self-hostable open-source LLM engineering platform offering dataset experiment runs, LLM-as-a-judge evaluators, user feedback scoring, and trace-level evaluation analytics.

- **[TruLens (`truera/trulens`)](https://github.com)**  
  Open-source (`MIT`) library for systematically evaluating and tracking LLM and RAG applications using programmable Feedback Functions (Groundedness, Context Relevance, Answer Relevance).

- **[EvalPlus (`evalplus/evalplus`)](https://github.com)**  
  Open-source (`Apache-2.0`) rigorous code-generation benchmarking framework extending HumanEval and MBPP with 80x more edge-case test inputs to expose fragile code synthesis.

- **[SWE-bench (`SWE-bench/SWE-bench`)](https://github.com)**  
  Foundational open-source (`MIT`) software-engineering benchmark evaluating autonomous coding agents on their ability to resolve real-world GitHub issues inside Dockerized repositories.

- **[LiveCodeBench (`LiveCodeBench/LiveCodeBench`)](https://github.com)**  
  Contamination-free open-source (`MIT`) coding benchmark continuously collecting new competitive programming problems across code generation, self-repair, and execution prediction.

- **[Giskard (`Giskard-AI/giskard-oss`)](https://github.com)**  
  Open-source (`Apache-2.0`) automated QA and testing framework for AI agents and RAG pipelines that scans for hallucinations, bias, prompt injection, and robustness regressions.

- **[HELM (`stanford-crfm/helm`)](https://github.com)**  
  Holistic Evaluation of Language Models (`Apache-2.0`) from Stanford CRFM benchmarking models across accuracy, calibration, robustness, fairness, bias, toxicity, and efficiency.

### Additional Strong Open-Source Options

- **[OpenAI Evals (`openai/evals`)](https://github.com)** and **[AutoEvals (`braintrustdata/autoevals`)](https://github.com)** for composable open-source scoring primitives and custom model-graded capability evals.
- **[VLMEvalKit (`open-compass/VLMEvalKit`)](https://github.com)** and **[lmms-eval (`EvolvingLMMs-Lab/lmms-eval`)](https://github.com)** for standardized open-source benchmarking of Vision-Language and Multimodal models (`MMMU`, `MathVista`, `OCRBench`).
- **[FastChat / Chatbot Arena (`lm-sys/FastChat`)](https://github.com)** and **[Prometheus-Eval (`prometheus-eval/prometheus-eval`)](https://github.com)** for Elo-based pairwise model arenas and open-weight judge models that replace proprietary GPT-4 judges.
