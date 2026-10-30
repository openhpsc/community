<!-- SPDX-License-Identifier: MIT -->

# Research

This directory holds investigations that help OpenHPSC make informed design
choices. Use Issues to coordinate the work and this directory to preserve the
question, evidence, and conclusions.

## Initial questions

| Topic | Question | Useful output |
| --- | --- | --- |
| Workload | What should the first demonstrator execute and prove? | Inputs, expected outputs, timing needs, and acceptance criteria |
| Candidate subsystem | Which open hardware configuration is practical to reproduce? | Comparison of source availability, licenses, tools, and integration effort |
| RTEMS integration | Which CPU and peripheral interfaces must the BSP support? | Compatibility matrix and identified software gaps |
| Fault protection | What faults does the selected mechanism handle? | Fault model, protection boundary, and experiment proposal |
| Reproducibility | What must another contributor have to repeat the study? | Pinned revisions, environment, commands, and result format |

These are proposed investigations. No outcome or candidate selection is implied.

## Add an investigation

Use `NNNN-short-topic.md`, starting with `0001` for the first note. Keep the
identifier stable and add an index entry here when the note exists.

Each note should contain:

- **Question and status:** proposed, in progress, or complete.
- **Scope:** what is included and what remains outside the investigation.
- **Sources and method:** primary references, revisions, and evaluation method.
- **Findings:** observations separated from inference and assumptions.
- **Limitations:** missing evidence, failed reproduction, or unresolved questions.
- **Outcome:** recommendation and links to issues, decisions, or follow-up work.

## Investigation index

No completed investigations are recorded yet. Start by proposing a bounded
study in [Issues](https://github.com/openhpsc/community/issues).

Keep large datasets and executable experiments in a dedicated repository or
appropriate artifact location when needed. Record the version and link here.
