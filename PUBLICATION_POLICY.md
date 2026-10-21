# Publication policy

How work becomes public in Sterile Field, and what never does.

Sterile Field is a one-person lab maintained by Dr. Ravi Teja Thiriveedhi. Production systems stay private; this organisation holds **new** repositories written for publication, never copies of private ones.

## Confidentiality levels

| Level | Examples | May appear here? |
|---|---|---|
| Public | Showcase docs, frameworks, templates, demos on invented data | Yes, after the five gates |
| Sanitised summary | Architecture descriptions, aggregate metrics, lessons | Yes, rewritten for publication, after the five gates |
| Private | Engine and governor code, agent prompts and configurations, internal dashboards, commercial playbooks | No |
| Client-confidential | Anything about a client system beyond an approved anonymised case study | Only with the client's written permission, anonymised |
| Never | Personal or patient data, credentials, client names and people, clinical case volumes | No |

## The five gates

| Gate | What it checks |
|---|---|
| G1 · Allow-list | Only files listed for publication are copied out; any other file stops the release |
| G2 · Secret and deny-list scan | Secret scanners across the full history, plus a private deny-list of client names, hosts, paths and personal-data markers |
| G3 · Fresh history | Each export is a new squashed commit; private history never travels |
| G4 · Fresh-context review | An AI reviewer that did not write the material checks accuracy, overclaims and privacy; G5 is the human check |
| G5 · Owner approval | The owner approves the release by hand and confirms the licence |

## How showcases stay current

Private work grows continuously; public showcases change only at meaningful milestones:

- **Triggers create candidates, not releases.** A private release tag, a nominated pull request or the monthly review proposes an update.
- **An update runs only when** the allow-listed files really changed and the owner starts it.
- **Every update arrives as a pull request** to the public repository, re-checked by public CI, and is released only after owner approval.
- **At most one showcase release per repository every two weeks**, batched.
- Client-derived showcases are never updated automatically; their figures change only by hand, with the client's written permission.

## Data in demos

Demos use invented or synthetic data only, labelled "synthetic, not real". No real patient, client or personal data is used to build, test or illustrate anything here.

## Claims

- Numbers link to their method or source, or are labelled with where they come from.
- Regulatory wording says systems are *designed toward* a regulation (for example India's DPDP Act), never certified or compliant.
- Nothing here is clinical advice or for clinical use as-is.

## AI assistance

AI coding agents draft much of the material under the owner's specifications. The owner reviews every change and owns every claim.

## Corrections

Spotted an error, an overclaim or something that should not be public? Open an issue in the repository or write to dr.raviteja1981.new@gmail.com. Privacy reports are handled first.
