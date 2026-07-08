# Job Requirements — AI Infrastructure Team Lead / Engineering Manager

> **Cycle:** 2026-07
> **Postings reviewed:** 25 (last 90 days preferred; a small number outside that window are noted with lower confidence)
> **Delta recommendation:** **no change** — every observed requirement theme is either already covered at this altitude, owned by a lower-level track (with team-lead prereq'd on it), or below the additive-change frequency threshold.
> **Machine-readable index:** [.aicg/job-requirements.json](.aicg/job-requirements.json)

## How this file is organized

Requirements are grouped by ownership. For each requirement we list:

- **Status** — `covered`, `covered-by-lower-track`, or `external`.
- **Frequency** — share of the 25 sampled postings that name the requirement (rough estimate; the additive-change threshold is 0.30).
- **Owner** — role that primarily teaches it. When ownership sits at a lower level, this file links out rather than duplicating.
- **Curriculum coverage** — module / project paths inside this repo, or a link to the sibling track that owns it.
- **Evidence** — verbatim quotes from postings. Full posting URLs are in the JSON index.

---

## 1. Engineering-management fundamentals

**Status:** covered · **Frequency:** ~1.0 · **Owner:** `ai-infra-team-lead-learning`

1:1s, structured feedback, coaching, performance management, career growth.

**Curriculum coverage**

- [lessons/mod-702-people-management/](lessons/mod-702-people-management/)
- [projects/project-05-leadership-capstone/](projects/project-05-leadership-capstone/) — theory-of-leadership doc, portfolio reflection

**Evidence (selected)**

- Anthropic (Agent Prompts & Evals): *"Recruit and retain engineers... 8+ years software engineering with 3+ years managing engineering teams."*
- Descript (EM, Agent): *"Run regular structured 1:1s, provide candid feedback at meaningful milestones, and actively invest in each person's growth."*
- Caylent (AI/ML EM): *"Run regular structured 1:1s, provide candid feedback at meaningful milestones."*
- Hightouch (EM, Agents): *"Foster growth of team members and ensure strong engagement and motivation."*
- DoorDash (EM, Merchant AI/ML): *"Mentor and develop engineers, shaping the next generation of applied AI leadership."*

## 2. Team strategy and roadmap

**Status:** covered · **Frequency:** ~0.85 · **Owner:** `ai-infra-team-lead-learning`

Multi-quarter vision, quarterly OKRs, capacity model, dependency map, stakeholder communication.

**Curriculum coverage**

- [lessons/mod-703-project-roadmap/](lessons/mod-703-project-roadmap/)
- [projects/project-02-technical-strategy/](projects/project-02-technical-strategy/) — 12-month strategy, capacity model, dependency map, executive narrative

**Evidence (selected)**

- Netflix (Sr EM Model Inference & Serving): *"setting the strategic vision and execution across multiple teams that deliver the core model serving infrastructure for all of Netflix."*
- Affirm (Sr EM ML Platform): *"Own the technical strategy and roadmap for ML Platform, covering real-time and batch feature computation, model training infrastructure, and model serving at scale."*
- DoorDash: *"Define a multi-year strategy and execute the AI roadmap across key Mx pillars — Onboarding, Menu Media Understanding & Generation, Menu Metadata Intelligence, and Agentic Task Automation."*
- Slack / Salesforce: *"Define, evolve, and communicate the team's vision, mission, and strategy across Slack."*
- Applied Intuition: *"Set team goals aligned with research milestones and production deployment."*

## 3. Hiring, interview design, and closing senior IC talent

**Status:** covered · **Frequency:** ~0.95 · **Owner:** `ai-infra-team-lead-learning`

Job-description authoring, interview rubrics, sourcing pipeline, close conversations.

**Curriculum coverage**

- [lessons/mod-705-hiring-onboarding/](lessons/mod-705-hiring-onboarding/)
- [projects/project-03-hiring-onboarding/](projects/project-03-hiring-onboarding/) — hiring playbook, interview guides, 30-60-90 onboarding

**Evidence (selected)**

- Anthropic: *"Senior IC recruiting and closing experience in competitive markets."*
- Anysphere (Cursor): *"Talent sourcing and hiring capability."*
- Cohere Health: *"Recruit, develop, and retain world-class platform engineers."*
- Caylent: *"Set the technical bar for ML roles on your team, lead or oversee technical assessments, and make hiring decisions you can stand behind."*
- Hudl: *"Hiring and managing a team of Senior to Mid-level Engineers while fostering a culture of technical excellence."*

## 4. Cross-functional coordination

**Status:** covered · **Frequency:** ~0.90 · **Owner:** `ai-infra-team-lead-learning`

Partnering with research, product, security, legal, finance, customer teams.

**Curriculum coverage**

- [lessons/mod-704-cross-team-coordination/](lessons/mod-704-cross-team-coordination/)
- [projects/project-04-platform-project/](projects/project-04-platform-project/) — DACI, stakeholder map, dependency-tracking, cross-team RACI

**Evidence (selected)**

- Anthropic: *"Demonstrated peer relationship management across different organizational cultures."*
- Applied Intuition: *"Collaborate with research, stack development, and infrastructure teams."*
- Cohere Health: *"Partner closely with Product, Clinical Operations, Customer Success, Security, and the Chief Data & AI Officer's organization."*
- Datadog (Manager II, Applied AI): *"Drive collaboration across Applied AI, product, and partner engineering teams to deliver on priorities."*
- Pinterest: *"Collaborate closely with Ads Ranking & Bidding, Measurement Products, and Conversion Ingestion teams to define interfaces, SLAs, and success metrics."*

## 5. Team operations, on-call, and incident response

**Status:** covered · **Frequency:** ~0.80 · **Owner:** `ai-infra-team-lead-learning`

Cadences (standups, retros, sprint planning), reliability rituals, incident response as a team practice.

**Curriculum coverage**

- [lessons/mod-701-team-operations/](lessons/mod-701-team-operations/)
- [projects/project-01-team-process/](projects/project-01-team-process/) — team-process playbook, sprint framework, on-call rotation, PIR template

**Evidence (selected)**

- Datadog: *"Own operational excellence for your teams' systems: reliability, on-call, incident response."*
- Descript: *"Drive operational excellence: Ensure execution is predictable, reliable, and sustainable."*
- Hightouch: *"Up-level the team on reliability, resulting in fewer incidents, catching our own issues before our customers do."*
- Affirm: *"Establish engineering excellence across the organization: reliability, observability, developer experience, and operational rigor."*

---

## 6. Technical depth: distributed training, model serving, GPU clusters, K8s

**Status:** **covered-by-lower-track** · **Frequency:** ~0.80 · **Owner:** [`ai-infra-senior-engineer-learning`](https://github.com/ai-infra-curriculum/ai-infra-senior-engineer-learning) (prereq); further specialty at [`ai-infra-ml-platform-learning`](https://github.com/ai-infra-curriculum/ai-infra-ml-platform-learning), [`ai-infra-performance-learning`](https://github.com/ai-infra-curriculum/ai-infra-performance-learning), [`ai-infra-mlops-learning`](https://github.com/ai-infra-curriculum/ai-infra-mlops-learning)

Postings expect deep technical experience with distributed training frameworks, GPU orchestration, model-serving stacks (vLLM, TensorRT-LLM, Triton), Kubernetes / Slurm, and networking (InfiniBand, RDMA). At team-lead altitude this is **prerequisite knowledge**, not new curriculum — the team-lead README states 3+ years of prior senior AI-infra experience as an entry bar.

**Do not duplicate here.** Reference the owning tracks above.

**Evidence (selected)**

- Anysphere: *"Familiarity with model serving frameworks (vLLM, TensorRT-LLM, TGI), load balancing, or multi-provider architectures."*
- Applied Intuition: *"Strong understanding of distributed training frameworks (e.g., PyTorch Distributed, Megatron-LM, DeepSpeed, FSDP)... GPU cluster management, high-performance networking (InfiniBand, RDMA)."*
- General Motors: *"Expertise in ML inference, model serving frameworks (triton, rayserve, vLLM etc)."*
- Affirm: *"Deep expertise in building and operating large-scale ML infrastructure — feature stores, model serving systems, training pipelines."*

---

## 7. Eval-platform ownership / model-quality regression control

**Status:** covered · **Frequency:** ~0.28 (below 0.30 threshold) · **Owner:** `ai-infra-team-lead-learning` (for prioritization/roadmap) with build-work owned at ML-Platform / MLOps tracks

Manager altitude expectation is *not* "build the eval platform" — it is: prioritize the investment, staff the team, hire the right ICs, and defend the roadmap to product/leadership. That work is exercised by:

- [lessons/mod-703-project-roadmap/](lessons/mod-703-project-roadmap/) — roadmap negotiation and prioritization
- [projects/project-02-technical-strategy/](projects/project-02-technical-strategy/) — capacity model, coherent-actions selection, quarterly OKR proposal

For **building** the eval platform itself, see the ML Platform / MLOps tracks (technical ICs).

**Below-threshold note.** Frequency is close to the 0.30 line and worth watching next cycle; if explicit "own the eval platform" language crosses 0.30 in the next 90-day window, propose adding a targeted exercise inside `mod-703` or `project-02` — not a new module.

**Evidence (selected)**

- Anthropic (Agent Prompts & Evals): *"Own the product-side eval platform: the frameworks, dashboards, bulk runners, and CI integrations."*
- Netflix (Model Evals & Data Curation): *"Design rigorous benchmarks and evaluation methodologies across ranking & recommendations, content understanding, and language/text generation."*
- Mitratech: *"Design and operationalize automated and human-in-the-loop evaluation strategies, integrating regression checks."*
- Datadog: *"Build evaluation and quality practices for AI systems, offline benchmarks, online metrics."*
- Descript: *"Experience building agents, developing evals, or leading teams building LLM-powered products."*
- DoorDash: *"Own the end-to-end lifecycle of ML systems — from ideation and experimentation to productionization and continuous improvement."*

## 8. GPU cost / FinOps / capacity planning at team altitude

**Status:** covered · **Frequency:** ~0.20 (below 0.30 threshold) · **Owner:** `ai-infra-team-lead-learning`

Explicit cost / capacity language shows up in inference-heavy postings. At team-lead altitude this maps to strategy and capacity work, not to token-level accounting.

- [projects/project-02-technical-strategy/](projects/project-02-technical-strategy/) already requires a capacity model that survives a hostile CFO/finance review and an explicit cost narrative in the executive artifact.
- [lessons/mod-703-project-roadmap/](lessons/mod-703-project-roadmap/) covers roadmap negotiation with finance/product trade-offs.

**Evidence (selected)**

- Anysphere: *"Skilled at reasoning about cost/performance tradeoffs at scale (GPU utilization, provider economics, capacity planning)."*
- Anysphere: *"Oversee GPU cluster utilization and capacity planning across providers."*
- Applied Intuition: *"Optimize performance metrics including throughput, fault tolerance, GPU utilization, and cost efficiency."*
- Reddit (Sr EM Developer Productivity): *"security, cost management, privacy, compliance, and operational safety are built into the development lifecycle."*

## 9. Model-launch operational leadership (dark launch, canary, rollback)

**Status:** covered · **Frequency:** ~0.16 (below 0.30 threshold) · **Owner:** `ai-infra-team-lead-learning`

The manager-altitude discipline (pre-committed rollback criteria, launch-readiness reviews, staged rollout) is covered exhaustively in [projects/project-04-platform-project/](projects/project-04-platform-project/) — the launch-plan deliverable specifies "go/no-go gates, dark launch, canary, phased rollout, and pre-committed rollback criteria." Model launches are a variant of the same discipline, not a distinct competency.

**Evidence (selected)**

- Anthropic (Agent Prompts & Evals): *"Be a steady hand through model launches — these are the team's highest-stakes operational moments."*
- Anthropic: *"Provide operational leadership during model launches."*
- Anysphere: *"Implement routing backpressure and admission control mechanisms."*

---

## 10. AI governance / model risk at manager altitude — external / watch-list

**Status:** **external** · **Frequency:** ~0.20 (below 0.30 threshold) · **Owner:** `ai-infra-team-lead-learning` (partial via project-02 diagnosis + project-04 security coordination)

Explicit framework-familiarity language (NIST AI RMF, ISO/IEC 42001, EU AI Act) appears in only ~5 of the 25 postings sampled, keeping the requirement below the 0.30 additive threshold this cycle. However, industry commentary (e.g. Augment Code's 2026 job-spec analysis) argues the trend is real and undercounted in explicit JD language. This is a **watch-list item** for the next cycle.

**Where the existing curriculum touches this today**

- [projects/project-02-technical-strategy/](projects/project-02-technical-strategy/) — the Diagnosis step already surfaces compliance and regulatory forces as strategic inputs.
- [projects/project-04-platform-project/](projects/project-04-platform-project/) — the security-team partner in the multi-tenant inference gateway scenario exercises cross-functional security/legal coordination.

**External resources for learners who want to go deeper now** (out of scope for the current curriculum modules):

- NIST **AI Risk Management Framework (AI RMF 1.0)** — free download.
- ISO/IEC **42001:2023** — AI management systems standard.
- **EU AI Act** — in force 2024; high-risk-system obligations effective from 2026.
- Anthropic **Responsible Scaling Policy (RSP)** — public reference for staged capability-risk gating.

**Evidence (selected)**

- Mitratech: *"Familiarity with AI governance and risk frameworks such as NIST AI RMF or ISO/IEC 42001."*
- Mitratech: *"Translate emerging governance and risk expectations into working engineering systems and platform controls."*
- Reddit: *"driving AI governance and platform adoption in a way that preserves engineering creativity while ensuring security, cost management, privacy, compliance, and operational safety are built into the development lifecycle."*
- Cohere Health: *"Establish the platforms and operational capabilities required to manage AI behavior at scale."*
- Caylent: *"AWS ML ecosystem expertise including SageMaker, Bedrock, and full ML lifecycle governance."*

**Re-evaluation trigger.** If explicit AI-governance-framework mentions cross 0.30 in the next 90-day sample, the recommended action is a targeted exercise (e.g. `exercise-06-governance-diagnosis`) inside `project-02-technical-strategy` — **not** a new module. <!-- needs-research: whether the AI Governance track in the parent org (`ai-governance-curriculum`) already owns this at a different altitude that team-lead should simply link to. -->

---

## Delta summary

| Change class     | Count | Notes |
|------------------|-------|-------|
| New modules      | 0     | No requirement crosses both frequency and coverage-gap thresholds. |
| New exercises    | 0     | Nearest candidates (eval-platform ownership, AI governance) are below 0.30; both are partially exercised by existing content. |
| New projects     | 0     | Five projects already cover the full leadership arc — process, strategy, hiring, cross-functional, capstone. |

See [`.aicg/curriculum-plan-delta.json`](.aicg/curriculum-plan-delta.json) for the empty-arrays delta artifact.
