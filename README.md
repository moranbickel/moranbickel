# Moran Bickel

**Israeli litigator — civil litigation & international arbitration — building ORCA, an AI legal reasoning system for Israeli civil law.**

A programmer builds a document generator. A litigator builds a decision system. ORCA is a decision system — it reasons about which causes of action hold, which elements the evidence supports, and what relief follows. The design constraint isn't passing a demo; it's surviving cross-examination.

ORCA itself is closed-source. **The methodology that produced it is open** — the disciplines below were extracted from production practice (and production failures), not invented for a write-up. Each one generalizes an internal ORCA discipline into something domain-neutral.

## Methodology

- **[Russian-Judge](https://github.com/moranbickel/Russian-Judge)** — Adversarial AI review with structured verdicts: a C/I/M defect taxonomy, a numerical pass floor, single- and cross-model audit modes. *New here? Start with this one — it's the load-bearing piece.*
- **[Three-Body-Protocol](https://github.com/moranbickel/Three-Body-Protocol)** — Keeping a thinking AI, an implementing AI, and a human aligned across sessions: STATUS_NOW, a decisions log, and briefs as bridge artifacts.
- **[Peer-Worker-Convergence](https://github.com/moranbickel/Peer-Worker-Convergence)** — Running multiple AI coding sessions on one repo without branch divergence: α/β/γ rules, the precision-target side-branch ceremony, a shared-file resolution playbook.
- **[CSAE](https://github.com/moranbickel/CSAE)** — Continuous Session-Attested Evidence: attesting AI-generated commits to a verifiable audit chain — intent registration, bundle authoring, audit mirror, validator.

More in the series, in progress: **[Pre-IMPL Forensic Discipline](https://github.com/moranbickel/Pre-IMPL-Forensic-Discipline)** (catching wrong premises before they become wrong commits — published as a v0.1 draft) and **Engineering Rules** (disciplines extracted from production failures).

## Why a litigator publishes this

Most AI-workflow advice is written by engineers for engineers. These pieces come from running AI-assisted work where the output had to meet a court-filing standard — where a wrong fact, a stale premise, or an unattributable change carries real cost. The disciplines are what survived that bar.

Issues and discussions on each repo are open.
