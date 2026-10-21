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
| 4 · Fresh-context review | An AI reviewer that did not write the material signs off before release (`docs/review/REVIEW_PASS.md`); gate 5 is the human check |
| 5 · Owner gate | The owner confirms by hand, and picks the licence, before the repo goes public |

## Showcases

<table>
<tr>
<td width="50%"><a href="https://github.com/sterilefield/whatsapp-agent-case-study"><img alt="WhatsApp agent case study: 15-agent platform, 460+ leads, 284 owner-approved follow-ups, −91% heartbeat tokens" src="https://github.com/sterilefield/whatsapp-agent-case-study/raw/main/docs/img/social-preview.png" width="100%"></a><br><sub><a href="https://github.com/sterilefield/whatsapp-agent-case-study"><b>WhatsApp agent case study</b></a> · <a href="https://sterilefield.github.io/whatsapp-agent-case-study/">live demo</a></sub></td>
<td width="50%"><a href="https://github.com/sterilefield/agent-governance-kit"><img alt="Agent governance kit: autonomy levels L0–L4, risk classes R0–R4, mapped to OWASP, NIST AI RMF and ISO/IEC 42001" src="https://github.com/sterilefield/agent-governance-kit/raw/main/docs/img/social-preview.png" width="100%"></a><br><sub><a href="https://github.com/sterilefield/agent-governance-kit"><b>Agent governance kit</b></a> · <a href="https://sterilefield.github.io/agent-governance-kit/">live demo</a></sub></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/sterilefield/llm-token-economics"><img alt="LLM token economics: heartbeat tokens cut from 12.0 M to 1.0 M a day (−91%) with 18 methods" src="https://github.com/sterilefield/llm-token-economics/raw/main/docs/img/social-preview.png" width="100%"></a><br><sub><a href="https://github.com/sterilefield/llm-token-economics"><b>LLM token economics</b></a> · <a href="https://sterilefield.github.io/llm-token-economics/">live demo</a></sub></td>
<td width="50%"><a href="https://github.com/sterilefield/empire-os-reference-architecture"><img alt="Empire OS reference architecture: 9 governed AI agents on an 8 GB Mac mini, 99/99-suite release gate" src="https://github.com/sterilefield/empire-os-reference-architecture/raw/main/docs/img/social-preview.png" width="100%"></a><br><sub><a href="https://github.com/sterilefield/empire-os-reference-architecture"><b>Empire OS reference architecture</b></a> · <a href="https://sterilefield.github.io/empire-os-reference-architecture/">live demo</a></sub></td>
</tr>
</table>

| Repository | What it is | Try it |
|---|---|---|
| [`empire-os-reference-architecture`](https://github.com/sterilefield/empire-os-reference-architecture) | 5-tier layout of a governed multi-agent platform on constrained hardware (8 GB control plane, 99/99-suite release gate, kill switch with human approval tiers) | [Live demo: Control plane playground](https://sterilefield.github.io/empire-os-reference-architecture/) |
| [`llm-token-economics`](https://github.com/sterilefield/llm-token-economics) | How an agent fleet's heartbeat tokens fell 91% (12.0 M → 1.0 M a day): 18 methods, a case study and an audit checklist | [Live demo: Heartbeat token calculator](https://sterilefield.github.io/llm-token-economics/) |
| [`agent-governance-kit`](https://github.com/sterilefield/agent-governance-kit) | Autonomy levels L0–L4, risk classes R0–R4, approval tiers, kill switches and audit templates mapped to OWASP Agentic Top 10, NIST AI RMF and ISO/IEC 42001, with a healthcare overlay for India | [Live demo: Agent governance gate](https://sterilefield.github.io/agent-governance-kit/) |
| [`whatsapp-agent-case-study`](https://github.com/sterilefield/whatsapp-agent-case-study) | Anonymised case study: a single-writer SQLite spine behind a 15-agent WhatsApp and Telegram operations platform for a real-estate brokerage (460+ leads, −91% heartbeat tokens, owner-approved messaging) | [Live demo: Owner approval desk](https://sterilefield.github.io/whatsapp-agent-case-study/) |

All four showcases have passed the five gates and each has a live demo on invented data that runs in your browser. Nothing is published early. How work becomes public, and what never does: [publication policy](https://github.com/sterilefield/.github/blob/main/PUBLICATION_POLICY.md).

**Start here:** [`whatsapp-agent-case-study`](https://github.com/sterilefield/whatsapp-agent-case-study) for a live client system, then [`agent-governance-kit`](https://github.com/sterilefield/agent-governance-kit) for how the agents are kept in check.

## Maintainer

A one-person lab maintained by **Dr. Ravi Teja Thiriveedhi** ([@Raviteja2k2k](https://github.com/Raviteja2k2k)) · clinician turned AI systems architect · 20 years of clinical practice and hospital operations · Hyderabad, India (IST)

[GitHub](https://github.com/Raviteja2k2k) · [LinkedIn](https://www.linkedin.com/in/dr-ravi-teja-thiriveedhi) · dr.raviteja1981.new@gmail.com · private walkthroughs of my own production systems on request, under NDA (client systems only with the client's permission)
