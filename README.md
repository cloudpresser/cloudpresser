# Hi, I'm Luiz Ozorio

Engineering leader building control systems for intelligent software — orchestration pipelines where humans supervise AI agents executing complex tasks.

## What I Do

- **Platform Engineering** — Cross-platform build systems, CI/CD automation, release engineering, and developer productivity tooling serving 5+ platforms from a single codebase
- **AI Execution Infrastructure** — Agent orchestration pipelines, RAG systems, MCP servers, execution tracing (OpenTelemetry), human-in-the-loop supervision interfaces
- **Engineering Leadership** — Defined architecture, standards, and mentoring practices for a 25-engineer organization; drove ~300% release cadence improvement through platform infrastructure and engineering culture
- **Open Source** — React Native core contributor, ArduPilot autonomous systems contributor, OpenCode ecosystem (mobile client, RLM REPL fix [experimental PR], Learn plugin)

## Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**React Native OpenCode Client**](https://github.com/cloudpresser/react-native-opencode-client) | Mobile supervision interface for AI coding agent platform — real-time streaming, terminal emulation, git viewer, interactive agent control. 37+ PRs in 2 weeks. | React Native, TypeScript |
| [**OpenCode Learn**](https://github.com/cloudpresser/opencode-learn) | Plugin enabling AI agents to capture and persist knowledge as reusable skill files | TypeScript |
| [**LLM Tools**](https://github.com/cloudpresser/llm-tools) | AI-powered CLI that generates PR descriptions from git diffs, reducing code review time ~80% | TypeScript, OpenAI, Azure DevOps |
| [**Wildlife Detection API**](https://github.com/cloudpresser/wildlifeApp) | REST API for automated species identification using Microsoft MegaDetector v5a (YOLOv5/PyTorch) | Python, Flask, PyTorch |

## How I Think About Systems

```
Human Intent ──> Orchestration ──> Agent Execution ──> Verification ──> Human Supervision
                      │                    │                  │
                 task routing         tool calling        trace trees
                 context mgmt        parallel exec       replayable
                 priority queue      checkpoints         sessions
```

The same architecture that governs robotics and industrial automation (I'm an [ArduPilot/MAVLink](https://github.com/ArduPilot/ardupilot) contributor) applies to AI agent systems: machine telemetry, operator interfaces, and human-in-the-loop control.

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

I write about AI agent architecture, control systems, and the engineering problems behind reliable AI-assisted development.

- [**Bash Is All You Need — Until It Isn't**](https://cloudpresser.com/writing/bash-is-all-you-need) — Why execution is a solved problem, but context curation, task orchestration, verification, and human supervision are the real engineering challenges. Part 1 of "Control Systems for Intelligent Software."

## Connect

- [LinkedIn](https://www.linkedin.com/in/luiz-ozorio/)
- [npm](https://www.npmjs.com/~cloudpresser)
- [Blog](https://cloudpresser.com)
