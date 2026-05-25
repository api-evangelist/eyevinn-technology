# Eyevinn Technology (eyevinn-technology)

Eyevinn Technology is a Stockholm, Sweden based video streaming consultancy and open source company specializing in cloud-native video infrastructure, HLS and MPEG-DASH packaging, FAST channels, WebRTC ingest (WHIP/WHEP), server-side ad insertion (SSAI), broadcast intercom, and player analytics. The company operates one of the largest video-focused open source portfolios on GitHub (300+ repositories across the Eyevinn and EyevinnOSC orgs) and runs Eyevinn Open Source Cloud (OSC), a managed multi-tenant SaaS platform that packages 180+ open source projects (databases, media tools, developer tools, AI runtimes, productivity apps) into one-click deployments with a token-based consumption model, a Personal Access Token (PAT) authenticated REST API, and client SDKs for TypeScript, Go, and Terraform. Eyevinn shares OSC revenue with the maintainers of the open source projects hosted on the platform, positioning OSC as a "Builder Economy" distribution channel for open source rather than a vendor-lock-in PaaS.

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/eyevinn-technology/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Kind:** opensource
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Ad Insertion
- Broadcast Intercom
- Channel Engine
- CMAF
- DASH
- FAST Channels
- FFmpeg
- HLS
- Live Streaming
- Media Over QUIC
- Open Source
- Open Source Cloud
- OSC
- Player Analytics
- REST
- SRT
- SSAI
- Sweden
- Transcoding
- Video Infrastructure
- VOD2Live
- WebRTC
- WHEP
- WHIP

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Eyevinn Open Source Cloud REST API

Management plane for provisioning and operating service instances on the OSC platform. PAT-authenticated, mints short-lived per-service Service Access Tokens (SATs).

- **Human URL:** [https://docs.osaas.io/osaas-api-docs/docs/index.html](https://docs.osaas.io/osaas-api-docs/docs/index.html)
- **Base URL:** `https://api.osaas.io`
- **Auth:** `x-pat-jwt: Bearer <PAT>` to obtain SATs from `https://token.svc.prod.osaas.io/servicetoken`

#### Properties

- [Documentation](https://docs.osaas.io/osaas-api-docs/docs/index.html)
- [APIReference](https://docs.osaas.io/osaas-api-docs/docs/index.html)
- [GettingStarted](https://docs.osaas.io)
- [SDK (TypeScript)](https://github.com/EyevinnOSC/client-ts)
- [SDK (Go)](https://github.com/EyevinnOSC/client-go)
- [CLI](https://www.npmjs.com/package/@osaas/cli)
- [Terraform Provider](https://github.com/EyevinnOSC/terraform-provider-osc)
- [GitHub Action](https://github.com/EyevinnOSC/action)
- [MCP Server](https://github.com/EyevinnOSC/mcp-server)

### Eyevinn Channel Engine

24/7 HLS FAST channel engine using VOD2Live technology. Apache-2.0, JavaScript/TypeScript.

- [GitHub Repository](https://github.com/Eyevinn/channel-engine)

### Eyevinn WHIP and WHEP Modules

Open source TypeScript implementations of the IETF WHIP and WHEP WebRTC HTTP signaling protocols.

- [GitHub Repository](https://github.com/Eyevinn/whip)

### Eyevinn Player Analytics Specification (EPAS)

Open spec and SDK suite for collecting vendor-neutral video player analytics in real time.

- [GitHub Repository](https://github.com/Eyevinn/player-analytics-specification)
- [Web SDK](https://github.com/Eyevinn/player-analytics-client-sdk-web)

### Eyevinn Open Intercom

Browser-based WebRTC broadcast intercom — `intercom-manager` (server) + `intercom-frontend` (client).

- [Intercom Manager](https://github.com/Eyevinn/intercom-manager)
- [Intercom Frontend](https://github.com/Eyevinn/intercom-frontend)

### Eyevinn SRT to WHEP Bridge

Rust service that ingests SRT contribution feeds and re-publishes them as WHEP-playable WebRTC streams.

- [GitHub Repository](https://github.com/Eyevinn/srt-whep)

### Eyevinn Media Supply Orchestrator

TypeScript framework for orchestrating media supply chain workflows across cloud-native components, pairing with the OSC catalog.

- [GitHub Repository](https://github.com/Eyevinn/media-supply-orchestrator)

### Eyevinn Media Over QUIC (MoQ) Tools

Experimental tools tracking the IETF Media Over QUIC working group: `moqlivemock` publisher simulator and `warp-player` CMAF media player.

- [moqlivemock](https://github.com/Eyevinn/moqlivemock)
- [warp-player](https://github.com/Eyevinn/warp-player)

## Common Properties

- [Website](https://www.eyevinn.se/)
- [Product Website (OSC)](https://www.osaas.io/)
- [Documentation](https://docs.osaas.io/)
- [API Reference](https://docs.osaas.io/osaas-api-docs/docs/index.html)
- [Console (US)](https://app.osaas.io/)
- [Console (SE)](https://app.se.osaas.io/)
- [Service Catalog](https://www.osaas.io/catalog)
- [Pricing](https://www.osaas.io/pricing)
- [Status Page](https://app.osaas.io/status)
- [GitHub (Eyevinn)](https://github.com/Eyevinn)
- [GitHub (EyevinnOSC)](https://github.com/EyevinnOSC)
- [Slack](https://slack.osaas.io)
- [Community Discussions](https://github.com/EyevinnOSC/community/discussions)
- [Blog (Medium)](https://eyevinntechnology.medium.com/)
- [Developer Blog (dev.to/video)](https://dev.to/video)
- [Contact: info@eyevinn.se](mailto:info@eyevinn.se)
- [OSC Contact: osc@eyevinn.se](mailto:osc@eyevinn.se)

## Features

- Builder Economy Consultancy
- Open Source Cloud (OSC) with 180+ services
- Personal Access Token API with per-service SATs
- Polyglot Client SDKs (TypeScript, Go)
- Terraform Provider and GitHub Action
- Model Context Protocol Server for AI agents
- Revenue Sharing With Open Source Maintainers
- FAST Channel Engine (VOD2Live)
- WebRTC Contribution and Distribution (WHIP/WHEP, SRT bridge)
- Open Player Analytics Specification (EPAS)
- Media Over QUIC Tooling

## Use Cases

- Linear FAST Channel Production
- Low-Latency WebRTC Distribution
- Browser-Based Broadcast Intercom
- Managed Open Source PaaS
- AI Agent Driven DevOps
- Vendor-Neutral Player Analytics
- Media Supply Chain Orchestration

## Integrations

Terraform, GitHub Actions, Model Context Protocol, VS Code Copilot Chat, FFmpeg, Shaka Packager, Owncast, PostgreSQL, Redis / Valkey, ClickHouse, n8n, Grafana, Gitea, Nextcloud.

## Solutions

- Streaming Engineering Services
- Open Source Cloud Subscription (Basic free / Personal EUR 15/mo / Professional EUR 69/mo)
- Liivo No-Code AI App Deployment

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
