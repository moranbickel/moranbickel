# Moran Bickel

Israeli civil litigator. I build ORCA, a closed-source AI reasoning system for
Israeli civil litigation. The repositories here are not ORCA. They are the
domain-neutral disciplines ORCA is built under, published on their own.

One idea runs through all of them: AI-assisted work at a court-filing standard
needs the same things a case needs - an adversarial check, a durable record,
and a verified premise - because a wrong fact, a stale assumption, or an
unattributable change carries real cost. Each repository below is one of those
disciplines, extracted from production practice and from production failures.

## The disciplines

- **[Russian-Judge](https://github.com/moranbickel/Russian-Judge)** - adversarial
  AI review that returns a structured verdict: a defect taxonomy, a numerical
  pass floor, single- and cross-model modes. Start here; the others reference it.
- **[Three-Body-Protocol](https://github.com/moranbickel/Three-Body-Protocol)** -
  keeping a thinking model, an implementing model, and a human aligned across
  sessions, through shared files instead of memory.
- **[Peer-Worker-Convergence](https://github.com/moranbickel/Peer-Worker-Convergence)** -
  running several AI coding sessions on one repository without their branches
  drifting apart.
- **[CSAE](https://github.com/moranbickel/CSAE)** - attaching a durable audit
  trail to AI-generated commits, so the record survives the question asked months
  later.
- **[Pre-IMPL-Forensic-Discipline](https://github.com/moranbickel/Pre-IMPL-Forensic-Discipline)** -
  checking a task's premise against the live system before writing code, so a
  stale note does not become a wrong commit. Published as a v0.1 draft.

## Why a litigator publishes this

Most AI-workflow writing is by engineers, for engineers. These pieces come from
running AI-assisted work where the output had to survive cross-examination. The
disciplines are what held up at that bar. ORCA itself stays closed; the
disciplines do not need to.

Issues and discussions are open on each repository.
