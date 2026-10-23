<p align="center">
  <a href="https://pingroom.io">
    <img src="https://pingroom.io/Pingroom-icon.png" alt="PingRoom app icon" width="112" />
  </a>
</p>

<h1 align="center">PingRoom</h1>

<p align="center">
  <strong>One tap. Everyone knows.</strong><br />
  Short-form communication for people, teams, automations, and AI agents.<br />
  Share an update or ask a question, and everyone in the room gets it at once. No new chat thread required.
</p>

<p align="center">
  <a href="https://apps.apple.com/us/app/pingroom/id6758355726">
    <img src="https://img.shields.io/badge/App%20Store-Download-E33122?style=for-the-badge&logo=apple&logoColor=white" alt="Download PingRoom on the App Store" />
  </a>
  <a href="https://play.google.com/store/apps/details?id=mindzone.pingroom.android">
    <img src="https://img.shields.io/badge/Google%20Play-Get%20the%20app-E33122?style=for-the-badge&logo=googleplay&logoColor=white" alt="Get PingRoom on Google Play" />
  </a>
  <a href="https://try.pingroom.io">
    <img src="https://img.shields.io/badge/Web-Try%20it%20in%20your%20browser-171717?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Try PingRoom in your browser" />
  </a>
  <a href="https://testflight.apple.com/join/UW186HBe">
    <img src="https://img.shields.io/badge/TestFlight-Join%20the%20beta-0D96F6?style=for-the-badge&logo=apple&logoColor=white" alt="Join the PingRoom beta on TestFlight" />
  </a>
</p>

<p align="center">
  <a href="https://pingroom.io">pingroom.io</a> ·
  <a href="https://pingroom.io/use-cases">Use cases</a> ·
  <a href="https://pingroom.io/features">Features</a> ·
  <a href="https://pingroom.io/features/live-activities">Live Activities</a> ·
  <a href="https://pingroom.io/connections">Connections</a> ·
  <a href="https://pingroom.io/agents">Agents</a> ·
  <a href="https://pingroom.io/developers">Developer docs</a>
</p>

### What a Ping can do

- **Reach the whole room in one tap.** "Dinner's ready", "I'm outside", "Deploy is live". One Ping, everyone knows.
- **Ask someone to act.** Add a confirmation request. The first person to confirm resolves it, and the room sees who's handling it.
- **Stay live until it's done.** [Live Activities](https://pingroom.io/features/live-activities) keep one changing card on the iPhone Lock Screen, the Dynamic Island, or an Android live update.
- **Fire on its own.** Trigger a Ping when someone arrives, at a set time, or from a webhook. Only the arrival is shared, never a live location.
- **Put a human in the loop.** AI agents ask questions, request approvals, and hand off decisions over MCP, the SDK, or the CLI.

### Where PingRoom fits

- **[Families](https://pingroom.io/use-cases/family-coord):** arrivals, pickups, dinner, safety, and daily routines.
- **[Couples](https://pingroom.io/use-cases/couples-private) and [friends](https://pingroom.io/use-cases/party-squad):** quiet check-ins, plans, and one-tap rescue signals.
- **[Dev teams](https://pingroom.io/use-cases/deploy-status):** deployments, incidents, standups, approvals, and on-call alerts.
- **[Automations](https://pingroom.io/connections) and [AI agents](https://pingroom.io/agents):** location and schedule triggers, webhooks, CI events, approval requests, and handoffs.

**[Explore all 74 ready-made rooms →](https://pingroom.io/use-cases)**

### Build with PingRoom

Send a Ping to your phone from any terminal, script, or CI job:

```bash
npm install --global @pingroom/cli
pingroom                                            # scan the QR code with the PingRoom app to connect
pingroom ping -m "Deploy succeeded ✅"
pingroom approval -p "Deploy to production?" --wait  # exits 0 only when approved
```

| Tool | Use it for |
|---|---|
| [**CLI and GitHub Action**](https://github.com/pingroom/cli) | Pings, questions, approvals, and live progress from shells and CI |
| [**TypeScript SDK**](https://github.com/pingroom/sdk) | Zero-dependency client for rooms, pings, approvals, real-time listen, and webhook verification |
| [**MCP and agent skills**](https://github.com/pingroom/skills) | Hosted MCP server plus ready-to-install skills for Claude Code, Grok Build, and OpenClaw |
| [**Starter templates**](https://github.com/orgs/pingroom/repositories?q=starter) | Small, runnable projects: uptime alerts, on-call routing, human review, job progress, and more |
| [**Pingminal**](https://github.com/pingroom/pingminal) | Cross-platform terminal broadcast CLI |
| [**Developer docs**](https://pingroom.io/developers) | Agent API, OAuth 2.1, webhooks, and the event and Question protocols |

---

### About me

I'm Mahdi, a cybersecurity specialist and CTO at CLRT, based in Dubai. I build PingRoom at [Mindzone Technologies](https://mindzone.tech). The rest of my time goes into security tooling, AI agent infrastructure, and taking apart how software really works.

#### Selected open source

**Security research**

| Project | What it does |
|---|---|
| [laravel-hack-auditor](https://github.com/mahdi-salmanzade/laravel-hack-auditor) | AI-powered Laravel security scanner with fix suggestions and a CTF challenge generator |
| [laravel-hack-auditor-action](https://github.com/mahdi-salmanzade/laravel-hack-auditor-action) | GitHub Action that scans Laravel PRs and comments findings inline |
| [laravel-vuln-lab](https://github.com/mahdi-salmanzade/laravel-vuln-lab) | Intentionally vulnerable Laravel 11 app for SAST testing and research |
| [meta-muse-teardown](https://github.com/mahdi-salmanzade/meta-muse-teardown) | Static teardown of Meta's Muse 3.0 macOS agent, with evidence and a reproduce script |
| [BeatsBar](https://github.com/mahdi-salmanzade/BeatsBar) | Powerbeats Pro 2 battery and heart rate in the macOS menu bar, plus a reverse-engineering of Apple's AACP protocol |

**AI agents and developer tools**

| Project | What it does |
|---|---|
| [MCP-Dubai](https://github.com/mahdi-salmanzade/MCP-Dubai) | MCP server for Dubai and UAE public data: Dubai Pulse, RTA, DLD, KHDA, DHA, and more |
| [hippo](https://github.com/mahdi-salmanzade/hippo) | A Go LLM client with a memory. Every provider, cost-aware, single binary |
| [GrokForge](https://github.com/mahdi-salmanzade/GrokForge) | A fast, careful, open-source Grok CLI for real work in the terminal |
| [Crosstalk](https://github.com/mahdi-salmanzade/Crosstalk) | Four terminal coding agents on one problem, with one of them managing the others |
| [expo58-skill](https://github.com/mahdi-salmanzade/expo58-skill) | Expo SDK 58 agent skill with verified package references and SDK migration |
| [iphone-duo-skill](https://github.com/mahdi-salmanzade/iphone-duo-skill) | Agent skill to adapt and verify existing apps for iPhone Duo |

**Mobile and hardware**

| Project | What it does |
|---|---|
| [odysseus-mobile](https://github.com/mahdi-salmanzade/odysseus-mobile) | Native mobile remote for the Odysseus self-hosted AI workspace |
| [expo-telegram-login](https://github.com/mahdi-salmanzade/expo-telegram-login) | Expo native module for Sign in with Telegram on iOS and Android |
| [glyph-cli](https://github.com/mahdi-salmanzade/glyph-cli) | Drive the Nothing Phone (4a) Pro's 137 Glyph LEDs from your terminal |
| [keyglow](https://github.com/mahdi-salmanzade/keyglow) | Browser-based lighting editor for the Wooting 80HE over WebHID |

<p align="center">
  <a href="https://x.com/mahdisphp">X @mahdisphp</a> ·
  <a href="https://mindzone.tech">mindzone.tech</a> ·
  <a href="https://x.com/PingRoomIO">PingRoom on X</a>
</p>
