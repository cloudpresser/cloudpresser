# Hi, I'm Luiz Ozorio

Building control-system primitives for supervised AI execution. Software development is the first proving ground — the architecture generalizes to any domain where humans supervise agents in high-consequence workflows.

## What I Do

- **Platform Engineering** — Cross-platform build systems, CI/CD automation, release engineering, and developer productivity tooling serving 5+ platforms from a single codebase
- **AI Execution Infrastructure** — Agent orchestration pipelines, RAG systems, MCP servers, execution tracing (OpenTelemetry), reconciliation layers, and human-in-the-loop supervision interfaces
- **Engineering Leadership** — Defined architecture, standards, and mentoring practices for a 25-engineer organization; drove ~300% release cadence improvement through platform infrastructure and engineering culture
- **Open Source** — React Native core contributor, ArduPilot autonomous systems contributor, OpenCode ecosystem, and control-surface reliability artifacts

## The Stack

These repos are not independent tools. They are layers of a single control-system architecture.

| Layer | Repo | Role |
|-------|------|------|
| **Control Surface** | [control-surface-agent](https://github.com/cloudpresser/control-surface-agent) | Thesis artifact for production reliability: explicit intent, plan, telemetry, reconciliation, operator intervention, and decision artifact in one supervised run. |
| **Supervision** | [react-native-opencode-client](https://github.com/cloudpresser/react-native-opencode-client) | Operator surface for software agents — observe, intervene, approve execution in real time. 37+ PRs in 2 weeks. |
| **Observability** | *emerging* | End-to-end execution tracing, replay, and longitudinal system introspection (OpenTelemetry) |
| **Verification** | [opencode-devtools](https://github.com/cloudpresser/opencode-devtools) | Control-loop gates — type checks, tests, build status as execution constraints |
| **Execution** | [OpenCode](https://github.com/anomalyco/opencode) | Agent runtime (contributor — RLM REPL sandbox fix, Learn plugin) |
| **Learned Policy** | [opencode-learn](https://github.com/cloudpresser/opencode-learn) | Feedback-driven adaptive controller — agents learn adaptive control hints, not ground truth |
| **Epistemic Safety** | [agent-memory-failure-demo](https://github.com/cloudpresser/agent-memory-failure-demo) | Controlled experiment proving lossy memory degrades agent correctness |
| **Thesis** | [Control Systems for Intelligent Software](https://cloudpresser.com/control-systems-for-ai) | Architecture essay series — execution, verification, observability, control surfaces, supervision |

## How I Think About Systems

```
Human Intent ──> Orchestration ──> Agent Execution ──> Verification ──> Human Supervision
                      │                    │                  │
                 task routing         tool calling        trace trees
                 context mgmt        parallel exec       replayable
                 priority queue      checkpoints         sessions
```

The same architecture that governs robotics and industrial automation (I'm an [ArduPilot/MAVLink](https://github.com/ArduPilot/ardupilot) contributor) applies to AI agent systems: machine telemetry, reconciliation, operator interfaces, and human-in-the-loop control.

Verification is bounded. Execution is open-ended. Reliability emerges through supervision, telemetry, and correction across repeated runs.

### This Architecture Is Domain-General

Software development is the current implementation context — it's observable, replayable, rich in intermediate artifacts, and a strong sandbox for control-loop design. But the primitives generalize:

| Domain | Agent executes... | Human supervises... |
|--------|-------------------|---------------------|
| Software | code edits, test runs | merge decisions, architecture |
| Research | evidence gathering, synthesis | source evaluation, conclusions |
| Operations | workflow execution | exception handling, escalation |
| Analytics | data traversal, pattern detection | decision validation |

The architecture is always: **intent → orchestration → execution → verification → supervision.**

Safety in staging is a checkpoint. Reliability in production is a continuous control problem.

The anchoring constraint across every domain: **never destroy raw evidence. Summarize for navigation, not for storage.**

## Tech

| | |
|---|---|
| **Platform Engineering** | CI/CD automation, release engineering, cross-platform build systems, deployment infrastructure, OTA updates, developer productivity tooling |
| **AI Infrastructure** | Agent orchestration, RAG pipelines, MCP servers, execution tracing (OpenTelemetry), LLM applications, prompt engineering |
| **Systems & Cloud** | AWS serverless, microservices, DDD, multi-tenant SaaS, Docker, Kubernetes, infrastructure as code |
| **Languages & Runtime** | TypeScript, Python, C#/.NET, Node.js, React/React Native, GraphQL |

## Open Source Contributions

- [**React Native**](https://github.com/facebook/react-native) — Contributor to the core framework
- [**ArduPilot**](https://github.com/ArduPilot/ardupilot) — Contributor to autonomous vehicle/drone firmware and documentation
- [**OpenCode**](https://github.com/anomalyco/opencode) — Submitted fix for critical RLM REPL sandbox crash (experimental PR), built mobile supervision client, created knowledge persistence plugin

## Writing

Series: **Control Systems for Intelligent Software** — mapping robotics and industrial automation architecture onto AI agent systems.

- [**Bash Is All You Need — Until It Isn't**](https://cloudpresser.com/writing/bash-is-all-you-need) — Execution is solved. Context curation, orchestration, verification, and supervision are the real problems.
- [**Why the Smart Model Reviewer Pattern Is Backwards**](https://cloudpresser.com/writing/smart-model-reviewer-is-backwards) — Strong models should generate. Cheap models should verify. The industry has it backwards.
- [**AI Agents Are Control Systems**](https://cloudpresser.com/writing/ai-agents-are-control-systems) — The ArduPilot/MAVLink architecture is a proven blueprint for AI agent supervision.
- [**Observability for AI Agents**](https://cloudpresser.com/writing/observability-for-ai-agents) — Traces and replay are how you tell whether a system remains reliable as it accumulates runs, interventions, and drift.
- [**Why AI Needs Control Surfaces, Not Just Chat**](https://cloudpresser.com/writing/why-ai-needs-control-surfaces) — Chat is fine for intent. Reliability needs control surfaces that make system behavior legible enough to supervise across runs.

## Thesis Artifacts

- [**control-surface-agent**](https://github.com/cloudpresser/control-surface-agent) — Production reliability infrastructure for agentic systems. A bounded decision workflow with explicit intent, explicit planning, telemetry, reconciliation, operator intervention, and a decision artifact.
- [**agent-memory-failure-demo**](https://github.com/cloudpresser/agent-memory-failure-demo) — Controlled experiment showing how lossy memory degrades agent correctness.

## Connect

- [LinkedIn](https://www.linkedin.com/in/luiz-ozorio/)
- [npm](https://www.npmjs.com/~cloudpresser)
- [Blog](https://cloudpresser.com)
