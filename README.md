# Awesome-OpenClaw-Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![](assets/banner.gif)

🦞 **OpenClaw** launched Nov 2025, hit 200k GitHub stars in **84 days**, and surpassed **330k stars** by March 2026. This repo is a **research-oriented** collection of papers, analyses, and resources on the OpenClaw ecosystem — the fastest-growing open-source AI agent framework.

<p align="center">
  <a href="#-papers"><img src="https://img.shields.io/badge/Papers-15%2B-blue?style=flat-square" alt="Papers"></a>
  <a href="https://github.com/openclaw/openclaw"><img src="https://img.shields.io/badge/OpenClaw-330k%2B%20Stars-yellow?style=flat-square" alt="Stars"></a>
  <a href="./README_CN.md"><img src="https://img.shields.io/badge/中文文档-点击查看-orange?style=flat-square" alt="中文"></a>
  <a href="#-contributing"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square" alt="PRs Welcome"></a>
  <a href="https://join.slack.com/t/openclaw-research/shared_invite/zt-3tetckn5x-tOKVsEEQN8ArnyxzqgWsAA"><img src="https://img.shields.io/badge/Slack-Join%20Us-4A154B?style=flat-square&logo=slack" alt="Slack"></a>
</p>

---

## Table of Contents

- [Papers](#-papers) — **Core of this repo**
  - [Core Architecture & Systems](#core-architecture--systems)
  - [Reinforcement Learning & Self-Evolution](#reinforcement-learning--self-evolution)
  - [Security & Trust](#security--trust)
  - [Embodied AI & Robotics](#embodied-ai--robotics)
  - [Agent Social Behavior](#agent-social-behavior)
  - [Personalized Agents](#personalized-agents-related)
- [Architecture](#-architecture)
- [Ecosystem Timeline](#-ecosystem-timeline)
- [Other Resources](#-other-resources) — SDKs, tools, community, related repos
- [Contributing](#-contributing)

---

## 📄 Papers

> 15+ papers published in Feb–Mar 2026 alone. Each entry includes paper link, code (if available), and key highlights.

### Core Architecture & Systems

| Title | Venue | Date | Paper | Code | Highlights |
|-------|-------|------|-------|------|------------|
| **AgentOS: NL-Driven OS Paradigm** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.08938-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.08938) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | Agent-centric OS paradigm; Skills-as-Modules; KDD framing |
| **OpenClaw as Language Infrastructure (Survey)** | Preprints.org | 2026.03 | [![Preprints](https://img.shields.io/badge/202603.1060-b31b1b?style=flat-square)](https://www.preprints.org/manuscript/202603.1060) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | GATE / AERO frameworks; analyzes 38 ecosystem papers |

### Reinforcement Learning & Self-Evolution

| Title | Venue | Date | Paper | Code | Highlights |
|-------|-------|------|-------|------|------------|
| **OpenClaw-RL: Train Any Agent Simply by Talking** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.10165) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/Gen-Verse/OpenClaw-RL) | Evaluative + Directive signals; async 4-component RL architecture |
| **MetaClaw: Meta-Learning in the Wild** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.17187-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.17187) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | Continuous meta-learning; skill-driven adaptation; accuracy 21.4% → 40.6% |

### Security & Trust

| Title | Venue | Date | Paper | Code | Highlights |
|-------|-------|------|-------|------|------------|
| **PASB: Benchmarking Attacks on OpenClaw** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.08412-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.08412) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/AstorYH/PASB) | End-to-end security eval; only 17% native defense rate |
| **Don't Let the Claw Grip Your Hand** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.10387-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.10387) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 47 adversarial scenarios; HITL defense: 17% → 19–92% |
| **SkillFortify: Formal Supply Chain Security** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.00195-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.00195) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/qualixar/skillfortify) [![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi)](https://pypi.org/project/skillfortify/) | 96.95% F1; 0% false positives; 22 agent frameworks |
| **OpenClaw PRISM: Runtime Security Layer** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11853-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11853) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | Defense-in-depth; zero-fork; anti prompt injection |

### Embodied AI & Robotics

| Title | Venue | Date | Paper | Code | Highlights |
|-------|-------|------|-------|------|------------|
| **RoboClaw: Agentic Framework for Robotic Tasks** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11558-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11558) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MINT-SJTU/RoboClaw) | Entangled Action Pairs; +25% success rate; −53.7% human effort |
| **ROSClaw: Bridging OpenClaw with ROS 2** | GitHub | 2026.03 | [![Blog](https://img.shields.io/badge/Blog-4CAF50?style=flat-square)](https://openclaws.io/blog/openclaw-robotics-embodied-ai) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/PlaiPin/rosclaw) | SF Hackathon champion; Unitree G1/H1, DJI; runs on RPi4 |

### Agent Social Behavior

| Title | Venue | Date | Paper | Code | Highlights |
|-------|-------|------|-------|------|------------|
| **From Agent-Only Social Networks to Autonomous Research** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.19810-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.19810) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | OpenClaw → Moltbook → ClawdLab; Sybil resistance |
| **OpenClaw Agents as Informal Learners at Moltbook** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.18832-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.18832) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 2.8M agents' informal learning behavior |
| **Peer Learning in the Moltbook Community** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.14477-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.14477) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 2.4M agents' peer learning patterns |
| **Risky Sharing & Norm Enforcement** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.02625-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.02625) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | Risk instruction sharing; self-regulation in agent communities |

### Personalized Agents (Related)

| Title | Venue | Date | Paper | Code | Highlights |
|-------|-------|------|-------|------|------------|
| **Toward Personalized LLM-Powered Agents** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.22680-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.22680) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | Four components: Profile / Memory / Planning / Action |

---

## 🏗 Architecture

```mermaid
flowchart LR
    subgraph Channels["📱 Channels"]
        direction TB
        C1[WhatsApp] ~~~ C2[Telegram] ~~~ C3[Discord] ~~~ C4[Slack] ~~~ C5["50+"]
    end

    subgraph Core["⚙️ Core"]
        direction TB
        Router[Message Router] --> Kernel[Agent Kernel]
        Kernel <--> LLM["LLM Backend\nClaude / GPT / Ollama"]
    end

    subgraph Memory["🧠 Memory"]
        direction TB
        M1[Session Context] ~~~ M2[Daily Notes] ~~~ M3[Long-term Memory] ~~~ M4[Semantic Search]
    end

    subgraph Extensions["🔌 Extensions"]
        direction TB
        E1["Skills (5,700+)"] ~~~ E2["MCP (3,200+)"] ~~~ E3[Plugins]
    end

    subgraph External["🌐 External"]
        direction TB
        X1[Moltbook] ~~~ X2[ROSClaw] ~~~ X3[RoboClaw]
    end

    Channels --> Core
    Core <--> Memory
    Core <--> Extensions
    Extensions --> External
```

---

## 📅 Ecosystem Timeline

```
2025.11 ─── Launch (ClawdBot / Moltbot → OpenClaw)
    │
2025.12 ─── ClawHub skill marketplace
    │
2026.01 ─── Moltbook (1.5M agents / 72h) ─── Academic paper boom (6 papers / 2 weeks)
    │
2026.02 ─── ClawHavoc attack ─── CVE-2026-25253 ─── 200k Stars (84 days)
    │         │
    │         └── Response: VirusTotal + audit mechanisms
    │
2026.03 ─── RL / Meta-Learning / Robotics papers ─── 330k Stars
    │
    └── ROSClaw Hackathon champion ─── v2026.3.13-1 (68th release)
              │
              └── WeChat official ClawBot plugin (03.22)
                    │
                    └── National Cybersecurity Advisory (China, 03.13)
```

<details>
<summary><b>Full timeline</b></summary>

| Date | Event |
|------|-------|
| 2025.11.24 | OpenClaw (formerly ClawdBot / Moltbot) launched |
| 2025.12 | ClawHub skill marketplace released |
| 2026.01 | Moltbook launched — 1.5M agents registered in 72h |
| 2026.01 | 6 academic papers produced in 2 weeks |
| 2026.02.02 | Risky Sharing & Norm Enforcement paper |
| 2026.02 | PASB security evaluation paper |
| 2026.02 | ClawHavoc supply chain attack — 1,184 malicious skills |
| 2026.02 | CVE-2026-25253 disclosed (RCE, CVSS 8.8) |
| 2026.02.16 | GitHub Stars crossed 200k (84 days) |
| 2026.02 | OpenClaw + VirusTotal security partnership |
| 2026.03 | OpenClaw-RL / MetaClaw / AgentOS / RoboClaw papers |
| 2026.03 | ROSClaw won SF OpenClaw Hackathon |
| 2026.03.13 | v2026.3.13-1 released (68th release) |
| 2026.03.13 | China National Cybersecurity Advisory |
| 2026.03.22 | WeChat official ClawBot plugin released |
| 2026.03 | GitHub Stars crossed 330k |

</details>

---

## 📦 Other Resources

<details>
<summary><b>Official Links</b></summary>

| Name | Link |
|------|------|
| OpenClaw Core | [github.com/openclaw/openclaw](https://github.com/openclaw/openclaw) |
| ClawHub Marketplace | [clawhub.com](https://clawhub.com) |
| Official Docs | [docs.openclaw.ai](https://docs.openclaw.ai) |

</details>

<details>
<summary><b>SDKs & Tools</b></summary>

| Name | Language | Description |
|------|----------|-------------|
| [openclaw-sdk](https://masteryodaa.github.io/openclaw-sdk/) | Python | Build & publish autonomous AI agents |
| [mcp-bridge-openclaw](https://www.npmjs.com/package/mcp-bridge-openclaw) | TypeScript | MCP multi-server bridge |
| [amor71/openclaw-mcp](https://github.com/amor71/openclaw-mcp) | TypeScript | Native MCP client |
| [henry-y/openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) | Python | OpenClaw arXiv paper reader |

</details>

<details>
<summary><b>Security References</b></summary>

| Name | Link |
|------|------|
| PASB Framework | [GitHub](https://github.com/AstorYH/PASB) |
| SkillFortify | [GitHub](https://github.com/qualixar/skillfortify) · [PyPI](https://pypi.org/project/skillfortify/) |
| CVE-2026-25253 | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-25253) |
| Security Guide | [bitdoze.com](https://www.bitdoze.com/openclaw-security-guide/) |

</details>

<details>
<summary><b>Chinese Community / 中文社区</b></summary>

| Name | Link | Description |
|------|------|-------------|
| OpenClaw China | [BytePioneer-AI/openclaw-china](https://github.com/BytePioneer-AI/moltbot-china) | Domestic IM adaption (3,200+ Stars) |
| 中文社区 | [clawd.org.cn](https://clawd.org.cn) | Feishu / DingTalk / WeCom / QQ |
| 中文教程 | [openclawgithub.cc](https://openclawgithub.cc) | Config & integration guides |
| Hello Claw | [Datawhale](https://datawhalechina.github.io/hello-claw/) | Datawhale tutorial |
| 中文站 | [clawcn.net](https://clawcn.net) | Domestic LLM guide |
| Learn OpenClaw | [learnopenclaw.com](https://learnopenclaw.com) | Learning platform |

</details>

<details>
<summary><b>Related Repositories</b></summary>

> Know a great OpenClaw project we missed? Open a PR and help us keep this list growing!

| Repository | Stars | Description |
|------------|-------|-------------|
| [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) | 823 | Comprehensive list of OpenClaw resources, tools, skills, tutorials & articles |
| [mergisi/awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) | 830+ | 177 production-ready AI agent templates across 24 categories |
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | — | Community curated skills collection |
| [community/openclaw-recipes](https://github.com/community/openclaw-recipes) | — | Common automation recipes |
| [templates/claw-templates](https://github.com/templates/claw-templates) | — | Starter templates for OpenClaw projects |
| [pranciskus/discourse-openclaw](https://github.com/pranciskus/discourse-openclaw) | NEW | Discourse forum integration with 12 tools |
| [wanikua/ByeByeClaw](https://github.com/wanikua/byebyeclaw) | NEW | One-command uninstaller for all Claw-family agents |

</details>

---

## 🤝 Contributing

Contributions are welcome! We especially need help with:

- **Papers** — Adding missing OpenClaw-related papers with proper links
- **Analysis** — Improving paper notes and highlights
- **Timeline** — Updating the ecosystem timeline with new events
- **Translation** — Translating content between English and Chinese

Please submit via [Pull Request](https://github.com/shuolucs/Awesome-OpenClaw-Research/pulls). See [README_CN.md](./README_CN.md) for the Chinese version.

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=shuolucs/Awesome-OpenClaw-Research&type=Date)](https://star-history.com/#shuolucs/Awesome-OpenClaw-Research&Date)
