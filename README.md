# Awesome-Prompt-Repositories

# Top Prompt Repositories Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Prompt Versioning, Local-First Registries & LLMOps Integration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Prompt Repositories**. These tools help teams store, version, and share prompts — moving them out of scattered text files and chat histories into managed, auditable repositories with history, aliases, and deployment hooks.

**Examples** include Cuebit, Langfuse, Agenta, Pezzo, PromptLayer, Latitude, LangSmith Hub, Glue-Prompt, PromptBase, and FlowGPT (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local-first version control, and transparent prompt lineage — ideal for teams prioritizing data sovereignty, avoiding vendor lock-in, and managing prompts as versioned engineering artifacts.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[LangSmith Hub](https://smith.langchain.com/hub)**  
  **The central hub for LangChain prompts, chains, and agents** — explore and contribute community prompts for RAG, agents, and text-to-SQL . **Integrated prompt management for LangChain ecosystem teams** with versioning, testing, and deployment tightly coupled to chains and agents . **Built by the creators of LangChain** with full awareness of the LLM application graph when managing prompts . **Best for teams already building on LangChain** wanting community prompts and native ecosystem integration.

- **[PromptBase](https://promptbase.com/)**  
  **Marketplace for buying and selling prompts** across ChatGPT, Midjourney, DALL·E, and Stable Diffusion. Curated prompt marketplace with seller payouts.

- **[FlowGPT](https://flowgpt.com/)**  
  **Community platform for discovering and sharing ChatGPT prompts** with use-case categories, rankings, and social features.

- **[PromptHero](https://prompthero.com/)**  
  **Prompt search engine and community** focused on AI art generation prompts for Midjourney, Stable Diffusion, and DALL·E.

- **[AIPRM](https://www.aiprm.com/)**  
  **Chrome extension providing a curated prompt library** for ChatGPT with team workspaces and prompt management.

## Open-Source GitHub Projects

- **[Cuebit](https://github.com/iRahulPandey/Cuebit)**  
  **The open-source, local-first prompt registry built for GenAI development teams** — PyPI package, Apache licensed . **Full prompt version control with history and lineage tracking** . **Alias system** (`summarizer-prod` → versioned prompt) for stable production references while iterating . **Tags and metadata** for organizing prompts across projects and tasks . **Template variables detection and validation** with preview and rendering . **Version comparison with visual diffs** . **Streamlit-based visual dashboard** plus **FastAPI REST API** (`/api/v1/...`) and **full CLI support** for automation . **Audit trail** with `created_at`, `updated_at`, and `updated_by` . **Import/Export** for backup and sharing . **`cuebit serve`** launches both API and UI . **Best for teams wanting a local-first, self-hosted prompt registry** with version control and a visual dashboard, without a cloud dependency .

- **[Langfuse](https://github.com/langfuse/langfuse)**  
  **The MIT-licensed AI engineering platform with natively integrated prompt management** — self-hostable on every tier . **Prompt management stores, versions, labels, and serves prompts** with client-side SDK caching so a fetch after the first hit does not add latency . **Tracing, evaluation, and experiments live in the same project** — pull a production example into a dataset in one click, change a prompt, run an experiment, and keep monitoring live traffic without an export step or tool switch . **All product features are MIT-licensed** including LLM-as-a-Judge evaluations, the playground, prompt experiments, and annotation queues in the free self-hosted distribution . **Best for teams wanting prompt management tightly integrated with tracing and evaluation** in one open-source platform .

- **[Agenta](https://github.com/agenta-ai/agenta)**  
  **Open-source LLMOps platform with integrated prompt management, evaluation, and observability** — all functional features now MIT-licensed . **Prompt playground** for comparing prompts side by side against test cases . **Multi-model support** for 50+ LLMs or bring-your-own models . **Version control with branching and environments** . **Complex configuration schemas** enabling SMEs to collaborate beyond simple prompts . **Flexible testsets** from production data, playground experiments, or CSV uploads . **20+ pre-built evaluators** plus custom evaluators and LLM-as-judge . **OpenTelemetry-native tracing** compatible with OpenLLMetry and OpenInference . **Best for teams wanting collaborative prompt engineering with evaluation** in one self-hostable platform .

- **[Pezzo](https://github.com/pezzolabs/pezzo)**  
  **Open-source, developer-first LLMOps platform for prompt design, version management, and instant delivery** — fully cloud-native and open-source . **Streamlines prompt design, version management, instant delivery, collaboration, troubleshooting, and observability** in one place . **Node.js, Python, and LangChain SDKs** with prompt management support across all three . **Best for teams wanting a developer-first prompt management platform** with multi-language SDK support .

- **[Glue-Prompt](https://pypi.org/project/glueprompt/)**  
  **Git-native prompt repository server** — prompts stored as YAML files in Git repositories, served via FastAPI . **RepoManager** clones and caches prompt repositories from remote URLs . **PromptLoader** loads and caches YAML prompts with TTL support . **TemplateRenderer** renders Jinja2 templates with variable substitution . **VersionManager** manages Git branches and tags for versioning . **WorktreeManager** handles concurrent version access in server mode . **REST API** with `/repos/{repo}/prompts/{prompt_path}` and `/repos/{repo}/prompts/{prompt_path}/render` endpoints, plus interactive Swagger UI and ReDoc . **Security considerations**: path validation against directory traversal and Jinja2 `SandboxedEnvironment` for untrusted templates . **Best for teams wanting Git-native prompt storage** with a serveable API and semantic versioning in YAML .

- **[PromptLayer](https://github.com/MagnivOrg/prompt-layer-library)**  
  **The first platform built for prompt engineers** — acts as middleware between your code and OpenAI's SDK . **Records all API requests** for search and exploration in the dashboard . **`pl_tags`** for grouping requests in the dashboard . **`return_pl_id`** returns the request ID as a tuple element . **Python and JavaScript wrapper libraries** available . **OpenAI Agents telemetry** and **Claude Agents plugin** support as optional extensions . **Best for teams wanting request-level tracking and prompt management** with minimal code changes .

- **[Latitude](https://github.com/latitude-dev/latitude-llm)**  
  **Open-source AI engineering platform with observability and evaluations first, then an eval-driven reliability loop** — LGPL-3.0 licensed with a more permissive commercial license available . **Capture prompts, inputs/outputs, tool calls, and latency/token usage/cost from real traffic** . **Prompt playground** to reproduce runs, iterate with real inputs, version changes, and publish to the AI Gateway . **Datasets** for batch testing and regression suites . **Built-in evals, LLM-as-judge, and human-in-the-loop scoring** . **Annotations** turn human judgment into trackable signals . **Issue discovery** clusters failures into recurring issues . **Prompt optimizer (GEPA)** searches prompt variations against eval suites . **Best for teams wanting an eval-driven reliability loop** that continuously improves prompts from production failures .

### Additional Strong Open-Source Options

- **promptfoo** — Open-source CLI and library for evaluating and red-teaming LLM apps. Test-driven LLM development with matrix views, red teaming, and CI/CD integration. Runs completely locally [citation:6].
- **llm-templates-latitude** — Plugin allowing prompts managed in Latitude to be used as templates in the `llm` CLI, combining centralized prompt management with flexible model execution [citation:15].
- **PromptLayer (Open Source)** — The wrapper libraries are open source, enabling request tracking without changing your OpenAI SDK usage [citation:3][citation:12].

**Frameworks for building custom systems**: Combine **Cuebit** for local-first prompt versioning with aliases and a visual dashboard, **Langfuse** for prompt management tightly integrated with tracing and evaluation, **Agenta** for collaborative prompt engineering with evaluation pipelines, **Glue-Prompt** for Git-native YAML prompt storage served via API, and **promptfoo** for test-driven evaluation before promoting prompts to production — to build a prompt repository stack tailored to your team's workflow, deployment model, and evaluation requirements.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Prompt repositories differ significantly in deployment model, versioning approach, and ecosystem coupling. **Cuebit is local-first and self-hosted** — no cloud dependency, with aliases for stable production references . **Langfuse open-sourced all product features under MIT on June 4, 2025** — prompt management, evaluations, and experiments are all in the free self-hosted distribution . **Agenta open-sourced all functional features under MIT** including evaluation and prompt management, keeping only enterprise collaboration (RBAC, SSO, audit logs) under a separate license . **Glue-Prompt stores prompts as YAML in Git** — versioning is Git-native, with semantic versioning conventions for stable releases . **PromptBase and FlowGPT are marketplaces** — prompts are shared publicly, not managed as private engineering artifacts.
- Self-hosted open-source solutions require proper backup of prompt registries, authentication for API access, and consistent version pinning across development and production environments.

---

**Made for AI engineers, prompt engineers, and teams managing prompts as versioned engineering artifacts.**
Let's make prompt repositories more open, version-controlled, and evaluation-driven.
