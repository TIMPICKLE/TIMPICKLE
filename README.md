<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:667eea,100:764ba2&amp;height=200&amp;section=header&amp;text=Nihao%20Dong&amp;fontSize=50&amp;fontColor=ffffff&amp;animation=fadeIn&amp;fontAlignY=38&amp;desc=AI%20Engineer%20%7C%20Agent%20Harnesses%20%7C%20DevOps%20Automation&amp;descSize=16&amp;descAlignY=58&amp;descAlign=50" width="100%" alt="Nihao Dong — AI Engineer, Agent Harnesses, DevOps Automation"/>
</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=667EEA&center=true&vCenter=true&repeat=true&width=620&height=45&lines=Building+Verifiable+Agent+Workflows;From+Medical+Software+to+Agent+Engineering;Engineering+Harnesses+for+Reliable+Agents)](https://git.io/typing-svg)

</div>

<div align="center">

[Projects](#selected-projects) · [Writing](#recent-blog-posts) · [Experience](#experience) · [CSDN Blog](https://blog.csdn.net/dongnihao)

</div>

---

## 🧑‍💻 About Me

```yaml
name: Nihao Dong
location: Shanghai, China
company: United Imaging Medical Technology
role: AI Efficiency Program Team
prev_role: Full Stack Engineer @ WebOIS
focus: Agent Engineering | Agent Harnesses | DevOps Automation
blog: https://blog.csdn.net/dongnihao
```

I build agents for software engineering workflows. My recent work focuses on the harness around the model: orchestration, tools, context, permission boundaries, failure handling, and verifiable outcomes.

I started in full-stack medical software development with C# / .NET and Angular. Today, I work on AI engineering and developer tooling, connecting coding agents to existing DevOps systems and turning project-specific workflows into reusable components.

---

## 🔭 Current Focus

- 🤖 **Agent harnesses:** separate workflow control from model reasoning, define tool permissions, and check completion against facts and external state
- ⚙️ **DevOps automation:** connect Azure DevOps work items and SonarQube issues to planning, code changes, validation, and reviewable pull requests
- 🧩 **Reusable agent components:** assemble business payloads on a shared runtime, inject versioned knowledge at lifecycle events, and package existing roles as reproducible recipes
- 🔎 **Verification and observability:** record task traces, tool calls, failure details, and acceptance evidence so results can be inspected and regressions tested

---

<a id="selected-projects"></a>

## 🚀 Selected Projects

### [devops-agent-chassis](https://github.com/TIMPICKLE/devops-agent-chassis)

A reusable engineering foundation for DevOps agents, organized around orchestration, connectors, knowledge injection, failure contracts, and observability.

- Python standard-library core with separate business payloads and optional model / MCP integrations
- Objective `DoneCriteria`, explicit tool-entry permission checks, and registered failure-cleanup callbacks
- Versioned Azure CodeAgent and SonarQube role recipes with configuration checks, per-project instances, and file-digest checks
- Runtime evidence, opt-in parallel execution of declared-independent ReAct tools, and OpenAI / Anthropic-compatible model adapters

[Architecture](https://github.com/TIMPICKLE/devops-agent-chassis/blob/main/docs/ARCHITECTURE.md) · [Role recipes](https://github.com/TIMPICKLE/devops-agent-chassis/blob/main/docs/ROLE_RECIPES.md) · [Current capabilities and limits](https://github.com/TIMPICKLE/devops-agent-chassis/blob/main/roadmap/CURRENT_STATE.md)

<details>
<summary>Verification snapshot · September 2026</summary>

The [September 16 implementation record](https://github.com/TIMPICKLE/devops-agent-chassis/blob/main/changelog/role-recipes-2026-09-16.md) reports **418 passed / 1 skipped** in local regression tests. The [role-recipe CI run](https://github.com/TIMPICKLE/devops-agent-chassis/actions/runs/35044157900) passed Python 3.9 / 3.13 recipe checks and offline reuse checks for existing roles.

These checks cover the documented regression and offline integration scope. Enterprise live acceptance and measured productivity gains remain open work.

</details>

### [AzureCodeAgent · Chassis-based implementation](https://github.com/TIMPICKLE/AzureCodeAgent_Base_Agent_chassis)

A controlled coding-agent workflow triggered by Azure DevOps work-item comments. It assembles task intake, planning, Claude Code execution, local checks, and configurable PR delivery on the shared chassis. Business-specific completion criteria and delivery logic stay in the application layer.

### [SonarQube AutoFlow · Microsoft Agent Framework](https://github.com/TIMPICKLE/SonarqubeAutoFlow_MAF)

A code-smell remediation workflow connecting SonarQube, Claude Code, and Azure DevOps through MCP. The project explores a deterministic outer workflow with an agent-driven repair step, and documents the migration from LangGraph to Microsoft Agent Framework.

### [NMPA Computer Use Agent](https://github.com/TIMPICKLE/nmpa-computer-use-agent)

An experimental Windows browser agent for retrieving public medical-device registration information through screenshots and mouse / keyboard actions. Includes action logs, screenshot history, repeated-action detection, and recovery handling.

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**AI / Agent Engineering**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Microsoft Agent Framework](https://img.shields.io/badge/Microsoft_Agent_Framework-0078D4?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-667EEA?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white)

**Frameworks & Tools**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)

**Patterns:** ReAct · Plan-and-Execute · RAG

**Also:** ASP.NET Core · ABP Framework · GitHub Copilot

</div>

---

<a id="experience"></a>

## 💼 Experience

**United Imaging Medical Technology**

```text
2024.12 – Present  ·  AI Efficiency Program Team
  ├─ Agent Architecture & Harness Engineering
  ├─ GitHub Copilot Enterprise Administration & Rollout
  ├─ MCP Development
  └─ AI Tooling

2021.12 – 2024.12  ·  Full Stack Engineer · WebOIS
  ├─ C# / ASP.NET Core / ABP Framework
  ├─ Angular / TypeScript
  └─ HL7 / DICOM Medical Protocol Integration
```

---

## 🎓 Education

| Degree | University | Period | Result |
| --- | --- | --- | --- |
| 🎓 MSc Advanced Computer Science | University of Liverpool | 2020–2021 | Merit |
| 🎓 BSc Computing Science | Staffordshire University | 2017–2020 | Upper Second |

---

<a id="recent-blog-posts"></a>

## 📝 Recent Blog Posts

I write in Chinese about agent architecture, harness engineering, evaluation, and practical implementation.

| Published | Article |
| --- | --- |
| 2026-09-04 | [Agent 的未来属于 Harness，而不只是更强的模型](https://timpickle.blog.csdn.net/article/details/164369841) |
| 2026-08-12 | [AI 智能体评测解密：如何为 Agent 构建可靠、可演进的评测体系](https://timpickle.blog.csdn.net/article/details/163698527) |
| 2026-07-23 | [从 Anthropic 的 harness 文章回看 Pi：它真正缺的是什么，真正强的又是什么](https://timpickle.blog.csdn.net/article/details/163139729) |
| 2026-07-13 | [流程是地板，不是天花板--从 Harness 工程看企业内部项目的架构选择](https://timpickle.blog.csdn.net/article/details/162850123) |
| 2026-06-29 | [从 Claude Code 放弃 RAG 说起：实际项目中如何合理创建知识库](https://timpickle.blog.csdn.net/article/details/162427851) |

<div align="center">

[![CSDN Blog](https://img.shields.io/badge/CSDN_Blog-Read_More-FC5531?style=for-the-badge)](https://blog.csdn.net/dongnihao)

</div>

---

## 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=TIMPICKLE&amp;theme=tokyonight&amp;hide_border=true&amp;background=0D1117" alt="GitHub Streak"/>
</div>

---

## 🏈 Life Beyond Code

<div align="center">

`🏈 American Football (Stingers)` · `🏀 Basketball` · `🎮 PS5 / NS` · `☕ Iced Americano (no sugar)` · `💆 Friday Massage Ritual`

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=TIMPICKLE&amp;color=667eea&amp;style=flat-square&amp;label=Profile+Views" alt="Profile Views"/>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:667eea,100:764ba2&amp;height=120&amp;section=footer" width="100%" alt="Purple gradient wave footer"/>
