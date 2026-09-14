# Hugo Valer

**Software architect · Governed agentic AI for on-premise and regulated environments**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hugo%20Valer-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hugovaler/)
[![Ovillo docs](https://img.shields.io/badge/Ovillo-documentation-2E7D32?style=flat-square&logo=readthedocs&logoColor=white)](https://hvaler.github.io/ovillo-docs/)

---

## What I do

I design and maintain AI-assisted development platforms for organisations where the source code cannot leave the building.

At Universidad Pontificia Comillas I am the principal architect of the development AI ecosystem: agents running on-premise on top of Azure DevOps Server, under a strict governance model. Advisors are read-only, commands are the single write path, and every decision is sealed as an ADR with a content hash. This is not developer assistance — it is a platform with invariants.

- **Agent governance.** Command / skill / agent triad, content-hash stamping, ADR-backed decisions.
- **On-premise by constraint.** Azure DevOps Server 2020, no code leaves the perimeter.
- **MCP.** Hub servers centralising architectural records and quality evidence.
- **Measured quality.** Gates that fail builds, not dashboards that decorate them.

---

## Proof, not adjectives

Last quality remediation campaign on the platform's codebase:

| Metric | Before | After |
|---|---|---|
| CRAPmax | 272 | 26 |
| Line coverage | 61.4% | 87.9% |
| Branch coverage | 65.8% | 91.7% |
| Quality gate | FAIL | PASS |

---

## Ovillo

[**Ovillo**](https://hvaler.github.io/ovillo-docs/) is my own Claude Code ecosystem for .NET, distributed as the `hv@ovillo` plugin. It brings the governance model above to any .NET codebase: read-only advisors, commands as the only write path, and a documented decision trail.

Documentation portal: **hvaler.github.io/ovillo-docs**

---

## Selected work

| Project | What it is |
|---|---|
| [**ovillo-docs**](https://github.com/hvaler/ovillo-docs) | Documentation portal for Ovillo, generated from source on every release. |
| [**stripboard-dev**](https://github.com/hvaler/stripboard-dev) | Autonomous line producer for film shoots. The LLM formulates, CP-SAT decides, a human approves. Gemini + Grafana MCP. |
| [**atelier**](https://github.com/hvaler/atelier) | Descriptive-geometry verifier. OpenCV measures the drawing, the model teaches and may not invent a number. Python, Vertex AI. |
| [**cursus**](https://github.com/hvaler/cursus) | Course planner whose tools can refuse, explain what a choice forecloses two years ahead, and be rewound. Built with WebMCP. |

Built during OpenAI Build Week, Agentic Cinema and All Things Agentic (2026).

---

## Stack

**Languages** C# · Python · Rust
**Frameworks** .NET · ASP.NET Core · Blazor
**Data** SQL Server · PostgreSQL
**Platform** Azure · Docker · Azure DevOps Server
**AI** Claude Code · MCP · agent orchestration and governance

Thirty years building software; the last few spent getting agentic AI to work in production rather than in demos.

---

## Contact

Madrid, Spain. Open to conversations about .NET architecture, MCP, and AI adoption in organisations with data-residency constraints.

[LinkedIn](https://www.linkedin.com/in/hugovaler/) · [Ovillo](https://hvaler.github.io/ovillo-docs/)
