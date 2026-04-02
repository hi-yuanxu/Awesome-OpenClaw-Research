# Awesome-OpenClaw-Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![](assets/banner.gif)

🦞 **OpenClaw** 于 2025 年 11 月上线，**84 天**突破 20 万 GitHub 星标，截至 2026 年 3 月已超过 **33 万星**。本仓库收集**围绕 OpenClaw 生态展开的研究论文** —— 涵盖 Agent 基础设施、学习与进化、安全、具身智能、社会动力学与领域应用。问题是通用的，OpenClaw 是观察窗口。

<p align="center">
  <a href="#-论文"><img src="https://img.shields.io/badge/论文-25%2B-blue?style=flat-square" alt="Papers"></a>
  <a href="https://github.com/openclaw/openclaw"><img src="https://img.shields.io/badge/OpenClaw-330k%2B%20Stars-yellow?style=flat-square" alt="Stars"></a>
  <a href="./README.md"><img src="https://img.shields.io/badge/English-README-orange?style=flat-square" alt="English"></a>
  <a href="./README_KR.md"><img src="https://img.shields.io/badge/한국어-문서-orange?style=flat-square" alt="한국어"></a>
  <a href="./README_JP.md"><img src="https://img.shields.io/badge/日本語-ドキュメント-orange?style=flat-square" alt="日本語"></a>
  <a href="#-贡献指南"><img src="https://img.shields.io/badge/PRs-欢迎-brightgreen?style=flat-square" alt="PRs Welcome"></a>
  <a href="https://join.slack.com/t/openclaw-research/shared_invite/zt-3tetckn5x-tOKVsEEQN8ArnyxzqgWsAA"><img src="https://img.shields.io/badge/Slack-加入讨论-4A154B?style=flat-square&logo=slack" alt="Slack"></a>
</p>

---

## 目录

- [论文](#-论文) — **本仓库核心**
  - [基础设施与系统](#基础设施与系统)
  - [学习与进化](#学习与进化)
  - [安全与信任](#安全与信任)
  - [具身智能](#具身智能)
  - [Agent 社会](#agent-社会)
  - [领域应用](#领域应用)
- [架构](#-架构)
- [生态时间线](#-生态时间线)
- [其他资源](#-其他资源) — SDK、工具、社区、相关仓库
- [贡献指南](#-贡献指南)

---

## 📄 论文

> 仅 2026 年 2-3 月就发表 25+ 篇论文。每条记录包含论文链接、代码链接（如有）及核心要点。

### 基础设施与系统

> 框架、OS 范式、评测基准与协议评估。

| 标题 | 来源 | 日期 | 论文 | 代码 | 要点 |
|------|------|------|------|------|------|
| **OpenClaw as Language Infrastructure (Survey)** | Preprints.org | 2026.03 | [![Preprints](https://img.shields.io/badge/202603.1060-b31b1b?style=flat-square)](https://www.preprints.org/manuscript/202603.1060) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | GATE / AERO 框架；分析 38 篇生态论文 |
| **AgentOS: NL-Driven OS Paradigm** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.08938-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.08938) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 以 Agent 为中心的 OS 范式；Skills-as-Modules；KDD 建模 |
| **EvoClaw: Evaluating AI Agents on Continuous Software Evolution** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.13428-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.13428) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/Hydrapse/EvoClaw) [![HuggingFace](https://img.shields.io/badge/Dataset-FFD21E?style=flat-square&logo=huggingface&logoColor=000)](https://huggingface.co/datasets/hyd2apse/EvoClaw-data) | DeepCommit 里程碑 DAG；7 仓库 / 5 语言；最强 Agent 连续场景仅 38% |
| **MCP-Atlas: Large-Scale Benchmark for MCP Tool-Use** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.00933-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.00933) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 36 个 MCP 服务器；220 个工具；1,000 个任务；多步工作流评估 |

### 学习与进化

> 强化学习、元学习与 Agent 自我提升。

| 标题 | 来源 | 日期 | 论文 | 代码 | 要点 |
|------|------|------|------|------|------|
| **OpenClaw-RL: Train Any Agent Simply by Talking** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.10165) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/Gen-Verse/OpenClaw-RL) | 评估+指导信号；异步四组件 RL 架构；个性化分数 0.17→0.81 |
| **MetaClaw: Meta-Learning in the Wild** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.17187-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.17187) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 持续元学习；技能驱动适应；准确率 21.4% → 40.6% |

### 安全与可信

> 攻击基准、防御框架、供应链安全与运行时防护。

| 标题 | 来源 | 日期 | 论文 | 代码 | 要点 |
|------|------|------|------|------|------|
| **PASB: Benchmarking Attacks on OpenClaw** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.08412-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.08412) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/AstorYH/PASB) | 端到端安全评估；原生防御率仅 17% |
| **A Trajectory-Based Safety Audit of Clawdbot (OpenClaw)** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.14364-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.14364) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/tychenn/clawdbot_report) | 34 测试用例 / 6 风险维度；总体通过率 58.9%；意图误解场景通过率 0% |
| **SkillFortify: Formal Supply Chain Security** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.00195-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.00195) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/qualixar/skillfortify) [![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi)](https://pypi.org/project/skillfortify/) | Dolev-Yao 建模；96.95% F1；0% 假阳性；支持 22 个框架 |
| **Don't Let the Claw Grip Your Hand** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.10387-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.10387) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 47 种对抗场景；MITRE ATLAS/ATT&CK；HITL 防御：17% → 19-92% |
| **OpenClaw PRISM: Runtime Security Layer** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11853-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11853) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 纵深防御；零分叉；防提示注入 |
| **Uncovering Security Threats & Architecting Defenses (FASA)** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.12644-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.12644) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 清华 & 蚂蚁集团；三层风险分类法；FASA + ClawGuard；26% 社区工具存在漏洞 |
| **Defensible Design for OpenClaw** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.13151-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.13151) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 安全即工程蓝图；风险分类法；实用研究议程 |

### 具身智能

> 机器人、物理实体化与 ROS 集成。

| 标题 | 来源 | 日期 | 论文 | 代码 | 要点 |
|------|------|------|------|------|------|
| **RoboClaw: Agentic Framework for Robotic Tasks** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11558-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11558) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MINT-SJTU/RoboClaw) | VLA 模型；纠缠动作对；成功率 +25%；人力 −53.7% |
| **ROSClaw: Bridging OpenClaw with ROS 2** | GitHub | 2026.03 | [![Blog](https://img.shields.io/badge/Blog-4CAF50?style=flat-square)](https://openclaws.io/blog/openclaw-robotics-embodied-ai) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/PlaiPin/rosclaw) | SF Hackathon 冠军；Unitree G1/H1、DJI；可在 RPi4 运行 |
| **RoClaw: Physical Embodiment for OpenClaw** | GitHub | 2026.03 | [![Blog](https://img.shields.io/badge/Blog-4CAF50?style=flat-square)](https://evoailabs.medium.com/the-rapid-transformation-of-openclaw-into-a-physical-ai-powerhouse-911d8546c1c0) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/EvolvingAgentsLabs/RoClaw) | 双脑字节码架构；体感固件；开源硬件 CAD 与仿真环境 |

### Agent 社会

> Agent 群体中的社会行为、涌现规范、同伴学习与集体动力学。

| 标题 | 来源 | 日期 | 论文 | 代码 | 要点 |
|------|------|------|------|------|------|
| **Risky Sharing & Norm Enforcement** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.02625-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.02625) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 3.9 万帖子 / 1.45 万 Agent；18.4% 含行动诱导语言；涌现规范执行 |
| **Peer Learning in the Moltbook Community** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.14477-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.14477) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 240 万 Agent 的同伴学习模式 |
| **OpenClaw Agents as Informal Learners at Moltbook** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.18832-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.18832) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 280 万 Agent 的非正式学习行为 |
| **From Agent-Only Social Networks to Autonomous Research** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.19810-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.19810) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | OpenClaw → Moltbook → ClawdLab；Sybil 抵抗；5 种架构模式 |
| **When OpenClaw Agents Learn from Each Other** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.16663-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.16663) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 16.7 万 Agent；双向脚手架效应；涌现同伴学习；AIED 启示 |

### 领域应用

> 垂直领域应用：医疗、教育、科学发现、个性化 Agent 等。

| 标题 | 来源 | 日期 | 论文 | 代码 | 要点 |
|------|------|------|------|------|------|
| **Toward Personalized LLM-Powered Agents** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.22680-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.22680) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 四大组件：Profile / Memory / Planning / Action |
| **When OpenClaw Meets Hospital: Agentic OS for Clinical Workflows** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11721-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11721) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | 受限执行环境；文档中心交互；页面索引记忆；医学技能库 |
| **EduClaw: Scaling Laws for Educational AI Agents** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11709-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11709) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | Agent 缩放定律；AgentProfile 框架；330+ 配置 & 1,100+ 技能模块覆盖 K-12 |
| **ScienceClaw + INFINITE: Autonomous Agents Coordinating Distributed Discovery** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.14312-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.14312) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/lamm-mit/scienceclaw) | MIT LAMM；300+ 科学技能；ArtifactReactor；肽设计 / 陶瓷筛选 / 跨领域 |

---

## 🏗 架构

```mermaid
flowchart LR
    subgraph Channels["📱 渠道"]
        direction TB
        C1[WhatsApp] ~~~ C2[Telegram] ~~~ C3[Discord] ~~~ C4[Slack] ~~~ C5["50+"]
    end

    subgraph Core["⚙️ 核心"]
        direction TB
        Router[消息路由] --> Kernel[Agent 内核]
        Kernel <--> LLM["LLM 后端\nClaude / GPT / Ollama"]
    end

    subgraph Memory["🧠 记忆"]
        direction TB
        M1[会话上下文] ~~~ M2[每日笔记] ~~~ M3[长期记忆] ~~~ M4[语义搜索]
    end

    subgraph Extensions["🔌 扩展"]
        direction TB
        E1["Skills (5,700+)"] ~~~ E2["MCP (3,200+)"] ~~~ E3[插件]
    end

    subgraph External["🌐 外部"]
        direction TB
        X1[Moltbook] ~~~ X2[ROSClaw] ~~~ X3[RoboClaw]
    end

    Channels --> Core
    Core <--> Memory
    Core <--> Extensions
    Extensions --> External
```

---

## 📅 生态时间线

```
2025.11 ─── 上线 (ClawdBot / Moltbot → OpenClaw)
    │
2025.12 ─── ClawHub 技能市场
    │
2026.01 ─── Moltbook (150万Agent/72h) ─── 学术论文爆发 (6篇/2周)
    │
2026.02 ─── ClawHavoc 攻击 ─── CVE-2026-25253 ─── 200k Stars (84天)
    │         │
    │         └── 安全响应: VirusTotal + 审核机制
    │
2026.03 ─── RL/元学习/机器人论文密集期 ─── 330k Stars
    │
    └── ROSClaw Hackathon 冠军 ─── v2026.3.13-1 (第68版)
              │
              └── 微信官方 ClawBot 插件 (03.22)
                    │
                    └── 国家网络安全通报中心预警 (03.13)
```

<details>
<summary><b>完整时间线</b></summary>

| 日期 | 事件 |
|------|------|
| 2025.11.24 | OpenClaw（原 ClawdBot / Moltbot）上线 |
| 2025.12 | ClawHub 技能市场发布 |
| 2026.01 | Moltbook 上线 — 72h 内注册 150 万 Agent |
| 2026.01 | 两周内产出 6 篇学术论文 |
| 2026.02.02 | Risky Sharing & Norm Enforcement 论文发表 |
| 2026.02 | PASB 安全评估框架论文发表 |
| 2026.02 | ClawHavoc 供应链攻击 — 1,184 个恶意技能 |
| 2026.02 | CVE-2026-25253 披露（RCE，CVSS 8.8） |
| 2026.02.16 | GitHub Stars 突破 200k（84 天） |
| 2026.02 | OpenClaw + VirusTotal 安全合作 |
| 2026.03 | OpenClaw-RL / MetaClaw / AgentOS / RoboClaw 等论文发表 |
| 2026.03 | ROSClaw 赢得 SF OpenClaw Hackathon |
| 2026.03.13 | v2026.3.13-1 发布（第 68 版） |
| 2026.03.13 | 国家网络安全通报中心安全预警 |
| 2026.03.22 | 微信官方 ClawBot 插件发布 |
| 2026.03 | GitHub Stars 突破 330k |

</details>

---

## 📦 其他资源

<details>
<summary><b>官方链接</b></summary>

| 名称 | 链接 |
|------|------|
| OpenClaw 核心 | [github.com/openclaw/openclaw](https://github.com/openclaw/openclaw) |
| ClawHub 市场 | [clawhub.com](https://clawhub.com) |
| 官方文档 | [docs.openclaw.ai](https://docs.openclaw.ai) |

</details>

<details>
<summary><b>SDK 与工具</b></summary>

| 名称 | 语言 | 说明 |
|------|------|------|
| [openclaw-sdk](https://masteryodaa.github.io/openclaw-sdk/) | Python | 构建与发布 AI Agent |
| [mcp-bridge-openclaw](https://www.npmjs.com/package/mcp-bridge-openclaw) | TypeScript | MCP 多服务器桥接 |
| [amor71/openclaw-mcp](https://github.com/amor71/openclaw-mcp) | TypeScript | 原生 MCP 客户端 |
| [henry-y/openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) | Python | OpenClaw arXiv 论文阅读助手 |

</details>

<details>
<summary><b>自动化科研工具</b></summary>

| 名称 | 链接 | 说明 |
|------|------|------|
| AutoResearchClaw | [GitHub](https://github.com/aiming-lab/AutoResearchClaw) | 全自动 23 阶段科研流水线：idea → 实验 → 会议论文；含多 Agent 同行评审 |
| OpenClaw-Medical-Skills | [GitHub](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | 869 个医疗 AI Skill，覆盖临床、基因组学、药物发现与生物信息学 |
| ScienceClaw | [GitHub](https://github.com/Zaoqu-Liu/ScienceClaw) | 自主科研流水线；266+ 领域技能；77+ 数据库 |
| ClawCures | [GitHub](https://github.com/agentcures/ClawCures) | 药物发现 AI 编排器；规划/批评循环；ADMET 属性图 |

</details>

<details>
<summary><b>安全参考</b></summary>

| 名称 | 链接 |
|------|------|
| PASB 框架 | [GitHub](https://github.com/AstorYH/PASB) |
| SkillFortify | [GitHub](https://github.com/qualixar/skillfortify) · [PyPI](https://pypi.org/project/skillfortify/) |
| SecureClaw | [GitHub](https://github.com/adversa-ai/secureclaw) |
| SlowMist 安全指南 | [GitHub](https://github.com/slowmist/openclaw-security-practice-guide) |
| CVE-2026-25253 | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-25253) |
| 安全指南 | [bitdoze.com](https://www.bitdoze.com/openclaw-security-guide/) |

</details>

<details>
<summary><b>评测基准</b></summary>

| 名称 | 链接 | 说明 |
|------|------|------|
| PinchBench | [pinchbench.com](https://pinchbench.com) · [GitHub](https://github.com/pinchbench/skill) | 23 个真实世界任务，覆盖 8 个类别；自动 + LLM 裁判评分 |
| EvoClaw | [evo-claw.com](https://evo-claw.com) · [HuggingFace](https://huggingface.co/datasets/hyd2apse/EvoClaw-data) | 持续软件演化基准；7 仓库 / 5 语言 / 98 里程碑 |

</details>

<details>
<summary><b>中文社区</b></summary>

| 名称 | 链接 | 说明 |
|------|------|------|
| OpenClaw China | [BytePioneer-AI/openclaw-china](https://github.com/BytePioneer-AI/moltbot-china) | 国内 IM 平台适配（3,200+ Stars） |
| 中文社区 | [clawd.org.cn](https://clawd.org.cn) | 飞书 / 钉钉 / 企微 / QQ |
| 中文教程 | [openclawgithub.cc](https://openclawgithub.cc) | 配置与接入指南 |
| Hello Claw | [Datawhale](https://datawhalechina.github.io/hello-claw/) | Datawhale tutorial |
| 中文站 | [clawcn.net](https://clawcn.net) | 国产大模型指南 |
| Learn OpenClaw | [learnopenclaw.com](https://learnopenclaw.com) | 学习平台 |

</details>

<details>
<summary><b>相关仓库</b></summary>

> 发现了我们遗漏的好项目？欢迎提交 PR 帮助完善这份清单！

| 仓库 | Stars | 说明 |
|------|-------|------|
| [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) | 823 | OpenClaw 资源、工具、技能、教程与文章大全 |
| [mergisi/awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) | 830+ | 177 个生产级 AI Agent 模板，覆盖 24 个领域 |
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | — | 社区精选技能合集 |
| [community/openclaw-recipes](https://github.com/community/openclaw-recipes) | — | 常用自动化配方 |
| [templates/claw-templates](https://github.com/templates/claw-templates) | — | OpenClaw 项目模板 |
| [pranciskus/discourse-openclaw](https://github.com/pranciskus/discourse-openclaw) | NEW | Discourse 论坛集成，12 个工具 |
| [wanikua/ByeByeClaw](https://github.com/wanikua/byebyeclaw) | NEW | 一键卸载所有 Claw 系列 Agent |

</details>

---

## 🤝 贡献指南

欢迎贡献！特别是以下方面：

- **论文** — 补充遗漏的 OpenClaw 相关论文，附带完整链接
- **分析** — 完善论文笔记与要点
- **时间线** — 更新生态时间线
- **翻译** — 中英文内容互译

请通过 [Pull Request](https://github.com/shuolucs/Awesome-OpenClaw-Research/pulls) 提交。英文版请查看 [README.md](./README.md)。

---

## ⭐ Star History

如果这个项目对你有帮助，请给个 Star！

[![Star History Chart](https://api.star-history.com/svg?repos=shuolucs/Awesome-OpenClaw-Research&type=Date)](https://star-history.com/#shuolucs/Awesome-OpenClaw-Research&Date)
