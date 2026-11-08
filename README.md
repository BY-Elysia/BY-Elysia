# Yang Bai · 白洋

**AI Agents · Large Language Models · Multimodal AI**

Incoming PhD student at the **School of Artificial Intelligence, Zhejiang University**, admitted directly to the doctoral program through the recommendation-based admission pathway; affiliated with **GIVE Lab**.

I am currently pursuing dual degrees in **Intelligent Science and Technology** and **Mathematics and Applied Mathematics** at Chongqing University of Posts and Telecommunications.

I build agent systems and LLM-powered applications, with interests in tool use, agent runtimes, multimodal learning, and reliable evaluation. I welcome **open-source collaboration and academic exchange** around these topics.

[中文介绍](#中文介绍) · [Projects](https://github.com/BY-Elysia?tab=repositories)

## Selected projects

| Project | Focus | Engineering highlights |
| --- | --- | --- |
| **[Aemeath Agent](https://github.com/BY-Elysia/Aemeath-agent)** | Agent runtime & tool integration | A shared Python harness for shell, HTTP, and Feishu entry points, with modular capabilities, Agent Skills, persistent sessions, confirmation flows, and audit logs. |
| **[Parallelization Agent Framework](https://github.com/BY-Elysia/parallelization-agent-framework)** | Verified code transformation | A model-agnostic CLI and MCP workflow combining isolated rewrites, differential verification, resource-bounded benchmarks, and explicit acceptance policies. |
| **[Xiye · 析页](https://github.com/BY-Elysia/question_bank_auto)** | AI document processing | Converts textbooks into structured question banks with cross-page extraction, source-linked review, resumable tasks, and human approval of generated answers. Built with TypeScript, React, NestJS, Zod, and Docker. |
| **[MLLM](https://github.com/BY-Elysia/MLLM)** | Multimodal training | Configurable CLIP and BLIP-2 training pipelines, including image–text data preparation, stage-specific objectives, and checkpoint management. |
| **[Paper Reading Skills](https://github.com/BY-Elysia/Paper-read-skills)** | Research workflows for agents | A reusable skill for reading LLM and multimodal papers, with structured analysis of architectures, training objectives, experiments, and supporting figures. |

## Experience & evaluation

- **Applied multimodal AI:** led an AI-assisted grading platform project spanning question extraction, structured question banks, AI grading, teacher review, and teaching assistance. The platform served **36 classes, 22 teachers, and approximately 2,500 students**.

- **AI product delivery:** Xiye connects model calls to typed output contracts, review workflows, recovery checkpoints, and browser-level regression checks. [Architecture](https://github.com/BY-Elysia/question_bank_auto/blob/main/docs/architecture.md)
- **Correctness before speed:** the parallelization framework preserves a fixed reference implementation and checks candidate behavior before benchmarking. Its published validation reports a **2.00× median speedup** for one fixed `chardet` workload with 4 workers; this is a workload-specific result. [Validation evidence](https://github.com/BY-Elysia/parallelization-agent-framework/blob/main/validation/README.md)
- **Experimental discipline:** recommendation work records retained approaches, unsuccessful directions, and reproduction steps. [RecSys experiments](https://github.com/BY-Elysia/RecSys-Challenge-2026/blob/main/EXPERIMENTS.md) · [TAAC retrospective](https://github.com/BY-Elysia/TAAC-2026)

**Selected honors:** National Scholarship (2025) · Kaggle NeuroGolf Championship 2026 bronze medal (229/2,963) · 10th place, 5th Jittor AI Challenge.

**Working stack:** Python · PyTorch · TypeScript · React · NestJS · FastAPI · SQLite · Docker · MCP

**More work:** [UNet + GoogLeNet ultrasound image pipeline](https://github.com/BY-Elysia/UNet-GooLeNet) · [Paper reading skill](https://github.com/BY-Elysia/Paper-read-skills)

## Collaboration

I am interested in collaborating on agent runtimes and tool integration, LLM-powered workflows, multimodal training, and reproducible evaluation. Project Issues are welcome for technical discussion, reproduction questions, and concrete collaboration proposals.

## 中文介绍

我叫**白洋**，目前就读于**重庆邮电大学智能科学与技术、数学与应用数学双学位**，已**保研直博至浙江大学人工智能学院，隶属 GIVE Lab**。

我主要关注 **Agent 与 LLM**，希望围绕智能体系统、大模型应用、多模态学习和可复现评估开展**开源合作与学术交流**。

### 主要实践

- **Agent 系统：** Aemeath Agent 通过统一运行时连接 Shell、HTTP 与飞书，支持工具能力装配、会话持久化、操作确认和审计。
- **Coding Agent 验证：** 代码并行化框架通过隔离改写、差分验证和受资源约束的基准测试，判断候选方案是否值得采用。
- **LLM 应用：** 析页覆盖教材跨页识题、结构化抽取、来源追溯、人工校对与任务恢复；另曾负责多模态 AI 智能批改平台，服务 36 个班级、22 名教师、约 2,500 名学生。
- **多模态与科研工具：** 实践 CLIP / BLIP-2 训练链路，并将大模型论文阅读流程整理为可复用的 Agent Skill。

**部分荣誉：** 2025 年国家奖学金；Kaggle 2026 NeuroGolf Championship 铜牌（229/2963）；第五届计图人工智能挑战赛全国第十名。

欢迎通过项目 Issues 交流 Agent 架构、工具调用、大模型应用、多模态训练与实验复现，也欢迎围绕具体问题发起合作。
