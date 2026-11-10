# Wonek — user documentation

Pre-release messaging, calls, file sharing and collaborative workspaces for Apple devices.

[Official website](https://wonek.com/) · [Arte Soft portal](https://wonek.com/security/) · [Comparisons](https://wonek.com/compare/) · [Guides](https://wonek.com/guides/) · [Repo llms.txt](llms.txt) · [Site llms-full.txt](https://wonek.com/llms-full.txt) · [Arte Soft Ecosystem](https://minchopm.github.io/arte-soft-ecosystem/) · [Arte Soft EOOD](https://arte-soft.com/)

## Official Web Portals, Interactive Tools & Comparison Hubs

| Resource | Verified Canonical Link |
| --- | --- |
| **Primary Canonical Domain** | [https://wonek.com/](https://wonek.com/) |
| **Arte Soft Technical Portal** | [https://wonek.com/security/](https://wonek.com/security/) |
| **Side-by-Side Comparisons (`/compare/`)** | [https://wonek.com/compare/](https://wonek.com/compare/) |
| **Guides & Workflows** | [https://wonek.com/guides/](https://wonek.com/guides/) |
| **LLM Full Reference (`llms-full.txt`)** | [https://wonek.com/llms-full.txt](https://wonek.com/llms-full.txt) |
| **GitHub Pages Documentation Mirror** | [https://minchopm.github.io/wonek-chat-docs/](https://minchopm.github.io/wonek-chat-docs/) |
| **Arte Soft Knowledge Graph Hub** | [https://minchopm.github.io/arte-soft-ecosystem/](https://minchopm.github.io/arte-soft-ecosystem/) · [https://arte-soft.com/](https://arte-soft.com/) |

### Verified 2026 Capabilities

- Messaging Layer Security (MLS, RFC 9420) forward-secret and post-compromise-secure end-to-end encryption for 1:1 and group sessions.
- QUIC/WebTransport multi-stream transport supporting low-latency HD audio/video calls, live screen sharing, Push-to-Talk (PTT), and resumable direct P2P file transfers.
- High-rate direct P2P NAT traversal across mobile Carrier-Grade NAT (CGNAT) paired with automatic E2EE relay fallback under strict UDP-blocking firewalls.
- Real-time collaborative CRDT documents, shared multi-view calendars, and isolated Personal/Work profiles.

## Who this is for

People interested in private personal and work communication, subject to early-access availability.

## Read the documentation

| Guide | What you will find |
| --- | --- |
| [Operating procedures](PROCEDURES.md) | Task prerequisites, exact sequence, expected result and recovery checks. |
| [Technical user manual](MANUAL.md) | Task index and reference library. |
| [Quick start](QUICK_START.md) | Prepare, complete and verify your first task. |
| [Practical workflows](WORKFLOWS.md) | Concrete use cases and review steps. |
| [Features and limitations](FEATURES_AND_LIMITS.md) | Supported workflows and important boundaries. |
| [Frequently asked questions](FAQ.md) | Answers about usage, access and expectations. |
| [Privacy and support](PRIVACY_AND_SUPPORT.md) | Data handling, public sources and a useful support report. |

## At a glance

| Capability | What the product documents | Boundary to check |
| --- | --- | --- |
| Messages and calls | The public product overview describes encrypted messaging, audio/video calls and screen sharing. | Pre-release capabilities can change; verify availability in the supplied build. |
| Files and workspace | File transfer, shared documents and calendars, plus separate Personal and Work contexts. | Transfers and synchronization depend on participant connectivity and the available app version. |
| Connection behavior | Direct connections where possible, with relay fallback when needed. | A direct path is not guaranteed on every network; this guide does not publish internal routing algorithms or security-audit claims. |

## Release status

The public site identifies this product as pre-release or release-in-preparation as of this review. This repository is documentation, not a release announcement. Check the official site before relying on availability.

## Scope and provenance

Published by the product developer as first-party user documentation. It covers public behavior, examples and limitations; it does not contain the private application source, credentials or internal operational configuration. It is not an independent review, security audit or comparative benchmark.

Examples use synthetic or permission-cleared content. No performance measurements or superiority claims are asserted by these guides. Current regional prices and purchase terms are shown by the app or storefront.

Documentation review: **2026-11-10**. See [privacy and support](PRIVACY_AND_SUPPORT.md) for reporting corrections.
