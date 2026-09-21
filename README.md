# Moran Bickel

Israeli litigator and founder of [ORCA Legal Labs](https://orca-legal.com).
I build tools for checking AI-assisted work: whether the task is still valid,
whether a cited record exists, and whether a review covers the actual change.

## Start with an example

[**agent-crash-tests**](https://github.com/moranbickel/agent-crash-tests) has three
small, synthetic exercises: an already-fixed bug, a nonexistent work item,
and a passing review of an older file. Run the authored demos without an API key,
or give a fresh exercise to your coding agent. Each case includes a control
where proceeding is appropriate.

The demos test the checker. They are not measurements of any model's reliability.

## Tools and working notes

| Repository | What you can use |
|---|---|
| [Docket](https://github.com/moranbickel/Docket) | A work ledger, installer, and checks for duplicate IDs, missing references, and unsupported closures. |
| [Russian-Judge](https://github.com/moranbickel/Russian-Judge) | Review prompts and a structured verdict format. |
| [Three-Body-Protocol](https://github.com/moranbickel/Three-Body-Protocol) | Short status files, decision records, and handoff templates. |
| [Peer-Worker-Convergence](https://github.com/moranbickel/Peer-Worker-Convergence) | Shell scripts and a routine for keeping persistent worker branches in sync. |
| [CSAE](https://github.com/moranbickel/CSAE) | Templates for linking scope, commits, and review records. |
| [Pre-IMPL-Forensic-Discipline](https://github.com/moranbickel/Pre-IMPL-Forensic-Discipline) | A checklist for checking a task's premise before implementation. Draft. |

ORCA's source, client material, and internal records are private. The new crash
tests use invented examples. The methodology repos describe practices; their
evidence limits are stated in the individual projects.

Found a reproducible failure? [Contribute a small case](https://github.com/moranbickel/agent-crash-tests/blob/main/CONTRIBUTING.md).
