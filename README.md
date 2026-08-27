# Sergey Morev, MD/PhD

**Clinical AI safety for the agentic era — deterministic boundaries for probabilistic systems, before and after they act.**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--6088--1880-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-6088-1880)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sergemrv-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sergemrv/)
[![Email](https://img.shields.io/badge/email-smorev.research%40gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:smorev.research@gmail.com)
[![Scope](https://img.shields.io/badge/scope-personal%20%C2%B7%20non--commercial-475569?style=flat-square)](#scope--independence)

MD/PhD — pediatric surgery, then five years in pharmacovigilance and medical affairs (Sanofi, Teva). I now apply that discipline to autonomous AI agents. I call this frame **AI Vigilance** — pharmacovigilance logic for runtime agent behavior. As AI moved from chat models to autonomous agents, the safety question moved from *"what did the model say?"* to *"what is this agent allowed to do, and on what evidence?"* Drug safety has long-established methods for a structurally similar problem: never trust a claim of safety — demand observed evidence, per case, with an audit trail.

## Selected projects

- **[EBAC-T4 — Deterministic Trace-Bound Authorization for High-Risk EHR Writes](https://github.com/sergey-morev/Deterministic-Trace-Bound-Authorization-for-High-Risk-EHR-Writes)**
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21281597.svg)](https://doi.org/10.5281/zenodo.21281597)
  Authorization gate for one high-risk action: execution authority per evidence cycle, ALLOW / DOWNGRADE / HALT with reason codes, HITL approval bound to exact payloads. Reference artifact, not production software.

- **[Clinical Verifiable Gates](https://github.com/sergey-morev/clinical-verifiable-gates)**
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21328660.svg)](https://doi.org/10.5281/zenodo.21328660)
  Deterministic verifier kernel: extractor contracts, UNKNOWN-by-default fields, PASS / BLOCK / ABSTAIN with ordered reason codes, evaluation-only Silence oracle. Installable, tested, with expected outputs published for each fixture.

- **[Audit the Verifier](https://github.com/sergey-morev/audit-the-verifier)**
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22081466.svg)](https://doi.org/10.5281/zenodo.22081466)
  Development-terminal audit study: specializes finite-population weighted-sampling machinery to estimate joint dangerous-error risk inside a primary-model/verifier confident-agreement region under a fixed oracle budget. The frozen 48-of-48 structural-representation gate left the aggregate statistic undefined (`INCONCLUSIVE_BY_DEGENERACY`) — published as development evidence, not a confirmatory result.

- **[CASEF — Clinical AI Safety Evaluation Framework](https://github.com/sergey-morev/CASEF-Clinical-AI-Safety-Evaluation-Framework)**
  ![Status](https://img.shields.io/badge/status-contract%20foundation%20v0.6.1-475569?style=flat-square)
  Qualification framework for LLM behavior under explicit constraints: spec → measurement → gates → evidence. v0.6.1 provides the contract foundation and validated schemas; the executable qualification pipeline does not exist yet. *Generation is cheap. Qualification is not.*

- **[Space Model Lab v3](https://github.com/sergey-morev/space-model-lab-v3)**
  [![Live demo](https://img.shields.io/badge/demo-live-16a34a?style=flat-square)](https://sergey-morev.github.io/space-model-lab-v3/)
  Case study of governed multi-agent development: a browser-based physics sandbox built by a provider-diverse AI team (architect, PM/auditor, gated single-writer executor) under human PI approval — with a decision log, commit-hash receipts, and a reproducible invariant baseline as the public review surface.

- **[Modular Reasoning Framework (MRF)](https://github.com/sergey-morev/Modular-Reasoning-Framework-MRF)**
  ![Status](https://img.shields.io/badge/status-closed%20Jul%202026-94a3b8?style=flat-square)
  Retained as a historical artifact: external reasoning orchestration for fast language models — which I read in retrospect as a predecessor of the governed-orchestration work above.

## Research areas

1. **Pre-action authorization & deterministic safety gates** — execution authority granted per evidence cycle, not by role or prompt; deterministic ALLOW / DOWNGRADE / HALT and PASS / BLOCK / ABSTAIN gates for state-changing steps; evidence model: traces + constraints + audit artifacts (natural-language claims alone aren't evidence).
2. **Qualification under pressure & behavior stability** — reproducible crash-tests for role drift; auditable FAIL artifacts; omission-aware evaluation: missed critical actions, not only wrong ones, are treated as a first-class failure mode.
3. **Governed human–agent development (PI-led)** — provider-diverse specialist roles under one human PI; decision logs, per-action write gates, receipts with observed validation results; **CLAIMED vs OBSERVED** discipline: an audit without a commit hash is a claim, not an observation. Applied throughout Space Model Lab v3.
4. **Architecture selection under hard constraints** — decision protocols for LLM-only vs world-model vs hybrid approaches; hard tradeoffs: latency budgets, verification independence, cost-of-error.

## How I do my research (independent & verifiable)

- Method sanity checks: framing, assumptions, failure modes; independent cross-checking
- Engineering discipline: prototypes → documented, testable artifacts; stable interfaces; minimal reproducible examples
- Adversarial QA: stress tests for unsafe behavior, hallucinated actions, and format brittleness; definition-of-done gates

## Contact

Open to open-source collaboration, research discussion, peer review, and unpaid writing/speaking where appropriate.

📫 **smorev.research@gmail.com** · [ORCID 0009-0000-6088-1880](https://orcid.org/0009-0000-6088-1880) · [LinkedIn](https://www.linkedin.com/in/sergemrv/)

## Scope & independence

All of the above is personal, independent, non-commercial open-source research, done in my own time with my own resources. My current employment is in transportation & logistics (New Brunswick, Canada) and is unrelated to this research. I do not offer commercial or paid services through these projects.
