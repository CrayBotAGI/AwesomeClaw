# Awesome OpenClaw Alternatives 中文版

> 精选的类 OpenClaw AI 助手项目清单 | Curated list of OpenClaw-like AI assistant projects

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![好玩](https://img.shields.io/badge/状态-好玩%20%26%20强大-orange.svg)](https://github.com/)

[OpenClaw](https://github.com/openclaw/openclaw) — 你的个人 AI 助手。任何操作系统。任何平台。龙虾哲学。🦞

本文档收集了与它类似的开源替代方案和商业产品。无论你是**龙虾驯兽师**、**性能狂热者**、**极简修道僧**，还是**边缘计算巫师**——这里都有适合你的选择！

---

## 🦞 为什么会有这个清单

OpenClaw 很强大，但是体量巨大：**超过 43 万行 TypeScript 代码**。不是每个人都需要这么强大的肌肉力量。我们覆盖的范围如下：

```
┌─────────────────────────────────────────────────────────────────────┐
│                      令人惊叹的 OpenClaw 光谱                        │
├─────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  沉重 ──────► 中等 ──────► 轻量 ──────► 微型 ──────► 边缘芯片        │
│                                                                      │
│  [🦞 43万行 ] [🦀 4万行    ] [⚡ 4千行    ] [💻 2千行    ] [🔌 5美元   ] │
│   OpenClaw    Dify        nanoClaw    bashobot    picoclaw        │
│               moltis      nanobot     myclaw      mimiclaw        │
│                                                                      │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 📚 目录

- [为什么会有这个清单](#️-为什么会有这个清单)
- [原文档项目总览](#-原文档项目总览)
- [开源项目](#-开源项目)
  - [🦞 核心项目](#️-核心项目)
  - [⚡ 轻量级替代](#-轻量级替代)
  - [🏢 企业级平台](#️-企业级平台)
  - [🧩 生态工具](️-生态工具)
- [商业产品](#-商业产品)
- [技术架构对比](#️-技术架构对比)
- [选型指南](#-选型指南)
- [贡献指南](#-贡献指南)
- [许可证](#-许可证)

---

## 📋 原文档项目总览

根据用户提供的数据，以下是所有项目的分类：

### 直接竞品（同赛道对标）

| 项目 | 公司 | 类型 | GitHub/官网 |
|------|------|------|-------------|
| **KimiClaw** | 月之暗面 | 商业 | 待补充 |
| **CoPaw** | 阿里云通义 | 商业 | 待补充 |

### 轻量替代方案

| 项目 | 开发方 | 语言 | 代码量 | GitHub |
|------|--------|------|--------|--------|
| **nanobot** | 香港大学 HKUDS | Python | ~3,428 行 | [GitHub](https://github.com/HKUDS/nanobot) |
| **myclaw** | 星纬智联 | Go | ~2,000 行 | [GitHub](https://github.com/stellarlinkco/myclaw) |
| **ZeroClaw** | 社区 | Rust | ~3.4MB 二进制 | [GitHub](https://github.com/brooks376/zeroclaw.bot) |
| **NanoClaw** | 社区 | Python | ~4,281 行 | [GitHub](https://github.com/ysz/nanoClaw) |

### 企业级替代方案

| 项目 | 公司 | 类型 | GitHub/官网 |
|------|------|------|-------------|
| **实在 Agent** | 实在智能 | 商业 | 待补充 |
| **QoderWork** | 阿里 | 商业 | 待补充 |
| **Coze** | 字节跳动 | 商业 | https://www.coze.cn |
| **Dify** | langgenius | 开源 | [GitHub](https://github.com/langgenius/dify) |
| **腾讯云 ADP** | 腾讯云 | 商业 | 待补充 |

### OpenClaw 生态衍生项目

| 项目 | 描述 | GitHub |
|------|------|--------|
| **OpenClawInstaller** | 终端一键部署方案 | [GitHub](https://github.com/sdwadsagw/OpenClawInstaller) |
| **OneClaw** | 小白零门槛桌面版 | [GitHub](https://github.com/oneclaw/oneclaw) |
| **Awesome OpenClaw Skills** | 精选 565+ 技能清单 | [GitHub](https://github.com/VoltAgent/awesome-openclaw-skills) |
| **MoltWorker** | 云端部署解放本地硬件 | [GitHub](https://github.com/cloudflare/moltworker) |
| **memU** | OpenClaw 的长期记忆层 | [GitHub](https://github.com/NevaMind-AI/memU) |
| **Clawra** | 开源 AI 女友（破圈级 Skill） | [GitHub](https://github.com/openclaw-girl-agent/openclaw-ai-girlfriend-by-clawra) |
| **picoclaw** | 在 $5 芯片上运行。无需操作系统。无需 Node.js。 | [GitHub](https://github.com/sipeed/picoclaw) |
| **mimiclaw** | 在 $5 芯片上运行（更智能） | [GitHub](https://github.com/memovai/mimiclaw) |

---

## 🦞 开源项目

### 🦞 核心项目

#### [OpenClaw](https://github.com/openclaw/openclaw)

> 你的个人 AI 助手。任何操作系统。任何平台。龙虾哲学。🦞

```yaml
语言: TypeScript
代码量: 430,000+ 行
星标: ⭐ 查看 GitHub
```

**核心特点：**
- 功能丰富的个人 AI 助手
- 多渠道接入：WhatsApp、Telegram、Discord、Slack、飞书
- 完善的技能系统和插件生态
- 持久化记忆和上下文管理
- 经过大规模实战检验

**相关链接：**
- 🌐 [openclaw.ai](https://openclaw.ai)
- 📖 [docs.openclaw.ai](https://docs.openclaw.ai)

---

### ⚡ 轻量级替代

#### [nanoClaw](https://github.com/ysz/nanoClaw)

> 易于安装、超轻量安全的 AI 助手。受 OpenClaw 启发。🦀

```yaml
语言: Python
代码量: ~4,281 行
对比: 体积小 99%，部署速度快 10 倍
```

**为什么它很棒：**
- 🔒 容器隔离，安全至上
- 🚀 由 Claude Code 驱动
- 💻 命令行优先，简单直接
- ✅ 两分钟完成部署

**最适合：** 安全敏感的用户，想要「一键即用」的人群

---

#### [nanobot](https://github.com/HKUDS/nanobot)

> 超轻量级个人 AI 助理 | Ultra-lightweight personal AI assistant

```yaml
开发方: HKUDS (香港大学)
语言: Python
代码量: ~3,428 行 (比 OpenClaw 精简 99.2%)
```

**为什么它很棒：**
- ⚡ 仅用约 4000 行代码实现 OpenClaw 核心功能
- 🧠 持久记忆、网页搜索、定时任务
- 🔌 支持多个 LLM 提供商
- 💬 Telegram/WhatsApp/飞书集成
- ⏱️ 真的只要两分钟部署（说真的）

**最适合：** 研究人员、学生、任何想要「最小代码，最大影响」的人

---

#### [myclaw](https://github.com/stellarlinkco/myclaw)

> 用 Go 编写的自托管 AI Agent 网关

```yaml
开发方: Stellar Link (星纬智联)
语言: Go
代码量: ~2,000 行核心代码
```

**为什么它很棒：**
- 📦 单二进制部署 —— 复制粘贴即可运行
- 💬 双通道：Telegram + 飞书
- ⏰ 定时任务、记忆持久化
- 🦊 Go 性能：快速、可靠

**最适合：** Go 生态爱好者，喜欢「单文件部署」的开发者

---

#### [ZeroClaw](https://github.com/brooks376/zeroclaw.bot)

> 用 Rust 构建的高性能开源 AI 智能体框架。

```yaml
语言: Rust
二进制大小: ~3.4MB
启动速度: ⚡ 眨眼间完成
```

**为什么它很棒：**
- 🚀 极速启动
- 💪 低内存占用
- 🔗 OpenRouter：22+ 模型，一个 API
- 🔌 可插拔架构
- 🛡️ 强大的安全控制

**最适合：** 资源受限环境、边缘计算、性能狂热者

---

#### [picoclaw](https://github.com/sipeed/picoclaw)

> 在 $5 芯片上运行 OpenClaw。无需操作系统。无需 Node.js。无需 Mac mini。

```yaml
开发方: Sipeed
硬件: $5 单片机
系统: 无。纯裸机运行！🔥
```

**为什么它很棒：**
- 💰 5 美元硬件 —— 比一杯咖啡还便宜
- 🎯 不需要操作系统 —— 到处都能跑
- 📦 便携、可分享
- 🔒 隐私优先，本地记忆

**最适合：** 黑客、物联网爱好者、想要「AI 装进口袋」的人（真的）

---

#### [mimiclaw](https://github.com/memovai/mimiclaw)

> MimiClaw：在 $5 芯片上运行 OpenClaw。无需操作系统（Linux）。无需 Node.js。

```yaml
开发方: memovai
硬件: $5 单片机
对比: 智能度优于 picoclaw，为什么不呢？🧠
```

**为什么它很棒：**
- 💰 同样的 5 美元价格
- 🧠 比 picoclaw 更智能
- 🎯 无 Linux、无 Node.js 的烦恼
- 📦 可共享的设备

**最适合：** 边缘计算、嵌入式 AI、在聚会上炫耀

---

#### [moltis](https://github.com/moltis-org/moltis)

> 用 Rust 构建的个人 AI 助手。单二进制，多 LLM 提供商。

```yaml
语言: Rust
部署方式: 单二进制
特点: 全栈 Rust 体验
```

**为什么它很棒：**
- 📦 单二进制，依赖全包含
- 🧠 长期记忆
- 🛡️ 沙箱执行
- 🎙️ 语音支持
- 🔌 MCP 工具集成
- 💬 多通道：Web、Telegram、API

**最适合：** Rust 爱好者，想要「性能 + 功能」

---

#### [bashobot](https://github.com/uraimo/bashobot)

> 受 OpenClaw 启发、100% 用 Bash 编写的个人助手。

```yaml
语言: Bash
代码量: 极简
依赖: 无。零。没有。Nada。
```

**为什么它很棒：**
- 🐹 纯 Bash —— 因为为什么不呢？
- ⚡ 零依赖
- 💻 任何有 `sh` 的地方都能运行
- 😎 极致极简主义

**最适合：** Bash 奇才、复古计算爱好者、任何享受「挑战不可能」的人

---

#### [microclaw](https://github.com/microclaw/microclaw)

> 生活在你的 Telegram/Discord/Slack/飞书聊天中的敏捷 AI 助手。

```yaml
语言: Rust
灵感来自: nanoClaw
平台: 所有聊天软件
```

**为什么它很棒：**
- 🚀 Rust 性能
- 💬 原生聊天集成
- 🔥 汲取精华

**最适合：** 想要在「对话发生的地方」拥有性能的开发者

---

#### [goclaw](https://github.com/smallnest/goclaw)

> 类似 openclaw 的开源 AI 助手框架。

```yaml
语言: Go
部署方式: 单二进制
通道: Telegram + 飞书
```

**为什么它很棒：**
- 🦊 Go 性能
- 📦 简单部署
- 💬 双通道支持
- ⏰ 任务调度 + 记忆

**最适合：** Go 开发者，想要「简单即生产力」

---

#### [liteclaw](https://github.com/liteclaw/liteclaw)

> 用 Golang 实现的 OpenClaw 高性能单二进制重写版本。

```yaml
语言: Go
基于: TypeScript 版本的 OpenClaw
目标: 轻量级 Go 重实现
```

**为什么它很棒：**
- 🔄 TypeScript OpenClaw → Go
- 📉 大幅降低资源占用
- ✅ 保留核心功能

**最适合：** 喜欢 OpenClaw 但想要「更轻更快」的人

---

#### [rustclaw](https://github.com/shimaenaga1123/rustclaw)

> 一款轻量级、具有内存意识的 Discord AI 助手，由 Anthropic 兼容 API 驱动。

```yaml
语言: Rust
专注: Discord
API: Anthropic 兼容
```

**为什么它很棒：**
- 🎮 专注 Discord 平台
- 💾 内存高效
- 🤖 Anthropic API 兼容

**最适合：** 需要「记住对话」的 Discord 服务器

---

#### [miniclawd](https://github.com/FoundDream/miniclawd)

> 用 TypeScript 实现的轻量级 openclaw 构建。

```yaml
语言: TypeScript
类型: 简化版 OpenClaw
目标: TypeScript 开发者
```

**为什么它很棒：**
- 💻 TypeScript 原生
- 📦 轻量级配置
- 🎯 专注的功能集

**最适合：** TS 开发者，想要 OpenClaw「没有 43 万行代码的包袱」

---

#### [secure-openclaw](https://github.com/ComposioHQ/secure-openclaw)

> 类似 OpenClaw 的 24×7 个人 AI 助手，运行在消息平台上。

```yaml
集成: 500+ 应用
通道: WhatsApp、Telegram、Signal、iMessage
```

**为什么它很棒：**
- 🔧 完整工具访问
- 🧠 持久记忆
- ⏰ 定时提醒
- 💬 跨平台消息推送

**最适合：** 想要 AI「在所有消息平台」都存在的超级用户

---

### 🏢 企业级平台

#### [Dify](https://github.com/langgenius/dify)

> 可投入生产的智能体工作流开发平台。

```yaml
语言: Python
类型: 企业级 + 开源
部署方式: Docker/K8s
```

**为什么它很棒：**
- 🏢 生产就绪，经过实战检验
- 🤝 兼容 100+ 主流 LLM
- 🔌 插件生态
- 🔧 低代码工作流构建器
- 🔒 支持私有化部署

**最适合：** 认真对待「大规模 AI 应用的企业」

---

#### [openakita](https://github.com/openakita/openakita)

> 具有技能系统和智能体架构的开源 AI 助手框架。

```yaml
特点: 技能系统、智能体架构
设计: 可扩展、可定制
```

**为什么它很棒：**
- 🧩 基于技能的架构
- 🤖 专为实现智能体而设计
- 🔌 可扩展性

**最适合：** 想要「从零打造自定义框架」的团队

---

### 🧩 生态工具

#### 🚀 部署工具

| 项目 | 描述 | GitHub |
|------|------|--------|
| **OpenClawInstaller** | 终端一键部署方案 | [GitHub](https://github.com/sdwadsagw/OpenClawInstaller) |
| **MoltWorker** | Cloudflare 无服务器部署 | [GitHub](https://github.com/cloudflare/moltworker) |
| **openclaw-helm** | Kubernetes Helm Chart | [GitHub](https://github.com/serhanekicii/openclaw-helm) |
| **openclaw-coolify** | Coolify 一键部署模板 | [GitHub](https://github.com/essamamdani/openclaw-coolify) |
| **openclaw-unraid** | Unraid NAS 部署模板 | [GitHub](https://github.com/jdhill777/openclaw-unraid) |
| **openclaw-umbrel** | Umbrel 应用商店集成 | [GitHub](https://github.com/harmalh/openclaw-umbrel) |

#### 🧠 记忆系统

| 项目 | 描述 | GitHub |
|------|------|--------|
| **memU** | OpenClaw 的长期记忆层（AI Agent 的「第二大脑」） | [GitHub](https://github.com/NevaMind-AI/memU) |
| **memu-engine-for-OpenClaw** | MemU 引擎的 OpenClaw 插件 | [GitHub](https://github.com/duxiaoxiong/memu-engine-for-OpenClaw) |
| **openclaw-memory-memu** | MemU 语义记忆集成 | [GitHub](https://github.com/murasame-desu-ai/openclaw-memory-memu) |

#### 🎨 技能集合

| 项目 | 描述 | GitHub |
|------|------|--------|
| **awesome-openclaw-skills** | 官方精选技能包（565+ 技能） | [GitHub](https://github.com/VoltAgent/awesome-openclaw-skills) |
| **awesome-openclaw** | 精选 OpenClaw 资源列表 | [GitHub](https://github.com/SamurAIGPT/awesome-openclaw) |
| **awesome-openclaw-skills-zh** | 中文官方技能库 | [GitHub](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) |

#### 🌟 衍生项目

| 项目 | 描述 | GitHub |
|------|------|--------|
| **Clawra** | 开源 AI 女友（破圈级技能） | [GitHub](https://github.com/openclaw-girl-agent/openclaw-ai-girlfriend-by-clawra) |
| **VisionClaw** | Meta Ray-Ban 智能眼镜实时 AI 助手 | [GitHub](https://github.com/sseanliu/VisionClaw) |
| **MarketBot** | 金融定制版 AI 代理 | [GitHub](https://github.com/EthanAlgoX/MarketBot) |

#### 📱 客户端应用

| 项目 | 描述 | GitHub |
|------|------|--------|
| **OpenClaw-app** | iOS 客户端 | [GitHub](https://github.com/acidoom/OpenClaw-app) |
| **openclaw-voice** | 浏览器语音聊天 | [GitHub](https://github.com/Purple-Horizons/openclaw-voice) |
| **openclaw-glasses** | Even G1 智能眼镜语音助手 | [GitHub](https://github.com/littlebotshi/openclaw-glasses) |
| **Cherry Studio** | AI 生产力工作室，300+ 助理 | [GitHub](https://github.com/CherryHQ/cherry-studio) |

#### 📊 管理面板

| 项目 | 描述 | GitHub |
|------|------|--------|
| **openclaw-command-center** | AI 助手指挥控制中心 | [GitHub](https://github.com/jontsai/openclaw-command-center) |
| **openclaw-dashboard** | Apple 液态玻璃风格仪表盘 | [GitHub](https://github.com/casianig/openclaw-dashboard) |

#### 📚 知识管理集成

| 项目 | 描述 | GitHub |
|------|------|--------|
| **arrowhead** | Obsidian 感知搜索，让 AI 成为知识助手 | [GitHub](https://github.com/totocaster/arrowhead) |

---

## 💰 商业产品

### ☁️ 云端托管服务

#### 直接竞品

| 产品 | 公司 | 定价 | 特点 | 状态 |
|------|------|------|------|------|
| **KimiClaw** | 月之暗面 | ~99 元/月 | 纯云端托管，零门槛使用，自动适配 K2.5 Thinking 模型 | 商业产品 |
| **CoPaw** | 阿里云通义 | 免费 + 付费 | 本地 + 云端双部署，全系统支持，钉钉/飞书远程操控 | 商业产品 |

#### 企业级解决方案

| 产品 | 公司 | 定价 | 特点 | 状态 |
|------|------|------|------|------|
| **实在 Agent** | 实在智能 | 企业定制 | 私有化/云端/混合部署，Office/WPS 深度集成，丰富插件市场 | 商业产品 |
| **QoderWork** | 阿里 | 待公布 | 桌面 AI 助理，集成阿里云服务 | 商业产品 |
| **Coze** | 字节跳动 | 免费 + 付费 | 低代码平台，60+ 插件生态，支持抖音、飞书集成 | [coze.cn](https://www.coze.cn) |
| **腾讯云 ADP** | 腾讯云 | 企业定制 | 企业级平台，深度集成腾讯云和 IM 生态 | 商业产品 |

> **注意：**
> - 商业产品的具体价格和功能请以官方发布为准
> - 标记为「商业产品」的项目可能未开源或需付费使用
> - 部分项目可能仍在开发中，请关注官方渠道获取更新

---

## 🏗️ 技术架构对比

| 项目 | 核心语言 | 代码量 | 部署难度 | 核心优势 | 适合场景 |
|------|----------|--------|----------|----------|----------|
| **OpenClaw** | TypeScript | 43万+ 行 | 🟡 中等 | 功能丰富，生态成熟 | 全功能用户 |
| **nanobot** | Python | ~3.4K 行 | 🟢 容易 | 极致轻量，2 分钟部署 | 学术研究、快速上手 |
| **myclaw** | Go | ~2K 行 | 🟢 容易 | 单二进制，Go 性能 | Go 开发者 |
| **nanoClaw** | Python | ~4.3K 行 | 🟢 容易 | 极简安全配置 | 安全优先用户 |
| **ZeroClaw** | Rust | ~3.4MB 二进制 | 🟡 中等 | 极速启动，小体积 | 性能狂热者 |
| **moltis** | Rust | 中型 | 🟡 中等 | 全功能 Rust AI 助手 | Rust 爱好者 |
| **bashobot** | Bash | 极简 | 🟢 容易 | 零依赖，纯 Bash | 极简主义者、怀旧派 |
| **picoclaw** | （嵌入式） | 小型 | 🟢 容易 | $5 芯片部署 | 物联网、边缘计算 |
| **mimiclaw** | （嵌入式） | 小型 | 🟢 容易 | $5 芯片，更智能 | 边缘 AI 演示 |
| **goclaw** | Go | ~2K 行 | 🟢 容易 | Go 性能，简单 | Go 生态 |
| **liteclaw** | Go | 中型 | 🟢 容易 | 轻量级 Go OpenClaw | Go + 低资源 |
| **microclaw** | Rust | 小型 | 🟡 中等 | 聊天原生 Rust | 聊天平台 |
| **miniclawd** | TypeScript | 轻量 | 🟡 中等 | 简化版 OpenClaw | TypeScript 开发者 |
| **rustclaw** | Rust | 小型 | 🟡 中等 | Discord 专用 | Discord 服务器 |
| **Dify** | Python | 大型 | 🟠 中-高 | 企业级、低代码平台 | 企业 AI 应用 |
| **openakita** | 待定 | 待定 | 待定 | 技能系统、智能体架构 | 自定义框架 |

---

## 🎯 选型指南

### 按用户类型

| 用户类型 | 首选推荐 | 原因 |
|----------|----------|------|
| **🤓 技术发烧友 / 开发者** | OpenClaw、moltis | 开源自由、高度定制、活跃社区 |
| **👨‍💼 普通用户 / 职场人** | nanoClaw、KimiClaw | 零门槛操作，良好的用户体验，安全可靠 |
| **🏢 企业团队** | Dify、实在 Agent、腾讯云 ADP | 专业支持、安全保障、企业级功能 |
| **⚡ 轻量需求** | bashobot、ZeroClaw | 最小资源占用，快速部署 |
| **🔧 边缘计算/物联网** | picoclaw、mimiclaw | 在 5 美元芯片上运行，无需操作系统 |
| **🐹 Bash 高手** | bashobot | 纯 Bash，极致炫技 |

### 按技术栈

```yaml
TypeScript / Node.js:
  → OpenClaw（原版）、miniclawd

Python:
  → nanoClaw（安全优先）、nanobot（研究友好）、Dify（企业级）

Rust:
  → ZeroClaw（性能优先）、moltis（全能）、rustclaw（Discord）、microclaw（聊天原生）

Go:
  → myclaw、goclaw、liteclaw（任选你的单二进制）

Bash:
  → bashobot（因为为什么不呢？）
```

### 按部署方式

```yaml
本地部署:
  → OpenClaw、nanoClaw、myclaw、ZeroClaw、moltis

云端托管 / 无服务器:
  → MoltWorker（Cloudflare）、KimiClaw、CoPaw

容器化:
  → 大部分项目都支持 Docker

Kubernetes:
  → OpenClaw（Helm Chart）、Dify

NAS / 家庭实验室:
  → OpenClaw Unraid/Umbrel

裸机 / 边缘:
  → picoclaw、mimiclaw（5 美元芯片）
```

### 快速决策树 🌳

```
需要 AI 助手？
    │
    ├─ 想要全部功能和所有特性？
    │   └─ → OpenClaw 🦞
    │
    ├─ 性能至上？
    │   ├─ Go 生态？ → myclaw / goclaw / liteclaw 🦊
    │   └─ Rust 首选？ → ZeroClaw / moltis 🦀
    │
    ├─ 资源受限？
    │   ├─ 边缘/物联网？ → picoclaw / mimiclaw（$5 芯片）🔌
    │   └─ 桌面极简？ → bashobot / nanobot 💻
    │
    ├─ 企业 / 团队？
    │   └─ → Dify / 实在 Agent 🏢
    │
    ├─ 只想要简单能用的？
    │   └─ → nanoClaw / KimiClaw ✨
    │
    └─ Discord 服务器？
        └─ → rustclaw 🎮
```

---

## 🤝 贡献指南

想让这个清单更棒？提交 Pull Request！

### 添加新项目

请包含：
- ✅ 项目名称和标语
- 🔗 GitHub 仓库链接
- 💻 核心技术栈
- ✨ 主要特点（最多 3 条要点）
- 🎯 最佳适用场景

### 分类标准

| 类别 | 定义 |
|------|------|
| **开源项目** | 源代码公开可用 |
| **商业产品** | 闭源或需付费使用 |
| **核心项目** | 完整的 AI 助手框架 |
| **轻量级替代** | 代码量小于 1 万行或专注特定场景 |
| **企业级平台** | 面向企业用户的完整解决方案 |
| **生态工具** | 围绕核心项目的辅助工具 |

---

## 📄 许可证

本项目采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 许可证。

---

## 🔗 相关资源

- 📖 [OpenClaw 官方文档](https://docs.openclaw.ai)
- 🌐 [OpenClaw 官网](https://openclaw.ai)
- 🎨 [Awesome OpenClaw Skills](https://github.com/VoltAgent/awesome-openclaw-skills)
- 💬 [OpenClaw Discord 社区](https://discord.gg/openclaw)

---

**最后更新：** 2026 年 2 月 18 日

**维护者：** 社区共同维护

---

> *"你的个人 AI 助手。任何操作系统。任何平台。龙虾哲学。"* — OpenClaw 🦞

---

<div align="center">

```
███████╗██║      █████╗ ████████╗ ██████╗  ██████╗ ███████╗███╗   ███╗
██╔════╝██║     ██╔══██╗╚══██╔══╝██╔════╝ ██╔═══██╗██╔════╝████╗ ████║
███████╗██║     ███████║   ██║   ██║  ███╗██║   ██║█████╗  ██╔████╔██║
╚════██║██║     ██╔══██║   ██║   ██║   ██║██║   ██║██╔══╝  ██║╚██╔╝██║
███████║███████╗██║  ██║   ██║   ╚██████╔╝╚██████╔╝███████╗██║ ╚═╝ ██║
╚══════╝╚══════╝╚═╝  ╚═╝   ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝╚═╝     ╚═╝
        令人惊叹的 OpenClaw 替代品中文版 🇨🇳
                                  🦞
```

</div>
