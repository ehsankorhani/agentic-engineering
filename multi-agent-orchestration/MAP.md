# Course map

Control layers, not beginner → expert. Production default is Track 2.

Do not edit `harness/`, `agent/`, or `code/` — prior drafts, left as-is.

## Spine

`00-spine.md` — same ideas, three vehicles.

```
goal → decompose → spawn (isolated context)
                  → contract (schema / HANDOFF / Result)
                  → barrier → merge → verify
```

| Track | Student writes | Who runs spawn/wait/merge | Job |
|---|---|---|---|
| [01 Prompt](01-prompt/) | chat | harness | watch the loop happen |
| [02 Role files](02-role-files/) | `agent.md` + protocol | harness | make a repeatable team |
| [03 Code](03-code/) | loop, spawn, contracts | you | become the harness |

Exam: [03 L09](03-code/L09-capstone-port-the-team.md) — port the Track 2 landing-page team into code. Same roles, same protocol, new runtime.

## Hard cuts

- **Track 1** — ephemeral prompts + bundled agents only (`scout`, `task`, `reviewer`, …). No `.omp/agents/*.md`.
- **Track 2** — durable roles, orchestrator file, handoff protocol. Slash command = invocation, not role definition.
- **Track 3** — implement the primitives. Not a framework zoo.
- **Appendix** — map one framework onto the spine. Not a fourth track.
- **Coda** — eval, cost, traces, when *not* to multi-agent. After Track 2 (most students stop) and again after Track 3. Not a track.

## 01 Prompt

Bundled agents. Student observes.

- [L00 Hello, agent](01-prompt/L00-hello-agent.md)
- [L01 Pipeline](01-prompt/L01-pipeline.md)
- [L02 Router](01-prompt/L02-router.md)
- [L03 Fan-out](01-prompt/L03-fan-out.md)
- [L04 Tools as roles](01-prompt/L04-tools-as-roles.md)
- [L05 Contracts](01-prompt/L05-contracts.md)
- [L06 Model routing](01-prompt/L06-model-routing.md)
- [L07 Hub-and-spoke](01-prompt/L07-hub-and-spoke.md)

## 02 Role files

Repeatable team. Student configures.

- [L00 Orientation](02-role-files/L00-orientation.md)
- [L01 Anatomy of agent.md](02-role-files/L01-agent-md-anatomy.md)
- [L02 Design a role](02-role-files/L02-design-a-role.md)
- [L03 Handoff protocol](02-role-files/L03-handoff-protocol.md)
- [L04 Model assignment](02-role-files/L04-model-assignment.md)
- [L05 Full orchestration](02-role-files/L05-full-orchestration.md)
- [L06 Slash command as invocation](02-role-files/L06-slash-command-invocation.md)
- [L07 Diagnosing failures](02-role-files/L07-diagnosing-failures.md)
- [L08 Extend the team](02-role-files/L08-extend-the-team.md)
- [L09 Capstone: a team of your own](02-role-files/L09-capstone-own-team.md)
- [Coda](02-role-files/coda-ops.md)

## 03 Code

You are the harness. Student implements.

- [L00 Agent runtime](03-code/L00-agent-runtime.md)
- [L01 Contracts](03-code/L01-contracts.md)
- [L02 Spawn & collect](03-code/L02-spawn-collect.md)
- [L03 Decompose & merge](03-code/L03-decompose-merge.md)
- [L04 Message bus](03-code/L04-message-bus.md)
- [L05 Artifact store](03-code/L05-artifact-store.md)
- [L06 DAG pipelines](03-code/L06-dag-pipelines.md)
- [L07 Guardrails](03-code/L07-guardrails.md)
- [L08 Observability](03-code/L08-observability.md)
- [L09 Capstone: port the Track 2 team](03-code/L09-capstone-port-the-team.md)
- [Coda](03-code/coda-ops.md)

## Appendix — frameworks

Mapping, not a track. Primitives first; one framework onto the spine.

- [Appendix map](appendix-frameworks/MAP.md)
- [LangGraph](appendix-frameworks/langgraph.md)
- [Strands](appendix-frameworks/strands.md)
- [CrewAI](appendix-frameworks/crewai.md)
