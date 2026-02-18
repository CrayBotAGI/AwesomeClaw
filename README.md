# AwesomeClaw 

![320203e11d1eeda8ec8244dbdf337b1a](https://github.com/user-attachments/assets/3fd69e5c-293d-426f-9b4c-1abe53315572)


> Curated list of OpenClaw-like AI assistant projects | 精选的类 OpenClaw AI 助手项目清单

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Fun](https://img.shields.io/badge/Status-Fun%20%26%20Awesome-orange.svg)](https://github.com/)

[OpenClaw](https://github.com/openclaw/openclaw) — Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞

This document collects open-source alternatives and commercial products similar to it. Whether you're a **lobster whisperer**, a **performance chaser**, a **minimalist monk**, or an **edge computing wizard** — there's something here for you!

---

## 🦞 Why This List Exists

OpenClaw is powerful but massive: **430,000+ lines of TypeScript**. Not everyone needs that much muscle power. Here's the spectrum we cover:

```
┌─────────────────────────────────────────────────────────────────────┐
│                    THE AWESOME OPENCLAW SPECTRUM                     │
├─────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  HEAVY ──────► MEDIUM ──────► LIGHT ──────► MICRO ──────► EDGE CHIP │
│                                                                      │
│  [🦞 430K  ] [🦀 40K    ] [⚡ 4K     ] [💻 2K     ] [🔌 5$     ] │
│   OpenClaw                nanoClaw    bashobot    zeroclaw
                                        myclaw       picoclaw        │
│               moltis      nanobot                  mimiclaw        │
│                                                                      │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 📚 Table of Contents

- [Why This List Exists](#️-why-this-list-exists)
- [Original Document Overview](#-original-document-overview)
- [Open Source Projects](#-open-source-projects)
  - [🦞 Core Projects](#️-core-projects)
  - [⚡ Lightweight Alternatives](#-lightweight-alternatives)
  - [🏢 Enterprise Platforms](#️-enterprise-platforms)
  - [🧩 Ecosystem Tools](️-ecosystem-tools)
- [Commercial Products](#-commercial-products)
- [Architecture Comparison](#️-architecture-comparison)
- [Selection Guide](#-selection-guide)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🦞 Claw Projects

### 🦞 Core Projects

#### [OpenClaw](https://github.com/openclaw/openclaw)   
Recommand:⭐⭐⭐⭐⭐   
All lobster criminal activities originate from here

> The origin of all lobster universes. 🦞

```yaml
Language: TypeScript
Code: 430,000+ lines
Stars: ⭐ [Check GitHub]
```

**Key Features:**
- Feature-rich personal AI assistant
- Multi-channel: WhatsApp, Telegram, Discord, Slack, Feishu
- Complete skill system & plugin ecosystem
- Persistent memory & context management
- Battle-tested at massive scale

**Links:**
- 🌐 [openclaw.ai](https://openclaw.ai)
- 📖 [docs.openclaw.ai](https://docs.openclaw.ai)

---

### ⚡ Lightweight Alternatives


#### [nanobot](https://github.com/HKUDS/nanobot)   
Recommand:⭐⭐⭐⭐⭐   
If you want to deeply understand the openclaw system, this project is absolutely excellent! Everything is in there!

> Ultra-lightweight personal AI assistant | 超轻量级个人 AI 助理

```yaml
Dev: HKUDS (香港大学)
Language: Python
Code: ~3,428 LOC (99.2% leaner than OpenClaw)
```

**Why It's Awesome:**
- ⚡ Core OpenClaw features in ~4K lines
- 🧠 Persistent memory, web search, scheduled tasks
- 🔌 Multi-LLM provider support
- 💬 Telegram/WhatsApp/Feishu integration
- ⏱️ Deploy in 2 minutes (seriously)

**Best For:** Researchers, students, anyone who wants **maximum impact with minimum code**

---

---

#### [ZeroClaw](https://github.com/brooks376/zeroclaw.bot)  
Recommand:⭐⭐⭐⭐   
A rather outstanding openclaw Rust rewrite version!

> High‑performance, open‑source AI agent framework built in Rust.

```yaml
Language: Rust
Binary Size: ~3.4MB
Startup: ⚡ Blink-and-you-miss-it fast
```

**Why It's Awesome:**
- 🚀 Blazing fast startup
- 💪 Low memory footprint
- 🔗 OpenRouter: 22+ models, one API
- 🔌 Pluggable architecture
- 🛡️ Strong security controls

**Best For:** Resource-constrained environments, edge computing, performance zealots

---

#### [picoclaw](https://github.com/sipeed/picoclaw)   
Recommand:⭐⭐⭐⭐   
An extremely lightweight openclaw in Go reset version from renowned embedded manufacturer spieed

> Run OpenClaw on $5 chip. No OS. No Node.js. No Mac mini.

```yaml
Dev: Sipeed
Hardware: $5 MCU
OS: None. Bare metal baby! 🔥
```

**Why It's Awesome:**
- 💰 $5 hardware — cheaper than coffee
- 🎯 No OS needed — runs everywhere
- 📦 Portable, shareable
- 🔒 Privacy-first, local memory

**Best For:** Hackers, IoT enthusiasts, anyone who wants **AI in their pocket (literally)**

---

#### [mimiclaw](https://github.com/memovai/mimiclaw)   
Recommand:⭐⭐⭐⭐⭐    
Oh my god, running openclaw on a real embedded device? You must be kidding me!

> MimiClaw: Run OpenClaw on a $5 chip. No OS(Linux). No Node.js.

```yaml
Dev: memovai
Hardware: $5 MCU
VS picoclaw: Smarter, because why not? 🧠
```

**Why It's Awesome:**
- 💰 Same $5 price point
- 🧠 Better intelligence than picoclaw
- 🎯 No Linux, no Node.js headaches
- 📦 Shareable device

**Best For:** Edge computing, embedded AI, showing off at meetups

---

#### [moltis](https://github.com/moltis-org/moltis)   
Recommand:⭐⭐⭐⭐   
Another option instead of Openclaw

> A personal AI assistant built in Rust. Single binary, multi-provider LLMs.

```yaml
Language: Rust
Deployment: Single binary
Features: Full-stack Rust experience
```

**Why It's Awesome:**
- 📦 Single binary, dependencies included
- 🧠 Long-term memory
- 🛡️ Sandbox execution
- 🎙️ Voice support
- 🔌 MCP tool integration
- 💬 Multi-channel: Web, Telegram, API

**Best For:** Rust lovers who want **performance AND features**

---

#### [bashobot](https://github.com/uraimo/bashobot)    
Recommand:⭐⭐   
Funny project but,not so popular...

> An OpenClaw inspired personal assistant in 100% Bash.

```yaml
Language: Bash
Lines: Minimal
Dependencies: None. Zero. Nada.
```

**Why It's Awesome:**
- 🐹 Pure Bash — because why not?
- ⚡ Zero dependencies
- 💻 Runs anywhere with `sh`
- 😎 Extreme minimalism

**Best For:** Bash wizards, retro computing fans, anyone who enjoys **beating impossible odds**

---

#### [microclaw](https://github.com/microclaw/microclaw)    
Recommand:⭐⭐⭐   
have not try,but it have a full GUI.

> An agentic AI assistant that lives in your Telegram/Discord/Slack/Feishu chats.

```yaml
Language: Rust
Inspired: nanoClaw
Platforms: All the chats
```

**Why It's Awesome:**
- 🚀 Rust performance
- 💬 Chat-native integration
- 🔥 Inspired by the best

**Best For:** Developers who want performance **where conversations happen**

---


#### [nanoClaw](https://github.com/ysz/nanoClaw)   
Recommand:⭐   
not so popular rebuilt project

> Easy install, Ultra-lightweight secure AI assistant. Inspired by OpenClaw. 🦀

```yaml
Language: Python
Code: ~4,281 LOC
VS OpenClaw: 99% smaller, 10x faster to deploy
```

**Why It's Awesome:**
- 🔒 Container isolation for security-first design
- 🚀 Powered by Claude Code as core engine
- 💻 CLI-first, dead simple to use
- ✅ Two-minute deployment

**Best For:** Security-conscious users who want things **to just work**™

---

#### [goclaw](https://github.com/smallnest/goclaw)   
Recommand:⭐⭐   
but we already have PicoClaw?

> An open-source AI assistant framework like openclaw.

```yaml
Language: Go
Deployment: Single binary
Channels: Telegram + Feishu
```

**Why It's Awesome:**
- 🦊 Go performance
- 📦 Simple deployment
- 💬 Dual channel support
- ⏰ Task scheduling + memory

**Best For:** Go developers who want **productivity without complexity**

---

#### [liteclaw](https://github.com/liteclaw/liteclaw)   
Recommand:⭐   
but we already have PicoClaw?

> High-performance, single-binary rewrite of OpenClaw in Golang.

```yaml
Language: Go
Based on: TypeScript OpenClaw
Target: Lightweight Go reimplementation
```

**Why It's Awesome:**
- 🔄 TypeScript OpenClaw → Go
- 📉 Dramatically reduced resource usage
- ✅ Core features preserved

**Best For:** Anyone who loves OpenClaw but wants it **lighter and faster**

---

#### [rustclaw](https://github.com/shimaenaga1123/rustclaw)    
Recommand:⭐  
seems a pure VIBECODING project.but we already have ZeroClaw?

> A lightweight, memory-aware Discord AI assistant powered by Anthropic-compatible APIs.

```yaml
Language: Rust
Focus: Discord
API: Anthropic-compatible
```

**Why It's Awesome:**
- 🎮 Discord-focused
- 💾 Memory-efficient
- 🤖 Anthropic API compatible

**Best For:** Discord servers that need **AI that remembers conversations**

---

#### [miniclawd](https://github.com/FoundDream/miniclawd)   
Recommand:⭐⭐   
GUI is good,not so popular,you can try it,i have not try

> A lightweight openclaw build with TypeScript.

```yaml
Language: TypeScript
Type: Simplified OpenClaw
Target: TypeScript developers
```

**Why It's Awesome:**
- 💻 TypeScript-native
- 📦 Lightweight profile
- 🎯 Focused feature set

**Best For:** TS devs who want OpenClaw **without the 430K LOC baggage**

---

#### [secure-openclaw](https://github.com/ComposioHQ/secure-openclaw)    
Recommand:⭐⭐⭐⭐   
trust me,sucure is also important!

> A personal 24x7 AI assistant like OpenClaw on messaging platforms.

```yaml
Integration: 500+ apps
Channels: WhatsApp, Telegram, Signal, iMessage
```

**Why It's Awesome:**
- 🔧 Full tool access
- 🧠 Persistent memory
- ⏰ Scheduled reminders
- 💬 Cross-platform messaging

**Best For:** Power users who want AI **everywhere they message**

---


#### [myclaw](https://github.com/stellarlinkco/myclaw)   
Recommand:⭐   
VIBE PROJECT.It looks no different from an ordinary openclaw

> Self-hosted AI Agent Gateway written in Go

```yaml
Dev: Stellar Link (星纬智联)
Language: Go
Code: ~2,000 LOC core
```

**Why It's Awesome:**
- 📦 Single binary deployment — copy-paste-run
- 💬 Dual channel: Telegram + Feishu
- ⏰ Scheduled tasks, memory persistence
- 🦊 Go performance: fast, reliable

**Best For:** Go ecosystem enthusiasts who love **single-file deployments**


### 🏢 Enterprise Platforms

#### [Dify](https://github.com/langgenius/dify)   
Recommand:⭐   
Not Agentic Agent platform,just Ordinary performance

> Production-ready platform for agentic workflow development.

```yaml
Language: Python
Type: Enterprise + Open Source
Deployment: Docker/K8s
```

**Why It's Awesome:**
- 🏢 Production-ready, battle-tested
- 🤝 100+ LLM compatibility
- 🔌 Plugin ecosystem
- 🔧 Low-code workflow builder
- 🔒 Self-hosted available

**Best For:** Enterprises serious about **AI at scale**

---

#### [openakita](https://github.com/openakita/openakita)   
Recommand:⭐⭐⭐   
An out-of-the-box agent platform, looks good

> An open-source AI assistant framework with skills and agent architecture.

```yaml
Features: Skill system, Agent architecture
Design: Extensible, customizable
```

**Why It's Awesome:**
- 🧩 Skill-based architecture
- 🤖 Purpose-built for agents
- 🔌 Extensible design

**Best For:** Teams that want **custom frameworks built from scratch**

---

### 🧩 Ecosystem Tools

#### 🚀 Deployment Tools / 部署工具

| Project | Description | GitHub |
|---------|-------------|--------|
| **OpenClawInstaller** | One-click terminal deployment | [GitHub](https://github.com/sdwadsagw/OpenClawInstaller) |
| **MoltWorker** | Cloudflare serverless deployment | [GitHub](https://github.com/cloudflare/moltworker) |
| **openclaw-helm** | Kubernetes Helm Chart | [GitHub](https://github.com/serhanekicii/openclaw-helm) |
| **openclaw-coolify** | Coolify one-click template | [GitHub](https://github.com/essamamdani/openclaw-coolify) |
| **openclaw-unraid** | Unraid NAS template | [GitHub](https://github.com/jdhill777/openclaw-unraid) |
| **openclaw-umbrel** | Umbrel App Store integration | [GitHub](https://github.com/harmalh/openclaw-umbrel) |

#### 🧠 Memory Systems / 记忆系统

| Project | Description | GitHub |
|---------|-------------|--------|
| **memU** | OpenClaw's long-term memory layer ("AI Agent's Second Brain") | [GitHub](https://github.com/NevaMind-AI/memU) |
| **memu-engine-for-OpenClaw** | MemU engine OpenClaw plugin | [GitHub](https://github.com/duxiaoxiong/memu-engine-for-OpenClaw) |
| **openclaw-memory-memu** | MemU semantic memory integration | [GitHub](https://github.com/murasame-desu-ai/openclaw-memory-memu) |

#### 🎨 Skill Collections / 技能集合

| Project | Description | GitHub |
|---------|-------------|--------|
| **awesome-openclaw-skills** | Official curated skills (565+ skills) | [GitHub](https://github.com/VoltAgent/awesome-openclaw-skills) |
| **awesome-openclaw** | Curated OpenClaw resource list | [GitHub](https://github.com/SamurAIGPT/awesome-openclaw) |
| **awesome-openclaw-skills-zh** | Chinese official skill library | [GitHub](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) |

#### 🌟 Derived Projects / 衍生项目

| Project | Description | GitHub |
|---------|-------------|--------|
| **Clawra** | Open-source AI girlfriend (viral skill) | [GitHub](https://github.com/openclaw-girl-agent/openclaw-ai-girlfriend-by-clawra) |
| **VisionClaw** | Meta Ray-Ban Glasses real-time AI assistant | [GitHub](https://github.com/sseanliu/VisionClaw) |
| **MarketBot** | Financial custom AI agent | [GitHub](https://github.com/EthanAlgoX/MarketBot) |

#### 📱 Client Apps / 客户端应用

| Project | Description | GitHub |
|---------|-------------|--------|
| **OpenClaw-app** | iOS client | [GitHub](https://github.com/acidoom/OpenClaw-app) |
| **openclaw-voice** | Browser voice chat | [GitHub](https://github.com/Purple-Horizons/openclaw-voice) |
| **openclaw-glasses** | Even G1 smart glasses voice assistant | [GitHub](https://github.com/littlebotshi/openclaw-glasses) |
| **Cherry Studio** | AI productivity studio, 300+ assistants | [GitHub](https://github.com/CherryHQ/cherry-studio) |

#### 📊 Dashboard / 管理面板

| Project | Description | GitHub |
|---------|-------------|--------|
| **openclaw-command-center** | AI assistant command center | [GitHub](https://github.com/jontsai/openclaw-command-center) |
| **openclaw-dashboard** | Apple Liquid Glass style dashboard | [GitHub](https://github.com/casianig/openclaw-dashboard) |

#### 📚 Knowledge Management / 知识管理集成

| Project | Description | GitHub |
|---------|-------------|--------|
| **arrowhead** | Obsidian-aware search, make AI your knowledge assistant | [GitHub](https://github.com/totocaster/arrowhead) |

---

## 💰 Commercial Products

### ☁️ Cloud-Hosted Services / 云端托管服务

#### Direct Competitors / 直接竞品

| Product | Company | Pricing | Features | Status |
|---------|--------|--------|----------|--------|
| **KimiClaw** | 月之暗面 | ~¥99/month | Cloud-only, zero-entry setup, auto-adapts K2.5 Thinking Model | Commercial |
| **CoPaw** | 阿里云通义 | Free + Paid | Local + Cloud dual deploy, full system support, DingTalk/Feishu remote control | Commercial |

#### Enterprise Solutions / 企业级解决方案

| Product | Company | Pricing | Features | Status |
|---------|--------|--------|----------|--------|
| **实在 Agent** | 实在智能 | Enterprise custom | Private/Cloud/Hybrid deployment, Office/WPS deep integration, rich plugin market | Commercial |
| **QoderWork** | 阿里 | TBD | Desktop AI assistant, integrated with Alibaba Cloud services | Commercial |
| **Coze** | 字节跳动 | Free + Paid | Low-code platform, 60+ plugin ecosystem, Douyin/Feishu integration | [coze.cn](https://www.coze.cn) |
| **腾讯云 ADP** | 腾讯云 | Enterprise custom | Enterprise platform, deep Tencent Cloud & IM ecosystem integration | Commercial |

> **Note:**
> - Commercial pricing and features subject to official announcements
> - Projects marked "Commercial" may be proprietary or require payment
> - Some projects still in development — follow official channels for updates

---

## 🏗️ Architecture Comparison

| Project | Core Language | Code Size | Deploy Difficulty | Core Advantage | Best For |
|---------|---------------|-----------|-------------------|----------------|----------|
| **OpenClaw** | TypeScript | 430K+ LOC | 🟡 Medium | Feature-rich, mature ecosystem | Full power users |
| **nanobot** | Python | ~3.4K LOC | 🟢 Easy | Ultra-lightweight, 2-min deploy | Research, quick start |
| **myclaw** | Go | ~2K LOC | 🟢 Easy | Single binary, Go performance | Go developers |
| **nanoClaw** | Python | ~4.3K LOC | 🟢 Easy | Minimal security-focused setup | Security-first users |
| **ZeroClaw** | Rust | ~3.4MB binary | 🟡 Medium | Blazing fast, tiny footprint | Performance zealots |
| **moltis** | Rust | Medium | 🟡 Medium | Full-featured Rust AI assistant | Rust enthusiasts |
| **bashobot** | Bash | Minimal | 🟢 Easy | Zero dependencies, pure Bash | Minimalists, retro fans |
| **picoclaw** | (embedded) | Small | 🟢 Easy | $5 chip deployment | IoT, edge computing |
| **mimiclaw** | (embedded) | Small | 🟢 Easy | $5 chip, smarter | Edge AI demos |
| **goclaw** | Go | ~2K LOC | 🟢 Easy | Go performance, simple | Go ecosystem |
| **liteclaw** | Go | Medium | 🟢 Easy | Lightweight Go OpenClaw | Go + low resources |
| **microclaw** | Rust | Small | 🟡 Medium | Chat-native Rust | Chat platforms |
| **miniclawd** | TypeScript | Light | 🟡 Medium | Simplified OpenClaw | TypeScript devs |
| **rustclaw** | Rust | Small | 🟡 Medium | Discord-specific | Discord servers |
| **Dify** | Python | Large | 🟠 Medium-Hard | Enterprise, low-code platform | Enterprise AI apps |
| **openakita** | TBD | TBD | TBD | Skill system, agent architecture | Custom frameworks |

---

## 🎯 Selection Guide

### By User Type

| User Type | Top Pick | Why |
|-----------|----------|-----|
| **🤓 Tech Enthusiasts / Developers** | OpenClaw, moltis | Open source freedom, highly customizable, active community |
| **👨‍💼 Regular Users / Professionals** | nanoClaw, KimiClaw | Zero friction, great UX, reliable & secure |
| **🏢 Enterprise Teams** | Dify, 实在 Agent, 腾讯云 ADP | Pro support, security guarantees, enterprise features |
| **⚡ Lightweight Seekers** | bashobot, ZeroClaw | Minimum resource usage, instant deployment |
| **🔧 Edge Computing / IoT** | picoclaw, mimiclaw | Runs on $5 chips, no OS needed |
| **🐹 Bash Wizards** | bashobot | Pure Bash, maximum flex |

### By Tech Stack

```yaml
TypeScript / Node.js:
  → OpenClaw (the OG), miniclawd

Python:
  → nanoClaw (security focus), nanobot (research-friendly), Dify (enterprise)

Rust:
  → ZeroClaw (performance), moltis (full-featured), rustclaw (Discord), microclaw (chat-native)

Go:
  → myclaw, goclaw, liteclaw (pick your single binary)

Bash:
  → bashobot (because why not?)
```

### By Deployment Method

```yaml
Local Deployment:
  → OpenClaw, nanoClaw, myclaw, ZeroClaw, moltis

Cloud Hosted / Serverless:
  → MoltWorker (Cloudflare), KimiClaw, CoPaw

Container (Docker):
  → Most projects support Docker

Kubernetes:
  → OpenClaw (Helm Chart), Dify

NAS / Home Lab:
  → OpenClaw Unraid/Umbrel

Bare Metal / Edge:
  → picoclaw, mimiclaw ($5 chips)
```

### Quick Decision Tree 🌳

```
Need AI Assistant?
    │
    ├─ Want full power & all features?
    │   └─ → OpenClaw 🦞
    │
    ├─ Performance critical?
    │   ├─ Go ecosystem? → myclaw / goclaw / liteclaw 🦊
    │   └─ Rust wanted? → ZeroClaw / moltis 🦀
    │
    ├─ Resource constrained?
    │   ├─ Edge/IoT? → picoclaw / mimiclaw ( $5 chip ) 🔌
    │   └─ Desktop minimal? → bashobot / nanobot 💻
    │
    ├─ Enterprise / Team?
    │   └─ → Dify / 实在 Agent 🏢
    │
    ├─ Just want it to work?
    │   └─ → nanoClaw / KimiClaw ✨
    │
    └─ Discord server?
        └─ → rustclaw 🎮
```

---

## 🤝 Contributing

Want to make this list more awesome? Submit a Pull Request!

### Adding New Projects

Please include:
- ✅ Project name & tagline
- 🔗 GitHub repository link
- 💻 Core tech stack
- ✨ Key features (2-3 bullets max)
- 🎯 Best-fit scenario

### Category Criteria

| Category | Definition |
|----------|------------|
| **Open Source** | Source code publicly available |
| **Commercial** | Proprietary or paid services |
| **Core Projects** | Complete AI assistant frameworks |
| **Lightweight Alternatives** | <10K LOC or focused on specific scenarios |
| **Enterprise Platforms** | Complete solutions for enterprise users |
| **Ecosystem Tools** | Auxiliary tools around core projects |

---

## 📄 License

This project is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

## 🔗 Related Resources

- 📖 [OpenClaw Official Documentation](https://docs.openclaw.ai)
- 🌐 [OpenClaw Official Website](https://openclaw.ai)
- 🎨 [Awesome OpenClaw Skills](https://github.com/VoltAgent/awesome-openclaw-skills)
- 💬 [OpenClaw Discord Community](https://discord.gg/openclaw)

---

**Last Updated:** February 18, 2026

**Maintainers:** Community-maintained document

---

> *"Your own personal AI assistant. Any OS. Any Platform. The lobster way."* — OpenClaw 🦞

---

<div align="center">

```
███████╗██╗      █████╗ ████████╗ ██████╗  ██████╗ ███████╗███╗   ███╗
██╔════╝██║     ██╔══██╗╚══██╔══╝██╔════╝ ██╔═══██╗██╔════╝████╗ ████║
███████╗██║     ███████║   ██║   ██║  ███╗██║   ██║█████╗  ██╔████╔██║
╚════██║██║     ██╔══██║   ██║   ██║   ██║██║   ██║██╔══╝  ██║╚██╔╝██║
███████║███████╗██║  ██║   ██║   ╚██████╔╝╚██████╔╝███████╗██║ ╚═╝ ██║
╚══════╝╚══════╝╚═╝  ╚═╝   ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝╚═╝     ╚═╝
          A W E S O M E   O P E N C L A W   A L T E R N A T I V E S
                                  🦞
```

</div>
