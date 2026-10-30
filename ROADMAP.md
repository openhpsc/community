<!-- SPDX-License-Identifier: MIT -->

# Roadmap

This roadmap defines the project's proposed sequence of work. Milestones are
completed through linked evidence, not calendar promises. Update this file when
priorities or completion criteria change.

## M0: Establish the community foundation

**Status: in progress**

- Publish the project overview and contribution workflow.
- Use Discussions for open conversation and Issues for actionable tasks.
- Identify the first research questions and welcome contributors.

**Complete when:** contributors can find the project scope, propose work, and
understand how a change is reviewed.

## M1: Define the first demonstrator

**Status: proposed**

- Select one representative workload and its expected outputs.
- Compare candidate subsystems and their public implementation artifacts.
- Investigate CPU, memory, interrupt, timer, and console requirements for RTEMS.
- Define a bounded fault model and measurable acceptance criteria.

**Complete when:** a reviewed investigation and architecture decision establish
what will be built, why it was chosen, and how it will be evaluated.

## M2: Reproduce a functional baseline

**Status: proposed**

- Pin the selected upstream sources, configuration, and tool versions.
- Run the workload in the chosen simulation environment.
- Publish commands, expected outputs, and known limitations.

**Complete when:** another contributor can reproduce the documented baseline
and obtain the expected functional result.

## M3: Evaluate one protection mechanism

**Status: proposed**

- Establish comparable baseline and protected configurations.
- Run a replayable fault-injection campaign.
- Publish outcome rules, raw counts, analysis, and implementation costs.

**Complete when:** the evidence answers the original experiment question and
states the protection boundary and remaining failure modes.

## Later directions

FPGA implementation, RTEMS integration, application processing, and physical
radiation characterization will be scoped as earlier results become available.
ASIC work requires a separate feasibility decision.

## Tracking progress

Link an issue to each active task and a result or pull request to its completion.
Use one status consistently: **proposed**, **in progress**, **blocked**, or
**complete**. Do not mark a milestone complete solely because its plan exists.
