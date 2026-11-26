# Human-Agent Collaborative Engineering Playbook

A practical playbook for human-AI agent collaboration across engineering design, implementation, verification, and delivery.

Humans and AI agents work together to clarify requirements, evaluate designs, build solutions, and verify outcomes. This playbook defines how to share context, exercise guided autonomy, record decisions, and deliver results backed by evidence.

## Read the playbook

The collaboration framework is maintained in [AGENTS.md](AGENTS.md), currently written in Korean. It defines the shared working rules for Motion Server, Soft ESC, DT-demo, and future projects.

| Topic | Coverage |
| --- | --- |
| Collaboration principles | Roles, shared reasoning, guided autonomy, and execution boundaries |
| Requirements and decisions | RF requirements, TD technical debt, and ADR architecture decision records |
| Engineering workflow | Context review, implementation, verification, and handoff |
| Completion criteria | Separate evidence for implementation, automated checks, integration, and physical hardware |
| Communication | Verified facts, explicit assumptions, progress updates, and limitations |
| Cross-project coordination | Repository responsibilities, interface changes, and reproducible integration |

## Getting started

1. Read the collaboration framework in AGENTS.md.
2. Review the target project's instructions, related RF/TD/ADR records, code, and current work.
3. Define the goal, constraints, execution scope, and acceptance criteria.
4. Work in small, verifiable steps and keep related records consistent.
5. Report what changed, what was verified, and what remains unresolved.

## Applying the framework

Each project maintains its own requirements, technical debt, decisions, and verification evidence. Use existing document names, identifiers, and workflows. Record important architecture decisions in ADRs and track outstanding technical debt in TDs.

The integration repository records the component versions and settings used for verification. Simulation and integration results must be distinguished from results verified on physical hardware.

## Evolving the playbook

Improve the framework through practical engineering experience. Changes should explain the problem, the proposed working practice, and the evidence or reasoning behind it.