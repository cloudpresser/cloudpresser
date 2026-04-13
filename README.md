# Hi, I'm Luiz Ozorio

Building control-system primitives for supervised AI execution. Software development is the first proving ground — the architecture generalizes to any domain where humans supervise agents in high-consequence workflows.

## What I Do

- **Platform Engineering** — Cross-platform build systems, CI/CD automation, release engineering, and developer productivity tooling serving 5+ platforms from a single codebase
- **AI Execution Infrastructure** — Agent orchestration pipelines, RAG systems, MCP servers, execution tracing (OpenTelemetry), human-in-the-loop supervision interfaces
- **Engineering Leadership** — Defined architecture, standards, and mentoring practices for a 25-engineer organization; drove ~300% release cadence improvement through platform infrastructure and engineering culture
- **Open Source** — React Native core contributor, ArduPilot autonomous systems contributor, OpenCode ecosystem (mobile client, RLM REPL fix [experimental PR], Learn plugin)

## The Stack

These repos are not independent tools. They are layers of a single control-system architecture.

| Layer | Repo | Role |
|-------|------|------|
| **Supervision** | [react-native-opencode-client](https://github.com/cloudpresser/react-native-opencode-client) | Operator surface — observe, intervene, approve agent execution in real time. 37+ PRs in 2 weeks. |
| **Observability** | *planned* | End-to-end execution tracing, replay, and system introspection (OpenTelemetry) |
| **Verification** | [opencode-devtools](https://github.com/cloudpresser/opencode-devtools) | Control-loop gates — type checks, tests, build status as execution constraints |
| **Execution** | [OpenCode](https://github.com/anomalyco/opencode) | Agent runtime (contributor — RLM REPL sandbox fix, Learn plugin) |
| **Learned Policy** | [opencode-learn](https://github.com/cloudpresser/opencode-learn) | Feedback-driven adaptive controller — agents learn adaptive control hints, not ground truth |
| **Epistemic Safety** | [agent-memory-failure-demo](https://github.com/cloudpresser/agent-memory-failure-demo) | Controlled experiment proving lossy memory degrades agent correctness |
| **Thesis** | [cloudpresser.com](https://cloudpresser.com) | Architecture essays: "Control Systems for Intelligent Software" series |

## How I Think About Systems

```
Human Intent ──> Orchestration ──> Agent Execution ──> Verification ──> Human Supervision
                      │                    │                  │
                 task routing         tool calling        trace trees
                 context mgmt        parallel exec       replayable
                 priority queue      checkpoints         sessions
```

The same architecture that governs robotics and industrial automation (I'm an [ArduPilot/MAVLink](https://github.com/ArduPilot/ardupilot) contributor) applies to AI agent systems: machine telemetry, operator interfaces, and human-in-the-loop control.

Verification is bounded. Execution is open-ended. Supervision is where reliability emerges.

### This Architecture Is Domain-General

Software development is the current implementation context — it's observable, replayable, rich in intermediate artifacts, and a strong sandbox for control-loop design. But the primitives generalize:

| Domain | Agent executes... | Human supervises... |
|--------|-------------------|---------------------|
| Software | code edits, test runs | merge decisions, architecture |
| Research | evidence gathering, synthesis | source evaluation, conclusions |
| Operations | workflow execution | exception handling, escalation |
| Analytics | data traversal, pattern detection | decision validation |

The architecture is always: **intent → orchestration → execution → verification → supervision.**

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
- [**AI Agents Are Control Systems**](https://cloudpresser.com/writing/ai-agents-are-control-systems) — The ArduPilot/MAVLink architecture is a proven blueprint for AI agent supervision.

## Connect

- [LinkedIn](https://www.linkedin.com/in/luiz-ozorio/)
- [npm](https://www.npmjs.com/~cloudpresser)
- [Blog](https://cloudpresser.com)
