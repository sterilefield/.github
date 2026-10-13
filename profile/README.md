<div align="center">

# Sterile Field

**Clean-room engineering for healthcare AI.**

Sanitised reference architectures, agent-governance kits and LLM cost tooling, extracted from production systems and published without client data, secrets or proprietary code.

</div>

## Why "sterile field"

In surgery, the sterile field is the boundary that decides what may touch the patient. Nothing crosses it without a check. Every repository here crosses a similar boundary before it goes public:

| Gate | What it checks |
|---|---|
| 1 · Allow-list | Only files written for publication are copied out, never whole private repos |
| 2 · Secret and deny-list scan | `gitleaks` across the full history, plus a deny-list of client names, hosts and personal data |
| 3 · Fresh history | Each showcase starts a new git history; private history never ships |
| 4 · Independent review | A separate reviewer signs off before release (`docs/review/REVIEW_PASS.md`) |
| 5 · Owner gate | The owner confirms by hand, and picks the licence, before the repo goes public |

## Showcases

| Repository | What it is | Status |
|---|---|---|
| [`empire-os-reference-architecture`](https://github.com/sterilefield/empire-os-reference-architecture) | 5-tier layout of a governed multi-agent platform on constrained hardware (8 GB control plane, 99/99-suite release gate, kill switch with human approval tiers) | **Public** |
| `llm-token-economics` | How heartbeat token use fell 91% (12.0 M → 1.0 M a day) and the method behind it | In preparation |
| `agent-governance-kit` | Autonomy levels L0–L4, risk classes R0–R4, approval and audit templates mapped to OWASP Agentic Top 10, NIST AI RMF and ISO/IEC 42001 | Planned |
| `whatsapp-agent-case-study` | Anonymised case study: a single-writer SQLite spine behind a 15-agent WhatsApp and Telegram operations platform | Planned |

Repositories appear as each one passes all five gates. Nothing is published early.

## Maintainer

**Dr. Ravi Teja Thiriveedhi** · clinician turned AI systems architect · 20 years of clinical practice and hospital operations · Hyderabad, India (IST)

[GitHub](https://github.com/Raviteja2k2k) · [LinkedIn](https://www.linkedin.com/in/dr-ravi-teja-clinical-ai) · dr.raviteja1981.new@gmail.com
