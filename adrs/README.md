<!-- SPDX-License-Identifier: MIT -->

# Architecture decisions

Architecture Decision Records (ADRs) preserve significant choices and the
reasoning behind them. They explain what was selected, which alternatives were
considered, and what evidence informed the decision.

## When to write an ADR

Record decisions that affect subsystem selection, hardware/software interfaces,
fault protection, recovery, or the verification approach. Routine editorial
changes do not need an ADR.

Discuss the proposal first. Use an issue or pull request for feedback, then mark
the ADR accepted only when maintainers have explicitly accepted the decision.

## Record format

Use `NNNN-short-title.md`. Start at `0001` and keep identifiers stable.

```markdown
# ADR-0001: <decision title>

Status: proposed
Date: YYYY-MM-DD
Related: <issue, research note, or pull request>

## Context
Problem, requirements, and constraints.

## Alternatives
Options and the evidence available for each.

## Decision
Chosen approach and rationale. Identify unresolved points if still proposed.

## Consequences
Integration costs, limitations, risks, and required verification.

## References
Sources, revisions, research notes, and review links.
```

Use **proposed**, **accepted**, **rejected**, or **superseded** consistently in both
the record and its index. If a decision is superseded, link the replacement;
preserve the earlier record as history.

## Decision index

No architecture decisions have been accepted yet. Add the first index entry when
an actual decision record is proposed.
