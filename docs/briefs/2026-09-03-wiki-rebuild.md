# Public Wiki rebuild brief

Status: confirmed by the operator on 2026-09-03.

## Outcome

Replace the previous market/vision Wiki with a current user help center for
Nicegram. Explain what each product feature does, how a user reaches it, where it
is available, and what can prevent it from appearing.

## Audience and language

- Primary reader: a Nicegram user trying to complete a task.
- Secondary reader: support, product, and engineering teams checking what the
  product publicly promises.
- Primary language: English. Localized editions are separate deliverables.
- Voice: calm expert with a humanization pass.

## Source ledger

| Source | Use | Authority | Contradictions |
|---|---|---|---|
| `https://nicegram.me` | Current public product language and canonical domain | Public | Some older privacy and feature copy is broader than store or code evidence |
| `https://nicegram.me/download` | Live/beta labels and official download links | Public | “Unlimited” is implemented with platform-specific practical limits |
| Apple App Store and Google Play | Current distribution and store disclosures | Public | Store privacy disclosures contradict the retired Wiki’s “no personal data” claim |
| `nicegram/Nicegram-iOS` | iOS source and build requirements | Public source | Private feature packages limit implementation visibility |
| `nicegram/Nicegram-Android` | Android source and build requirements | Public source | A private composite build limits implementation visibility |
| `nicegram/nicegram-desktop` | Desktop source-visible additions | Public source | Source presence is not proof of a released feature |
| Private Nicegram dataroom | Cross-repository ownership and evidence map | Internal | Internal names and topology must not leak into public help |

Contradictions: the replacement Wiki uses the narrower claim, marks uncertain
availability, and links to the current policy or store instead of inventing a
guarantee.

## Requirements

| ID | Requirement | Verification |
|---|---|---|
| REQ-01 | Remove the old market, token, earning, and vision Wiki | `git ls-files` and `SUMMARY.md` contain no retired content pages |
| REQ-02 | Publish a task-oriented feature catalog | Every supported feature family appears in `features/README.md` and navigation |
| REQ-03 | Explain purpose, operation, availability, and limitations | Documentation structure check |
| REQ-04 | Use `nicegram.me` for current public Nicegram links | repository-wide link scan |
| REQ-05 | Do not present source-only or beta work as generally available | status labels and source review |
| REQ-06 | Add voice, terminology, facts, UX foundation, and scenarios | required authoring files exist |
| REQ-07 | Update public iOS, Android, Desktop, and organization descriptions | README diff and GitHub metadata check |
| REQ-08 | Keep app links on the main domain and preserve unrelated local work | live association-file check and targeted status review |

## Autonomy and release

The operator explicitly authorized full replacement of the existing Wiki and
updates to the core Nicegram repository descriptions. The work may update local
files and GitHub repository metadata. Publishing commits is not implied; each
repository is handed back as a reviewable diff.

## Done

All requirements have evidence, Markdown links resolve or are intentionally
external, no active public link uses the retired root domain, and each changed
repository retains unrelated local changes.
