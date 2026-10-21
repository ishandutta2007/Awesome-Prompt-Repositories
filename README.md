# ⚡ Awesome-Prompt-Repositories

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Prompt Repositories Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a> <a href="https://github.com/ishandutta2007/Awesome-Prompt-Repositories/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Prompt-Repositories?style=flat-square&logo=github&color=gold" alt="Stars"/></a> <a href="https://github.com/ishandutta2007/Awesome-Prompt-Repositories/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Prompt-Repositories?style=flat-square&logo=github&color=blue" alt="Forks"/></a> <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"/></a> <a href="https://github.com/ishandutta2007/Awesome-Prompt-Repositories/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a> <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🎯 Top Prompt Repositories, Versioning & LLMOps Ecosystem

> **A curated collection of leading SaaS platforms and open-source GitHub projects for prompt registries, prompt version control, collaborative prompt engineering, and LLMOps integration.**  
> *Focused on Prompt Lineage, Git-Native Registries, Local-First Storage, and Evaluation-Driven CI/CD Pipelines.*  
> **Last updated: March 2026**

This repository tracks premier **SaaS platforms** and **open-source repositories** designed for **Prompt Repositories & Management**. As generative AI applications mature into production systems, raw text files and unstructured chat logs no longer suffice. These platforms treat prompts as first-class software artifacts — offering cryptographic versioning, environmental aliases (e.g. `staging`, `production`), zero-latency client SDK caching, dynamic template rendering, regression eval gates, and end-to-end trace correlation.

---

## 📑 Table of Contents

- [🌐 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS / Hosted Platforms](#️-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🧩 Architecture & Stack Composition Guide](#-architecture--stack-composition-guide)
- [🤝 How to Contribute](#-how-to-contribute)
- [⭐ Star History](#-star-history)
- [💖 Support & Sponsoring](#-support--sponsoring)
- [⚖️ Disclaimer](#️-disclaimer)
- [🏷️ Tags & Keywords](#️-tags--keywords)

---

## 🌐 Sector Overview & Market Dynamics

* **Estimated Market Size & Velocity:** The global LLMOps and prompt engineering tooling sector was estimated at **$1.8 billion in 2024** and is projected to surpass **$7.2 billion by 2029**, expanding at a compound annual growth rate (**CAGR**) of **~32.5%** as enterprises operationalize hundreds of generative AI models, agents, and complex RAG pipelines.
* **Market Structure & Fragmentation:** The industry exhibits **moderate fragmentation** with distinct segmentation. High-end developer LLMOps suites (e.g., Braintrust, LangSmith, Vellum) and observability frameworks are consolidating enterprise telemetry workflows, while consumer and creator prompt marketplaces (e.g., FlowGPT, PromptBase) dominate commercial distribution. Concurrently, a vibrant open-source ecosystem (e.g., Langfuse, promptfoo, Opik, Phoenix) provides data-sovereign, local-first alternatives that resist single-vendor lock-in.

---

## ☁️ SaaS / Hosted Platforms

Below is a comparison of top hosted prompt management platforms, sorted descending by **company scale (valuation / funding / revenue)**.

| 🏢 Platform | 💰 Company Scale / Valuation | 🏷️ Starting Pricing | 🎁 Free Tier / Trial Limits | 🚀 Key Capabilities & Focus |
| :--- | :--- | :--- | :--- | :--- |
| **[Braintrust](https://www.braintrust.dev/)** | **~$500M Valuation**<br>*(Raised $80M Series B in Feb 2026 led by ICONIQ; $120M+ total raised)* | **$249 / month**<br>*(Pro Plan: includes 5 GB processed data/mo, 50k scores, $100 model credits)* | **Free Forever Starter Plan:**<br>1 GB data/month, 10,000 scores/month, $10 monthly model credits, 14-day data retention, unlimited seats & datasets | Enterprise AI evaluation, regression testing, automated prompt CI/CD eval gates, dynamic prompt playground, and real-time observability. |
| **[LangSmith Hub](https://smith.langchain.com/hub)** | **~$250M Valuation**<br>*(Raised $25M Series A led by Sequoia Capital; $35M total raised)* | **$39 / seat / month**<br>*(Plus Plan: expanded team workspaces, 50k monthly traces included)* | **Free Forever Developer Plan:**<br>1 seat, 5,000 base traces/month, 14-day data retention, unlimited public & private Prompt Hub commits | Git-like SHA prompt commits, deep LangChain & LangGraph agent lineage, tracing integration, and interactive sandbox playground. |
| **[Vellum](https://www.vellum.ai/)** | **~$90M Valuation**<br>*(Raised $20M Series A in July 2025 led by Leaders Fund; $25.5M total raised)* | **$300 / month**<br>*(Pro Plan: team collaboration seats; model tokens billed at direct provider cost without markup)* | **Free Forever Base Plan:**<br>Up to 5 users, 50 prompt executions/day, 25 workflow executions/day, sandbox testing environment | Multi-model prompt playground, side-by-side prompt comparisons, complex agent workflow builder, and regression testing. |
| **[FlowGPT](https://flowgpt.com/)** | **~$45M Valuation**<br>*(Raised $10M Pre-Series A led by Goodwater Capital & DCM)* | **$14.99 / month**<br>*(FlowGPT Plus: advanced AI models, 2× conversation memory, priority response queue)* | **Free Forever Plan:**<br>Unlimited public prompt library browsing and testing, basic chat models, daily generation credit cap (~100 daily credits) | Consumer & creator prompt marketplace, interactive prompt discovery, community bot hosting, and social prompt rating. |
| **[AIPRM](https://www.aiprm.com/)** | **~$35M Valuation**<br>*(~$10M ARR, 2M+ active extension users, bootstrapped profitable)* | **$20 / month**<br>*(AIPRM Plus: $9/mo billed annually; unlocks private prompt lists & custom brand voice)* | **Free Forever Plan:**<br>Access to 4,000+ public community prompt templates, capped at 2 private prompt templates, 1 custom list | 1-click ChatGPT prompt templates, SEO & marketing workflow automation, browser extension prompt launcher, and team snippets. |
| **[PromptBase](https://promptbase.com/)** | **~$10M Valuation**<br>*(~$2M ARR, bootstrapped / angel-backed)* | **$14 / month**<br>*(PromptBase Select subscription; or pay-per-prompt starting at $1.99–$4.99 / prompt)* | **Free Forever Plan:**<br>$0 upfront fee to browse marketplace and list prompts for sale (20% platform commission on marketplace sales) | Commercial prompt marketplace for Midjourney, ChatGPT, DALL·E 3, FLUX, and Stable Diffusion with creator payout rails. |
| **[PromptLayer](https://promptlayer.com/)** | **~$10M Valuation**<br>*(YC W24, ~$1.5M raised, seed-stage)* | **$49 / month**<br>*(Pro Plan: $40/mo billed annually; advanced search, CSV exports, unlimited prompts)* | **Free Forever Plan:**<br>1 user seat, up to 10 stored prompts, 2,500 requests/month, 250 evaluation cell executions/month | Request-level prompt telemetry middleware, prompt CMS, visual regression comparison, and OpenAI/Anthropic SDK wrapping. |
| **[PromptHero](https://prompthero.com/)** | **~$4M Valuation**<br>*(~$600K ARR, bootstrapped / seed)* | **$19 / month**<br>*(Starter Plan: 300 AI generation credits/mo, PRO badge, portfolio showcase; PRO at $29/mo)* | **Free Forever Plan:**<br>Unlimited search and copy of image generation prompts, community portfolio, 25 free initial image credits | AI image & text-to-image prompt repository with specialized discovery for Midjourney, SDXL, and Stable Diffusion models. |

---

## 💻 Open-Source GitHub Projects

Curated open-source prompt repositories, registries, and LLMOps frameworks. Sorted descending by **GitHub_Stars**:

### 1. 🥇 [Langfuse](https://github.com/langfuse/langfuse) [![GitHub_Stars](https://img.shields.io/github/stars/langfuse/langfuse?style=social&color=white)](https://github.com/langfuse/langfuse/stargazers)
* **License:** MIT | **Stars:** ~36.1k+ ⭐
* **Core Capabilities:** The leading open-source AI engineering and LLMOps platform with natively integrated prompt management. Prompts are centrally stored, labeled (e.g. `production`, `staging`), and versioned with client-side SDK caching to eliminate network latency on runtime fetches.
* **Why Teams Choose It:** Seamlessly connects prompts to production traces, LLM-as-a-judge evals, and playground experiments in a 100% self-hostable container stack without vendor lock-in.

### 2. 🥈 [promptfoo](https://github.com/promptfoo/promptfoo) [![GitHub_Stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social&color=white)](https://github.com/promptfoo/promptfoo/stargazers)
* **License:** MIT | **Stars:** ~26.2k+ ⭐
* **Core Capabilities:** CLI and testing framework for automated prompt evaluation, regression testing, and security red-teaming. Define prompts as templates, run test matrices across 50+ LLM providers, and assert deterministic or semantic outputs.
* **Why Teams Choose It:** Fast, lightweight, runs locally in CI/CD pipelines (GitHub Actions, GitLab CI), catching prompt regressions and jailbreaks before code merges.

### 3. 🥉 [Opik](https://github.com/comet-ml/opik) [![GitHub_Stars](https://img.shields.io/github/stars/comet-ml/opik?style=social&color=white)](https://github.com/comet-ml/opik/stargazers)
* **License:** Apache-2.0 | **Stars:** ~22.8k+ ⭐
* **Core Capabilities:** Open-source platform by Comet ML for evaluating, testing, and monitoring LLM applications and prompt repositories. Features prompt library versioning, automated evaluation metrics, and end-to-end distributed tracing.
* **Why Teams Choose It:** Enterprise-grade scalability for high-throughput LLM pipelines, combined with a modern UI and deep Python/TypeScript SDKs.

### 4. 🚀 [Phoenix](https://github.com/Arize-ai/phoenix) [![GitHub_Stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social&color=white)](https://github.com/Arize-ai/phoenix/stargazers)
* **License:** Apache-2.0 | **Stars:** ~11.9k+ ⭐
* **Core Capabilities:** AI observability and evaluation platform created by Arize AI. Provides prompt playground experimentation, OpenTelemetry-based distributed tracing, RAG analysis, and dataset management.
* **Why Teams Choose It:** Notebook-friendly, local-first deployment via single pip install or Docker container, ideal for data science teams iterating on complex prompt topologies.

### 5. 🔍 [OpenLLMetry](https://github.com/traceloop/openllmetry) [![GitHub_Stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=social&color=white)](https://github.com/traceloop/openllmetry/stargazers)
* **License:** Apache-2.0 | **Stars:** ~7.5k+ ⭐
* **Core Capabilities:** OpenTelemetry-native instrumentation and prompt management extension by Traceloop. Standardizes telemetry collection across LangChain, LlamaIndex, OpenAI, Anthropic, and Bedrock.
* **Why Teams Choose It:** Vendor-neutral prompt telemetry that exports directly to Datadog, Dynatrace, Honeycomb, or any OTel collector.

### 6. 🛡️ [Helicone](https://github.com/Helicone/helicone) [![GitHub_Stars](https://img.shields.io/github/stars/Helicone/helicone?style=social&color=white)](https://github.com/Helicone/helicone/stargazers)
* **License:** Apache-2.0 | **Stars:** ~6.2k+ ⭐
* **Core Capabilities:** Developer-first LLM gateway and observability platform with built-in prompt tracking, version comparison, smart caching, and rate limiting.
* **Why Teams Choose It:** Integrates via a single base URL change in your OpenAI or Anthropic SDK, instantly capturing prompt latency, cost, and template parameters.

### 7. 🤖 [Coze-Loop](https://github.com/coze-dev/coze-loop) [![GitHub_Stars](https://img.shields.io/github/stars/coze-dev/coze-loop?style=social&color=white)](https://github.com/coze-dev/coze-loop/stargazers)
* **License:** Apache-2.0 | **Stars:** ~5.8k+ ⭐
* **Core Capabilities:** Full-lifecycle AI agent optimization and prompt management platform providing dynamic prompt templates, interactive debugging, and multi-turn conversation evaluation.
* **Why Teams Choose It:** Tailored for complex multi-agent systems where prompts dynamically incorporate tool definitions and state variables.

### 8. 📚 [OpenPrompt](https://github.com/thunlp/OpenPrompt) [![GitHub_Stars](https://img.shields.io/github/stars/thunlp/OpenPrompt?style=social&color=white)](https://github.com/thunlp/OpenPrompt/stargazers)
* **License:** Apache-2.0 | **Stars:** ~4.9k+ ⭐
* **Core Capabilities:** Research-standard open-source framework for prompt-learning and prompt tuning over pre-trained language models developed by Tsinghua University (THUNLP).
* **Why Teams Choose It:** Highly modular design supporting soft prompts, hard prompt templates, verbalizers, and prompt tuning algorithms.

### 9. 🔬 [Agenta](https://github.com/agenta-ai/agenta) [![GitHub_Stars](https://img.shields.io/github/stars/agenta-ai/agenta?style=social&color=white)](https://github.com/agenta-ai/agenta/stargazers)
* **License:** MIT | **Stars:** ~4.8k+ ⭐
* **Core Capabilities:** Open-source developer-centric prompt engineering and LLMOps platform. Provides a collaborative prompt playground, version control with branching and deployment environments, and custom evaluator suites.
* **Why Teams Choose It:** Empowers non-technical domain experts to iterate and test prompts in the UI while developers consume versioned prompts via clean REST/Python SDKs.

### 10. 🌐 [Latitude](https://github.com/latitude-dev/latitude-llm) [![GitHub_Stars](https://img.shields.io/github/stars/latitude-dev/latitude-llm?style=social&color=white)](https://github.com/latitude-dev/latitude-llm/stargazers)
* **License:** LGPL-3.0 | **Stars:** ~4.7k+ ⭐
* **Core Capabilities:** AI engineering platform with an eval-driven reliability loop. Captures prompts, inputs/outputs, and costs from live traffic, grouping failure clusters to guide prompt optimization (GEPA).
* **Why Teams Choose It:** Closes the feedback loop between production prompt failures and iterative prompt engineering improvements.

### 11. ⚙️ [Promptify](https://github.com/promptslab/Promptify) [![GitHub_Stars](https://img.shields.io/github/stars/promptslab/Promptify?style=social&color=white)](https://github.com/promptslab/Promptify/stargazers)
* **License:** Apache-2.0 | **Stars:** ~4.6k+ ⭐
* **Core Capabilities:** Prompt engineering and prompt versioning library to turn unstructured model generation into strictly typed structured JSON outputs, NER entities, and classifications.
* **Why Teams Choose It:** Simple Pythonic API that turns raw LLM completions into reliable downstream data structures.

### 12. ⚡ [Pezzo](https://github.com/pezzolabs/pezzo) [![GitHub_Stars](https://img.shields.io/github/stars/pezzolabs/pezzo?style=social&color=white)](https://github.com/pezzolabs/pezzo/stargazers)
* **License:** Apache-2.0 | **Stars:** ~3.3k+ ⭐
* **Core Capabilities:** Developer-first prompt management and LLMOps platform designed to streamline prompt design, instant publishing, and observability without redeploying backend code.
* **Why Teams Choose It:** First-class SDK support for Node.js, TypeScript, and Python with immediate prompt synchronization across services.

### 13. 📐 [Prompt Engine](https://github.com/microsoft/prompt-engine) [![GitHub_Stars](https://img.shields.io/github/stars/microsoft/prompt-engine?style=social&color=white)](https://github.com/microsoft/prompt-engine/stargazers)
* **License:** MIT | **Stars:** ~2.8k+ ⭐
* **Core Capabilities:** Microsoft utility library for creating, managing, and rendering few-shot prompts and conversational dialogues for LLMs in JavaScript, TypeScript, and Python.
* **Why Teams Choose It:** Lightweight, zero-dependency utility that guarantees clean few-shot formatting and token budget adherence.

### 14. 🔌 [PromptLayer Library](https://github.com/MagnivOrg/prompt-layer-library) [![GitHub_Stars](https://img.shields.io/github/stars/MagnivOrg/prompt-layer-library?style=social&color=white)](https://github.com/MagnivOrg/prompt-layer-library/stargazers)
* **License:** MIT | **Stars:** ~780+ ⭐
* **Core Capabilities:** Official open-source client libraries for PromptLayer, wrapping OpenAI and Anthropic SDK calls to track prompt versions, template inputs, and request IDs.
* **Why Teams Choose It:** Enables immediate request-level logging and prompt version governance with single-line SDK interception.

### 15. 🗄️ [RESTai](https://github.com/apocas/restai) [![GitHub_Stars](https://img.shields.io/github/stars/apocas/restai?style=social&color=white)](https://github.com/apocas/restai/stargazers)
* **License:** Apache-2.0 | **Stars:** ~515+ ⭐
* **Core Capabilities:** Open-source AIaaS (AI as a Service) platform supporting local LLMs (Ollama, vLLM) and commercial APIs, featuring built-in prompt versioning, vector search, and block-based flow design.
* **Why Teams Choose It:** Complete self-hosted AI middleware with integrated prompt storage and multi-provider model routing.

### 16. 💾 [Cuebit](https://github.com/iRahulPandey/Cuebit) [![GitHub_Stars](https://img.shields.io/github/stars/iRahulPandey/Cuebit?style=social&color=white)](https://github.com/iRahulPandey/Cuebit/stargazers)
* **License:** Apache-2.0 | **Stars:** ~1 ⭐
* **Core Capabilities:** Open-source, local-first prompt registry built specifically for GenAI developers. Supports prompt version lineage, environment aliases (`summarizer-prod`), template variable validation, Streamlit UI, and FastAPI REST endpoints.
* **Why Teams Choose It:** Complete local sovereignty—run `cuebit serve` on your developer machine with zero cloud dependencies or external credentials.

---

## 🧩 Architecture & Stack Composition Guide

To construct a resilient, production-ready prompt engineering and LLMOps architecture, combine specialized tools across four foundational layers:

```
┌────────────────────────────────────────────────────────┐
│             Prompt Authoring & Marketplaces            │
│       (FlowGPT, AIPRM, PromptBase, LangSmith Hub)      │
└───────────────────────────┬────────────────────────────┘
                            │
┌───────────────────────────▼────────────────────────────┐
│      Prompt Registry, Versioning & Linage CMS          │
│    (Langfuse, Agenta, Pezzo, Cuebit, PromptLayer)      │
└───────────────────────────┬────────────────────────────┘
                            │
┌───────────────────────────▼────────────────────────────┐
│          Continuous Evaluation & CI/CD Gates           │
│           (promptfoo, Braintrust, Opik, Phoenix)       │
└───────────────────────────┬────────────────────────────┘
                            │
┌───────────────────────────▼────────────────────────────┐
│        Gateway, Telemetry & Production Observability   │
│           (Helicone, OpenLLMetry, Latitude)            │
└────────────────────────────────────────────────────────┘
```

* **Version Management:** Use **Langfuse** or **Agenta** for centralized team versioning with environment aliases (`staging`, `prod`), preventing breaking prompt changes from affecting live users.
* **Regression Testing:** Incorporate **promptfoo** into your GitHub Actions workflow to run assertion checks and red-teaming datasets before PR approvals.
* **Local-First & Data Sovereign Workflows:** Use **Cuebit** or **Phoenix** for offline, privacy-first environments that must comply with strict governance standards.

---

## 🤝 How to Contribute

Contributions are warmly encouraged! Help keep this repository comprehensive and accurate:

1. 🍴 **Fork the repository** to your GitHub account.
2. 🌿 **Create a feature branch:** `git checkout -b feature/add-new-prompt-tool`
3. 📝 **Add or update an entry:** Ensure factual descriptions, official website links, GitHub repository links, license details, and exact pricing/free tier parameters.
4. 📬 **Submit a Pull Request** with a concise explanation of the tool and why it adds value to the prompt engineering community.

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Prompt-Repositories&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Prompt-Repositories&type=date&legend=top-left)

---

## 💖 Support & Sponsoring

Thank you for visiting and supporting the **Awesome Prompt Repositories** project! If you found this curated list helpful for your LLMOps, AI engineering, or prompt management stack, please consider:

* ⭐ **Starring** this repository to help others discover it
* 🍴 **Forking** the repo and contributing your own tools and insights
* 📢 **Sharing** with your colleagues, AI engineering teams, and community
* ☕ **Buying a coffee / sponsoring** the maintainer via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007)

Your support keeps this ecosystem up-to-date, actively curated, and comprehensive!

---

## ⚖️ Disclaimer

* This repository is an independently curated community resource for educational and informational purposes. Mention of platforms, products, or services does not constitute commercial endorsement.
* Pricing tiers, free quotas, and feature sets change frequently. Always consult official vendor documentation for up-to-date terms.

---

## 🏷️ Tags & Keywords

`prompt-repositories` • `prompt-registry` • `prompt-management` • `prompt-versioning` • `llmops` • `prompt-engineering` • `llm-evaluation` • `prompt-templates` • `langchain` • `langsmith` • `langfuse` • `promptfoo` • `opik` • `braintrust` • `generative-ai` • `ai-engineering` • `local-first` • `git-ops`
