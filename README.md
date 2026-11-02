<div align="center">
  <img src="https://raw.githubusercontent.com/Arsh624/Arsh624/main/photo.png" width="180" style="border-radius: 12px"/>

  <h3>Archit Shukla</h3>
  <p>AI infrastructure and ML engineer · San Francisco, CA</p>
</div>

<br/>

M.S. Computer Science, University of Colorado Boulder (GPA 3.9, May 2026).  
I work on LLM inference serving, GPU and distributed systems, and the backend and Kubernetes infrastructure AI products run on.

**Right now**
- Software Development Intern at **EcoServants**, building backend features on a PHP/MySQL platform for an environmental nonprofit.
- Contributing to open source ML infrastructure: **vLLM**, **DSPy**, **prime-rl**, and **LangChain Deep Agents**.
- Building **Kith**, a multi-agent platform behind a provider-agnostic inference gateway, and **Kube-Op-Lite**, a Kubernetes operator for GPU workloads.

---

## Open Source

Contributing to the ML infrastructure I use and build on:

- **[vLLM](https://github.com/vllm-project/vllm)** - LLM serving engine. [Run-batch request validation fix](https://github.com/vllm-project/vllm/pull/65029)
- **[prime-rl](https://github.com/PrimeIntellect-ai/prime-rl)** - Agentic RL training at scale. [Trainer loss logging fix](https://github.com/PrimeIntellect-ai/prime-rl/pull/4352)
- **[DSPy](https://github.com/stanfordnlp/dspy)** - Framework for programming language models. [XMLAdapter list handling fix](https://github.com/stanfordnlp/dspy/pull/10761)
- **[LangChain Deep Agents](https://github.com/langchain-ai/deepagents)** - Agent harness. [CRLF line-ending bug report](https://github.com/langchain-ai/deepagents/issues/7488)

See all of my [pull requests](https://github.com/pulls?q=is%3Apr+author%3AArsh624).

---

## Work

**Software Development Intern, EcoServants** `Aug 2026 – Present`  
Backend features on a PHP/MySQL platform, built with coding agents and gated by mutation testing (13 of 13 injected faults caught across 310+ checks). Proposal autosave with versioned revisions and HMAC-signed unsubscribe tokens.

**Graduate Researcher, Peleg Lab (BioFrontiers Institute)** `Aug 2025 – Jan 2026`  
Distributed AI inference pipelines in Python and multithreaded C++ on GCP GPU clusters. 35% higher evaluation throughput, vLLM on Kubernetes with 300+ sweeps and zero failures, 40% faster fault diagnosis with GDB and Valgrind.

**Graduate Teaching Assistant, Lab Systems, CU Boulder** `Jan 2026 – May 2026`  
Led 3 lab sections (55+ students). Workflow analysis in R to find bottlenecks in lab operations.

**Software Engineering Intern, CodeClause** `Jun 2024 – Jul 2024`  
REST microservices and SQL paths: p95 latency from 310ms to 180ms. Jenkins and GitHub Actions deploys cut release failures from 1 in 6 builds to 1 in 24.

**Software Engineer Intern, Adflix Media** `Apr 2023 – Sep 2023`  
Kafka and Spark ETL landing 5M+ records a day, with Prometheus and Grafana alerting on throughput and consumer lag.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

**[Kith – Multi-Agent AI Platform](https://github.com/Arsh624/Kith-Multi-Agent-Relationship-Intelligence-Platform)**

Maps contacts from emails, docs, and meeting notes into a knowledge graph of 1,000+ entities. FastAPI inference gateway over hosted APIs and local vLLM completed 99.2% of agent runs in simulated provider outages.

![](https://img.shields.io/badge/MULTI--AGENT%20%7C%20RAG%20%7C%20KNOWLEDGE%20GRAPHS-3C3489?style=flat-square&labelColor=3C3489&color=3C3489&logoColor=CECBF6)

`LangGraph` `FastAPI` `vLLM` `Neo4j` `Qdrant` `Redis`

</td>
<td width="50%" valign="top">

**[Kube-Op-Lite](https://github.com/Arsh624/kube-op-lite)**

Kubernetes operator in Go that restores failed GPU pods to desired state in under 30 seconds, with admission webhooks, a Helm chart, and benchmark regression analysis.

![](https://img.shields.io/badge/KUBERNETES%20%7C%20GPU%20%7C%20OPERATORS-0C447C?style=flat-square&color=0C447C)

`Go` `Kubebuilder` `Helm` `Prometheus`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[RepoGraph V2](https://github.com/Arsh624/Repograph-V2/blob/main/Repograph%20Paper%20.pdf)**

LLM repair for order-dependent flaky tests, guided by a function-state graph and verified across random test orders. With iPFlakies, repair coverage rose from 33% to 56.6% of 537 tests. Written up as a paper.

![](https://img.shields.io/badge/DISTRIBUTED%20%7C%20STATIC%20ANALYSIS-085041?style=flat-square&color=085041)

`Python` `C++` `REST APIs` `Linux`

</td>
<td width="50%" valign="top">

**[Regime-Switching RL for Portfolio Optimization](https://github.com/Arsh624/Regime-switching-RL-model-for-Portfolio-Optimization)**

Three specialist PPO agents routed by an HMM market-regime detector. Sharpe 0.82 to 1.41 and max drawdown 29.6% to 16.2% on 2018–2022 test data.

![](https://img.shields.io/badge/REINFORCEMENT%20LEARNING%20%7C%20FINANCE-27500A?style=flat-square&color=27500A)

`PyTorch` `Stable-Baselines3` `Gymnasium`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Anomaly Detection Service](https://github.com/Arsh624/TS-anomaly-detection-pipeline)**

Streaming ML pipeline processing live event data and exposing anomaly predictions through backend APIs in real time.

![](https://img.shields.io/badge/STREAMING%20ML%20%7C%20REAL--TIME-712B13?style=flat-square&color=712B13)

`Python` `ML pipeline` `REST API`

</td>
<td width="50%" valign="top">

**[TripSync – AI Multi-Agent Travel Planning](https://github.com/Arsh624/TripSync)**

Multi-agent trip planner that aggregates group preferences and generates itineraries with LLM orchestration.

![](https://img.shields.io/badge/MULTI--AGENT%20%7C%20LLM%20WORKFLOWS-633806?style=flat-square&color=633806)

`Next.js` `TypeScript` `Supabase` `Gemini`

</td>
</tr>
</table>

## Stack

**Languages** - Python, C++, Go, TypeScript, JavaScript, Java, C, SQL, Bash

**LLM Inference & ML** - vLLM, PyTorch, Speculative Decoding, Continuous Batching, KV Cache, LangGraph, LangChain, DSPy, RAG Pipelines, LLM-as-Judge Evals, Langfuse, PPO / GRPO

**Backend & Distributed Systems** - FastAPI, Node.js, REST APIs, Microservices, Apache Kafka, Apache Spark, Multithreaded C++, Async & Event-Driven Architectures

**Databases & Data** - PostgreSQL, MySQL, Redis, Neo4j, Qdrant, MongoDB, DynamoDB, ETL Pipelines, Query Optimization

**Cloud & Infrastructure** - Kubernetes, Kubebuilder, Helm, Docker, GCP, AWS, Terraform, CI/CD, GitHub Actions, Linux

**Observability & Debugging** - Prometheus, Grafana, OpenTelemetry, Nsight Systems, GDB, Valgrind, Pytest, Structured Logging

---

## Links

[Portfolio](https://architshukla-portfolio.vercel.app) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/archit-shukla06) &nbsp;·&nbsp; [Email](mailto:architshukla546@gmail.com)

---

![Stats](https://github-readme-stats.vercel.app/api?username=Arsh624&theme=ambient_gradient&hide_border=true&include_all_commits=true&count_private=false)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Arsh624&theme=ambient_gradient&hide_border=true&include_all_commits=true&count_private=false&layout=compact)

![Contribution activity](https://github-readme-activity-graph.vercel.app/graph?username=Arsh624&theme=github-compact&hide_border=true&area=true)
