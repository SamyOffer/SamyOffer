<p align="center">
  <img src="./assets/minimal-banner.svg" alt="Samy Offer — Artificial Intelligence: Big Data, Optimization and Algorithms" width="100%" />
</p>

# Hi, I'm Samy 👋

I'm a **Computer Science master's student at UCLouvain**, specializing in **Artificial Intelligence: Big Data, Optimization and Algorithms**. My work spans language models, combinatorial optimization, and high-performance computing.

Based in **Brussels, Belgium**. I'm exploring **AI Consultant**, **Solutions Engineer**, and **IT / Tech Consultant** roles, with an interest in product, business analysis, and cybersecurity risk.

<p align="center">
  <a href="https://www.linkedin.com/in/samy-offer-38a559293/">LinkedIn</a> ·
  <a href="https://samyoffer.github.io/cours-master-ucl/">Master's learning notes</a> ·
  <a href="https://github.com/search?q=author%3ASamyOffer&type=pullrequests">All my pull requests</a>
</p>

### Master's thesis

**Designing a discovery protocol for switched homing.** A home Internet connection should remain usable when its primary gateway fails; a nearby smartphone could temporarily serve as a cellular backup. The thesis aims to design, implement, and evaluate a protocol that lets devices discover backup gateways, detect failures, choose a replacement, and coordinate the switch. The evaluation will examine IPv6 addressing and routing, connection continuity, failover time, false detections, and protocol overhead.

### Selected academic work

**LLM fine-tuning & retrieval-based question answering** · NLP course  
Fine-tuned language models with LoRA for style-specific generation; built a retrieval-augmented QA system and semantic search experiments with Word2Vec and GloVe.

**Optimization & constraint programming** · Advanced algorithms course  
Implemented constraint models with PyCSP3 and explored Branch & Bound for TSP, dynamic programming, linear programming, and A* search.

**High-performance computing** · Computer architecture course  
Optimized matrix computation with AVX512 and cache-aware blocking; implemented CUDA kernels for parallel pattern matching.

**[Interactive master's learning notes](https://samyoffer.github.io/cours-master-ucl/)**  
Public notes and interactive explanations covering machine learning, data mining, and constraint programming. [Source](https://github.com/SamyOffer/cours-master-ucl).

<!-- Add links to the three academic project repositories when they are published. -->

### Applied AI projects

**JobPilot** · *private repository*  
An AI-assisted job search and application system that evaluates roles, navigates compatible forms, and tracks replies while keeping external actions under explicit control.

- **Source orchestration:** Optional Treg connectors bring Google SERP results and public LinkedIn jobs into the discovery pipeline alongside employer ATS feeds, without relying on a LinkedIn session.
- **Hybrid AI architecture:** Jev/TypeSafe makes structured decisions from actions observed on a page; Playwright executes validated choices. A Gemini LLM drafts free-text answers from confirmed profile facts, with OpenAI and Claude available as alternative providers. Jev checks the drafts before they are used.
- **Controlled execution:** Deterministic code manages budgets, deduplication, workflow state, and submission evidence. Persistent checkpoints support recovery after interruptions; uncertain submissions become explicit exceptions instead of being retried blindly.

**EMAIL** · *private repository*  
An AI-assisted employer intelligence system that connects hiring signals across job boards, career sites, public ATS feeds, and web research to targeted outreach.

- **Treg intelligence layer:** Optional Treg routes combine multiple providers for company discovery, decision-maker research, and separate email verification. Calls are cached and constrained by an allowlist and a zero-cost route policy.
- **AI with evidence:** Gemini supports structured extraction and company qualification using cited public evidence. Uncertain matches remain pending rather than being presented as facts.
- **Human review:** Gemini uses my CV and company signals to prepare tailored drafts and flags claims for review before any message is sent. Resumable tasks and API cost limits keep the workflow controllable.

### Open source contributions

- **[Freesper · PR #3](https://github.com/anthonyjacquelin/freesper/pull/3)** — Fixed Electron/macOS recording-window behavior across displays and workspaces. **Merged.**
- **[tldr-pages · PR #19321](https://github.com/tldr-pages/tldr/pull/19321)** — Added documentation for the `dzdo` command. **Merged.**
- **[tldr-pages · PR #19059](https://github.com/tldr-pages/tldr/pull/19059)** — Added French translations for the `head` command. **Merged.**

[Browse all my public pull requests](https://github.com/search?q=author%3ASamyOffer&type=pullrequests), including earlier iterations.

### Areas and tools

`Applied AI` `Gemini` `Jev / TypeSafe` `Treg` `Playwright` `Optimization` `Python` `TypeScript` `PyTorch` `C / CUDA`

### Let's connect

For AI consulting, solutions engineering, freelance work, or open source collaboration, [connect with me on LinkedIn](https://www.linkedin.com/in/samy-offer-38a559293/).
