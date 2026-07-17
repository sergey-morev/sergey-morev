# Sergey Morev, MD/PhD

**Clinical AI safety for the agentic era — deterministic boundaries for probabilistic systems, before and after they act.**

Physician-researcher: MD/PhD, 6+ years in pharmacovigilance & drug safety, now applying that discipline to autonomous AI agents. I call this frame **AI Vigilance** — pharmacovigilance logic for runtime agent behavior. As AI moved from chat models to autonomous agents, the safety question moved from *"what did the model say?"* to *"what is this agent allowed to do, and on what evidence?"* Drug safety solved a structurally similar problem decades ago: never trust a claim of safety — demand observed evidence, per case, with an audit trail.

## Selected projects

- **[EBAC-T4 — Deterministic Trace-Bound Authorization for High-Risk EHR Writes](https://github.com/sergey-morev/Deterministic-Trace-Bound-Authorization-for-High-Risk-EHR-Writes)** — authorization gate for high-risk EHR writes: execution authority per evidence cycle, ALLOW / DOWNGRADE / HALT with reason codes, HITL approval bound to exact payloads.
- **[Clinical Verifiable Gates](https://github.com/sergey-morev/clinical-verifiable-gates)** — medical verifier kernel: extractor contracts, UNKNOWN-by-default fields, deterministic PASS / BLOCK / ABSTAIN, Silence gate against fabricated slot-filling.
- **[CASEF — Clinical AI Safety Evaluation Framework](https://github.com/sergey-morev/CASEF-Clinical-AI-Safety-Evaluation-Framework)** — reproducible, artifact-based qualification of LLM behavior under explicit constraints. *Generation is cheap. Qualification is not.*
- **[Space Model Lab v3](https://github.com/sergey-morev/space-model-lab-v3)** — case study of governed multi-agent development: a browser-based physics sandbox built by a provider-diverse AI team (architect, PM/auditor, gated single-writer executor) under human PI approval, with a full decision log and commit-hash receipts.
- **[LLM / World-Model / Hybrid Decision Frame](https://github.com/sergey-morev/llm-worldmodels-hybrid-decision-frame)** — architecture decision protocol for choosing system design under risk, latency, and verification constraints.
- **[Modular Reasoning Framework (MRF)](https://github.com/sergey-morev/Modular-Reasoning-Framework-MRF)** — earlier research: external reasoning orchestration for fast language models; a predecessor of the governed-orchestration ideas above.

## Research areas

1. **Pre-action authorization & deterministic safety gates** — execution authority granted per evidence cycle, not by role or prompt; deterministic ALLOW / DOWNGRADE / HALT and PASS / BLOCK / ABSTAIN gates for state-changing steps; evidence model: traces + constraints + audit artifacts (natural-language claims alone aren't evidence).
2. **Qualification under pressure & behavior stability** — reproducible crash-tests for role drift; auditable FAIL artifacts; omission-aware evaluation: in clinical settings, missed critical actions — not only wrong ones — are the dominant harm mode.
3. **Governed human–agent development (PI-led)** — provider-diverse specialist roles under one human PI; decision logs, per-action write gates, receipts with observed validation results; **CLAIMED vs OBSERVED** discipline: an audit without a commit hash is a claim, not an observation. Demonstrated end-to-end in Space Model Lab v3.
4. **Architecture selection under hard constraints** — decision protocols for LLM-only vs world-model vs hybrid approaches; hard tradeoffs: latency budgets, verification independence, cost-of-error.

## How I do my research (independent & verifiable)

- Method sanity checks: framing, assumptions, failure modes; independent cross-checking
- Engineering discipline: prototypes → documented, testable artifacts; stable interfaces; minimal reproducible examples
- Adversarial QA: stress tests for unsafe behavior, hallucinated actions, and format brittleness; definition-of-done gates

## Contact

Open to open-source collaboration, research discussion, peer review, and unpaid writing/speaking where appropriate.

📫 **smorev.research@gmail.com**

## Scope & independence

All of the above is personal, independent, non-commercial open-source research, done in my own time with my own resources. My current employment is in transportation & logistics (New Brunswick, Canada) and is unrelated to this research. I do not offer commercial or paid services through these projects.
