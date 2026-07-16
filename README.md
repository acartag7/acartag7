# Arnold Cartagena

Senior platform engineer and technical lead working on infrastructure automation, developer tooling, and AI-assisted engineering systems.

I stay close to the code. Most of my work is around Kubernetes, Kafka, cloud infrastructure, internal developer platforms, CI/CD, observability, and the tooling that helps engineers ship and operate systems with less manual work.

Lately I have been focused on AI-agent workflows: runtime controls, approval gates, MCP tools, review loops, provenance, and safer automation around real engineering work.

Based in Bern, Switzerland. Relocating to Prague, Czechia.

---

## What I Build

- **Platform automation:** Kubernetes/cloud platforms, GitOps, Terraform, CI/CD, golden paths, and self-service workflows.
- **Data and integration platforms:** Kafka, Kafka Connect, API platforms, event-driven workflows, and cloud migration patterns.
- **AI-assisted engineering systems:** agent workflows, MCP tools, runtime enforcement, review loops, and human-gated automation.
- **Research and evaluation:** practical work on tool-call safety, AI coding workflows, and failure modes in AI-assisted software delivery.

## Agent And MCP Tooling

| Project | What it does |
| --- | --- |
| [captatum](https://github.com/acartag7/captatum) | MCP web-fetch for agents: fetch any URL, render JS when needed, SSRF-guarded, with a provenance receipt on every response. Fetched content is treated as untrusted data, never instructions. |
| [mcp-sso](https://github.com/acartag7/mcp-sso) | OAuth 2.1 for remote MCP servers: spec-correct resource-server verification plus an AS bridge giving clients DCR/PKCE while your existing IdP stays the identity source. |
| [qratum](https://github.com/acartag7/qratum) | Local librarian for AI coding sessions — capture, search, redact, and review Claude and Codex work. ([qratum.dev](https://qratum.dev)) |
| [spec-reviewer](https://github.com/acartag7/spec-reviewer) | Local-first Markdown spec reviewer with source-anchored feedback for agent and human review loops. |
| [handoff-guard](https://github.com/acartag7/handoff-guard) / [handoff-guard-ts](https://github.com/acartag7/handoff-guard-ts) | Structured-output validation for LLM workflows with retry feedback. |
| [pasteforward](https://github.com/acartag7/pasteforward) | Small CLI utility that makes image paste work in Claude Code and Codex over SSH. |
| [engineering-os](https://github.com/acartag7/engineering-os) | The process and quality rules behind how I ship: specs, review gates, and verification loops. |

## Security Product Line

| Project | What it does |
| --- | --- |
| [Edictum](https://github.com/edictum-ai/edictum) | Runtime governance for AI agents: allow, block, or require approval on tool calls, and record every decision before it executes. SDKs for [Python](https://github.com/edictum-ai/edictum), [TypeScript](https://github.com/edictum-ai/edictum-ts), [Go](https://github.com/edictum-ai/edictum-go), and [OpenClaw](https://github.com/edictum-ai/edictum-openclaw). |

## Research

- [**Mind the GAP**](https://arxiv.org/abs/2602.16943) — *Text Safety Does Not Transfer to Tool-Call Safety in LLM Agents*. arXiv, Feb 2026.
- [**gap-benchmark**](https://github.com/acartag7/gap-benchmark) — Measuring text-safety vs tool-call-safety divergence across regulated domains.
- [**ai-monoculture**](https://github.com/acartag7/ai-monoculture) — Measuring architectural convergence across 6 frontier models and 144 completions.

## Best Fit

Roles where I can combine platform engineering, backend systems, developer tooling, and AI-assisted automation:

- Staff / Principal Platform Engineer
- Infrastructure Automation Engineer
- Developer Tools / Internal Developer Platform Engineer
- AI Platform / Agent Tooling Engineer
- Hands-on Technical Lead for platform or automation teams

## Links

- [cv.arnoldcartagena.com](https://cv.arnoldcartagena.com)
- [LinkedIn](https://linkedin.com/in/arnold-cartagena)
- [edictum.ai](https://edictum.ai) · [docs.edictum.ai](https://docs.edictum.ai)
