<div align="center">

# SwiftScale AI

### Local-first AI agents and developer infrastructure

We build dependable, inspectable tools that keep developers close to their code, data, and machines.

[![Website](https://img.shields.io/badge/Website-swift--scale.com-0969da?style=for-the-badge)](https://swift-scale.com)
[![Documentation](https://img.shields.io/badge/Docs-swift--scale.com%2Fdocs-0b7285?style=for-the-badge)](https://swift-scale.com/docs/)
[![SwiftCoder](https://img.shields.io/badge/SwiftCoder-open_source-111827?style=for-the-badge&logo=github)](https://github.com/swift-scale-ai/swiftcoder)

</div>

## Open-source projects

| Project | What it does | Start here |
| --- | --- | --- |
| **[SwiftCoder](https://github.com/swift-scale-ai/swiftcoder)** | A local-first AI coding agent that can understand a repository, plan work, edit files, run commands, review changes, and verify results. | [Repository](https://github.com/swift-scale-ai/swiftcoder) · [Releases](https://github.com/swift-scale-ai/swiftcoder/releases/latest) |
| **[SwiftCore](https://github.com/swift-scale-ai/swiftcore)** | The shared agent runtime behind SwiftCoder and other SwiftScale applications: sessions, tools, permissions, models, protocols, persistence, plugins, and reusable UI. | [Explore the code](https://github.com/swift-scale-ai/swiftcore) |

## SwiftScale platform

SwiftScale provides the identity, model routing, capacity, usage controls, and OpenAI-compatible APIs that power our agent products.

- **[SwiftCoder](https://swiftcoder.io)** — a focused desktop and terminal coding agent.
- **[Developer documentation](https://swift-scale.com/docs/)** — API access, authentication, model routing, and Coding Plan guides.
- **[SwiftScale](https://swift-scale.com)** — product information, plans, and platform updates.

## Native developer utilities

Our SwiftScale Labs projects explore focused, visual replacements for classic command-line tools on Apple Silicon Macs.

| Project | What it does | Download |
| --- | --- | --- |
| **[ReTop](https://github.com/swiftscalecloud/ReTop)** | A colorful process and system monitor with per-core CPU, memory, swap, and per-interface network views. | [Latest release](https://github.com/swiftscalecloud/ReTop/releases/latest) |
| **[ReMTR](https://github.com/swiftscalecloud/ReMTR)** | A graphical network-path monitor with loss, latency, jitter, route changes, and RTT history. | [Latest release](https://github.com/swiftscalecloud/ReMTR/releases/latest) |
| **[ReDu](https://github.com/swiftscalecloud/ReDu)** | A read-only visual disk-usage analyzer with tree navigation, allocated sizes, and file-type insights. | [Latest release](https://github.com/swiftscalecloud/ReDu/releases/latest) |
| **[ReGet](https://github.com/swiftscalecloud/ReGet)** | A visual download manager with progress, speed history, resumable transfers, and controlled cancellation. | [Latest release](https://github.com/swiftscalecloud/ReGet/releases/latest) |

## Principles

- **Local first** — workspace access, tools, and session state remain on the user's machine by default.
- **Inspectable agents** — plans, tool calls, file changes, commands, and validation results stay visible.
- **Controlled execution** — sensitive operations cross explicit permission and policy boundaries.
- **Provider flexibility** — applications depend on stable model contracts rather than a single provider.
- **Verifiable delivery** — useful work ends with reviewable artifacts and concrete checks.
- **Open development** — public code, issues, pull requests, and reproducible releases build trust.

## Technology

```text
Agent applications    TypeScript · Rust · Electron · SolidJS · Effect
Agent platform        Sessions · tools · permissions · MCP · plugins · durable events
AI infrastructure     OpenAI-compatible APIs · model routing · usage controls
Native utilities      Rust · Ratatui · Darwin APIs · Apple Silicon
Release trust         GitHub Actions · Developer ID · Apple notarization · SHA-256
```

## Get started

```bash
# Install the SwiftCoder CLI on macOS or Linux
curl -fsSL https://swiftscale.app/swiftcoder/install.sh | sh

# Then authenticate and start a repository task
swiftcoder login
swiftcoder
```

Visit the [SwiftCoder repository](https://github.com/swift-scale-ai/swiftcoder) for desktop builds, additional installation methods, source code, and contribution guidance.

<div align="center">

**Build locally. Inspect every step. Ship with confidence.**

</div>
