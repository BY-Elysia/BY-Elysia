# BY-Elysia

**AI Engineering · Agent Systems · Multimodal Learning**

I build AI applications and experiment with the models behind them—from agent runtimes and document workflows to multimodal training and recommendation systems.

My work emphasizes explicit interfaces, reproducible experiments, and validation that connects implementation choices to observable results.

[中文介绍](#中文介绍) · [Projects](https://github.com/BY-Elysia?tab=repositories)

## Selected projects

| Project | Focus | Engineering highlights |
| --- | --- | --- |
| **[Xiye · 析页](https://github.com/BY-Elysia/question_bank_auto)** | AI document processing | Converts textbooks into structured question banks with cross-page extraction, source-linked review, resumable tasks, and human approval of generated answers. Built with TypeScript, React, NestJS, Zod, and Docker. |
| **[Aemeath Agent](https://github.com/BY-Elysia/Aemeath-agent)** | Agent runtime & tool integration | A shared Python harness for shell, HTTP, and Feishu entry points, with modular capabilities, Agent Skills, persistent sessions, confirmation flows, and audit logs. |
| **[Parallelization Agent Framework](https://github.com/BY-Elysia/parallelization-agent-framework)** | Verified code transformation | A model-agnostic CLI and MCP workflow combining isolated rewrites, differential verification, resource-bounded benchmarks, and explicit acceptance policies. |
| **[MLLM](https://github.com/BY-Elysia/MLLM)** | Multimodal training | Configurable CLIP and BLIP-2 training pipelines, including image–text data preparation, stage-specific objectives, and checkpoint management. |
| **[RecSys Challenge 2026](https://github.com/BY-Elysia/RecSys-Challenge-2026)** | Conversational recommendation | Multi-channel retrieval with BM25, SigLIP2, and a Qwen3 query adapter, followed by LambdaRank ranking and documented experiments. |

## Implementation & evaluation

- **AI product delivery:** Xiye connects model calls to typed output contracts, review workflows, recovery checkpoints, and browser-level regression checks. [Architecture](https://github.com/BY-Elysia/question_bank_auto/blob/main/docs/architecture.md)
- **Correctness before speed:** the parallelization framework preserves a fixed reference implementation and checks candidate behavior before benchmarking. Its published validation reports a **2.00× median speedup** for one fixed `chardet` workload with 4 workers; this is a workload-specific result. [Validation evidence](https://github.com/BY-Elysia/parallelization-agent-framework/blob/main/validation/README.md)
- **Experimental discipline:** recommendation work records retained approaches, unsuccessful directions, and reproduction steps. [RecSys experiments](https://github.com/BY-Elysia/RecSys-Challenge-2026/blob/main/EXPERIMENTS.md) · [TAAC retrospective](https://github.com/BY-Elysia/TAAC-2026)

**Working stack:** Python · PyTorch · TypeScript · React · NestJS · FastAPI · SQLite · Docker · MCP

**More work:** [UNet + GoogLeNet ultrasound image pipeline](https://github.com/BY-Elysia/UNet-GooLeNet) · [Paper reading skill](https://github.com/BY-Elysia/Paper-read-skills)

## 中文介绍

我关注 **AI 应用工程、Agent 系统、多模态学习与推荐系统**，将模型能力接入可使用、可验证的工作流。

- **应用落地：** 析页将教材 PDF 与图片转为结构化题库，覆盖跨页识题、来源追溯、人工校对、任务恢复与导出。
- **Agent 工程：** Aemeath Agent 统一多种交互入口，围绕能力装配、会话持久化、操作确认和审计组织运行时。
- **工程验证：** 代码并行化框架通过隔离改写、差分验证和受资源约束的基准测试，判断候选方案是否值得采用。
- **模型实践：** 开展 CLIP / BLIP-2 训练链路、多通道召回与排序实验，并记录实现、消融与复现方法。

欢迎通过相关项目的 Issues 交流实现细节、问题与改进建议。

