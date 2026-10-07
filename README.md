## Ryan Chappell — Emergent AI Agency

I'm the founder and lead engineer of **[Emergent AI Agency](https://emergentaiagency.com)**. We design, build and run production software for businesses: field-service platforms, e-commerce, accredited online education, clinical data capture and AI research tools. Under the hood is our own agent platform, where AI coding agents do the heavy lifting and every decision, review and release stays with an engineer.

Client code is private, so each project below has a **showcase repo**: what we built, how it's architected, the hard problems we solved, and real numbers from the private repository.

**14 projects · 8,000+ commits in 2026 · 7 systems running in production for real businesses**

---

### Client work in production

| Project | What we built | Live |
|---|---|---|
| [**Kelleher HVAC**](https://github.com/codeslayer44/kelleher-hvac-showcase) | Public website, online bill pay and staff back office for a family-owned Richmond home-services company, from Google search to paid invoice. 1,400+ commits. | [kelleherhvac.com](https://kelleherhvac.com) |
| [**Midlothian Mechanical**](https://github.com/codeslayer44/midlothian-mechanical-showcase) | Operating platform for an HVAC and plumbing contractor: twenty years of history moved off a legacy system and reconciled to the cent, plus AI-assisted quoting where code owns every price. | [midlomechanical.com](https://midlomechanical.com) |
| [**ARC Method Academy**](https://github.com/codeslayer44/arc-method-academy-showcase) | IP-protected certification academy: gated video curriculum, a tamper-resistant final exam and certificates anyone can verify. | [arcmethodacademy.com](https://arcmethodacademy.com) |
| [**Buchanan CPE**](https://github.com/codeslayer44/buchanan-cpe-showcase) | Self-study continuing education for CPAs, built to NASBA QAS standards with study time and exam rules enforced by the server. | [bescpe.com](https://bescpe.com) |
| [**Stone Sonic Audio**](https://github.com/codeslayer44/stone-sonic-showcase) | Storefront and back office for handbuilt loudspeakers: deposit-first checkout, signed purchase agreements and a nine-stage build tracker customers can follow. | [stonesonicaudio.com](https://stonesonicaudio.com) |
| [**Clinical data capture**](https://github.com/codeslayer44/clinical-data-capture-showcase) | Paper-free ABA therapy data collection for a behavioral-health provider: offline-first technician tablet, supervisor desk, append-only clinical record. | Private deployment |

### Products

| Project | What it is | Live |
|---|---|---|
| [**FleetHarbor**](https://github.com/codeslayer44/fleetharbor-showcase) | Fleet maintenance for trade contractors. AI turns a photographed invoice or a spoken note into a record a person approves. | [fleetharbor.us](https://fleetharbor.us) |
| [**Avercite**](https://github.com/codeslayer44/avercite-showcase) | Virginia tax research agent that cites the law by name, over a typed authority graph, with an evaluation set that gates every change. | [avercite.com](https://avercite.com) |
| [**Emergent website and client portal**](https://github.com/codeslayer44/emergent-site-showcase) | A homepage you walk into by scrolling, an AI assistant that drafts the project brief, and a portal where clients sign, pay and follow their projects. | [emergentaiagency.com](https://emergentaiagency.com) |

### How we build: our in-house platform

| Project | What it is |
|---|---|
| [**NextAgent**](https://github.com/codeslayer44/nextagent-showcase) | Our control plane for AI coding agents: chat, voice and fleet operations for Claude Code, Codex, Grok and Pi agents on our own machines, each in an OS-level sandbox. 3,000+ commits. |
| [**HostKit**](https://github.com/codeslayer44/hostkit-showcase) | Our hosting platform, built for agents to drive: they create, deploy, debug and operate full-stack apps through MCP tools, with zero-downtime deploys and shared `@hostkit/*` packages every client app starts from. |

Together they close the loop: an engineer briefs an agent from a laptop or phone, the agent builds the change, deploys it to HostKit, checks it came up healthy and reports back. That's how a small team ships and maintains this many production systems.

### Experiments and tools

- [**Key Broker**](https://github.com/codeslayer44/key-broker-showcase): a macOS vault that lets AI agents use an API token without ever seeing it (Swift)
- [**InTune**](https://github.com/codeslayer44/intune-showcase): iPhone prototype that helps couples say what they mean, with Claude (SwiftUI)
- [**Nexus**](https://github.com/codeslayer44/nexus-agents-showcase): shared memory, local voice and a safe operations API for a team of agents on OpenClaw (retired experiment)
- [**mlx-whisper-server**](https://github.com/codeslayer44/mlx-whisper-server): local OpenAI-compatible Whisper server for Apple Silicon (open source)

---

### What that means for your project

| If you need… | Where we've done it |
|---|---|
| An operations platform for a service business | Kelleher HVAC, Midlothian Mechanical, FleetHarbor |
| Payments, e-commerce and contracts | Stone Sonic, Kelleher bill pay, Emergent client portal |
| Courses, exams and certificates that hold up to scrutiny | Buchanan CPE, ARC Method Academy |
| Sensitive data handled carefully | Clinical data capture |
| Legacy data moved without losing a cent | Midlothian Mechanical |
| AI that's grounded, checked and accountable | Avercite, Midlothian quoting, FleetHarbor intake |
| Native Apple apps | InTune, Key Broker |

**Start a project:** [emergentaiagency.com](https://emergentaiagency.com)
