---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## 李九林 / Jiulin Li

AI-native 产品工程与算法实践者。北京邮电大学计算机技术硕士，2026 届。方向覆盖 AI Agent、AI 产品工程、多模态大模型、全栈 AI 平台、垂直领域数据资产和应用研究。

- Email: [lijiulin@bupt.edu.cn](mailto:lijiulin@bupt.edu.cn)
- Homepage: [https://jiulin-li.github.io/](https://jiulin-li.github.io/)
- Projects: [{{ base_path }}/projects/]({{ base_path }}/projects/)
- Google Scholar: [Profile](https://scholar.google.com/citations?user=730nEoQAAAAJ&hl=zh-CN&oi=ao)
- Product: [六艺AI / www.liuyi.life](https://www.liuyi.life)

## Education

**北京邮电大学**
M.Sc. in Computer Technology, 2023.09-2026.06 expected

- 计算机学院（国家示范性软件学院），网络与交换技术全国重点实验室。
- GPA 3.63/4.0，均分 86.33/100。
- Relevant coursework: 人机对话系统、复杂网络、高性能计算、新兴互联网技术与服务、软件质量控制与项目管理。

**北京邮电大学 / Queen Mary University of London**
B.E. in Internet of Things Engineering, 2019.09-2023.06

- First Class Honours；GPA 3.69/4.0，均分 88.34/100。
- 获免试推荐硕士研究生资格。

## Experience

**北京六艺观化科技有限公司 / 六艺AI**
Founder, CEO/CTO, Product Lead, 2025.10-present

- 主导 AI 传统文化个性化报告产品从 0 到 1 上线，负责产品定义、全栈工程、算法底座、支付/订单/券码/报告交付、运营看板、部署运维与团队协作。
- 技术栈包括 React 19、Vite、TypeScript、FastAPI、Postgres、DingMing、GenService、Dulupay、systemd、nginx 和 CDN。
- 产品形成“出生信息与问卷 -> 结构化分析 -> 免费预览 -> 支付/兑换解锁 -> 完整报告交付 -> 我的报告找回”的闭环，并上线 [www.liuyi.life](https://www.liuyi.life)。

**北京通用人工智能研究院（BIGAI）**
Multimodal Large Model Algorithm Intern, 2025.03-2025.08

- 参与 Any2Any 多模态理解与生成系统，覆盖前沿模型调研、VILA-U / NeXT-GPT / Wan2.1 / Open-Sora 等基座部署评测、VAE projector 探索、多模态指令数据构建与 MLLM 微调。
- 参与 Qwen2.5-Omni、Wan2.1-VACE、AudioLDM2、EmotiVoice 等模块化模型编排，落地硬路由式 text / image / audio / video 理解与生成链路，并扩展情绪分析专家能力。
- 参与 MAGUS 多智能体框架，将理解与生成拆分为 Cognition / Deliberation 两阶段，用角色化 MLLM agents 与 Growth-Aware Search 协调 LLM 推理和 diffusion 生成。

## Selected Projects

**OpenClaw 多 Agent 指挥与数据资产构建工作流**
Agent workflow design, dispatch, and validation, 2026.03-2026.05

- 设计并调度 OpenClaw agent 长期执行数据采集、作者发现、内容整理、日报回传与历史压缩任务，把复杂工作拆解为 subagent task、cron task 和 skill workflow。
- 任务约束覆盖 browser snapshot、增量 JSONL 写入、预去重、状态文件更新、统计摘要、retry queue 与 SIGTERM 摘要，避免把长上下文和全量数据直接塞入 agent。
- 通过飞书日报、状态文件与压缩索引验收 agent 产物，并把历史会话/文件压缩为 archive index、session summaries、command digest 和项目事实卡。

**FateRipple / GenService AI 内容产品与商业化链路**
Founder, CTO, Product Lead, 2025.10-present

- 拆分 Base 后端与 GenService 内部生成服务，用户侧 API 负责认证、档案、报告、订单、支付、券码与运营看板，生成服务负责热门议题、运势与报告生成任务。
- 实现热门议题、结构化问卷、免费预览、微信/支付宝支付、兑换码核销、订单状态恢复、完整报告交付、我的报告找回、内部报告工作台和 GenService 监控。
- 围绕 SKU-Settings、SKU_DEV、Ops Dashboard、GenMonitor 和 HARNESS 文档沉淀可迭代产品工程体系。

**DingMing / YiWorld 垂直领域算法平台**
Project builder and product-technical owner, 2025-2026

- 构建可安装 Python 核心库，把传统文化/命理领域的规则计算、结构化中间结果、prompt 模板和报告生成拆分为“核心库 + 外置应用”。
- 核心能力包括 Ming、PanEngine、ReportManager、ReportStreamManager、Romance / Career / Hepan 等报告服务，并接入君臣 COT 分析链路。
- 外置应用包括 FastAPI 基础算法服务、AWS Lambda + Supabase 异步报告服务、React 前端和飞书机器人服务。

**MAGUS / BIGAI Any2Any 多模态大模型系统**
Multimodal algorithm intern and paper contributor, 2025.03-2025.08

- 参与 Any2Any 多模态大模型系统设计、部署与评测，覆盖 VILA-U、NeXT-GPT、Wan2.1、Open-Sora 等基座调研与评测，以及 Qwen2.5-Omni、Wan2.1-VACE 等模块化模型编排。
- 参与 MAGUS 多智能体框架，将多模态理解与生成拆分为 Cognition / Deliberation 两阶段，通过 Perceiver、Planner、Reflector 等角色化 MLLM agents 完成协作理解与规划。
- 在 Deliberation 阶段引入 Growth-Aware Search 协调 LLM 推理和 diffusion 生成，支持文本、图像、音频、视频的可插拔 Any2Any 转换。

**HARNESS / nanobot Agent 驱动部署与资料治理**
Deployment engineering and knowledge governance, 2026

- 为 FateRipple 建立 agent-assisted 发布规范，覆盖提交规则、远端部署、依赖安装、rsync、systemd restart、健康检查、前端构建与静态资源同步。
- 将线上配置真源、服务启动、源站/CDN 验收、运维排障和 agent 协作规则写入 HARNESS 文档，降低小团队部署过程的不可控性。

**命理 Benchmark 数据集与 QA 生成管线**
Dataset and evaluation pipeline builder, 2026

- 设计并跑通中文垂直领域 benchmark 数据管线，从原始书籍清洗、章节切分、结构化抽取到 QA 生成、provenance 追踪与去重缓存。
- 将知识、规则理解和命例推理转化为可评测数据资产，并按类别、来源、题型和流程阶段进行统计，支撑模型能力评估与误差分析。
- 内部事实库记录 76,431 条 QA 数据；公开使用前需确认数据来源与披露边界。

## Research

- **MAGUS: A Unified Multi-Agent Framework for Universal Multimodal Understanding and Generation**, arXiv, 2025. [link](https://arxiv.org/abs/2508.10494)
- **WaveDN: A Wavelet-based Training-free Zero-shot Enhancement for Vision-Language Models**, ACM MM 2024, CCF-A. First author. [link](https://dl.acm.org/doi/10.1145/3664647.3681559)
- **Enhancing the Zero-shot Capability of Vision-Language Models from the Perspective of Modality Divergence / AdaDN**, manuscript under review, 2025.
- **A Fuzzy Error Based Fine-Tune Method for Spatio-Temporal Recognition Model**, PRCV 2023, CCF-C. [link](https://link.springer.com/chapter/10.1007/978-981-99-8429-9_8)
- **Meal delivery routing optimization with order allocation strategy based on transfer stations for instant logistics services**, IET Intelligent Transport Systems, JCR Q2, 2022. [link](https://ietresearch.onlinelibrary.wiley.com/doi/pdf/10.1049/itr2.12206)
- **Real-time logistics order splitting method, apparatus, device, and storage medium**, CN112950119B, 2022. [link](https://patents.google.com/patent/CN112950119B/zh)

## Skills

- **AI Agent / LLM**: Multi-Agent, context engineering, tool/function calling, MCP usage, prompt/workflow constraints, skill workflows, Codex, Claude Code, OpenClaw, nanobot-style deployment.
- **AI Product**: AI workflow, PRD/MVP, SKU, free preview, paid unlock, voucher, result card, private-domain conversion, ops dashboard, privacy/service-boundary design.
- **Engineering**: Python, FastAPI, React 19, Vite, TypeScript, Postgres, REST API, internal auth, task scheduling, Linux, systemd, nginx, rsync, CDN, health checks.
- **Model / Data**: LLM, MLLM, VLM, Any2Any, Diffusion, Qwen2.5-Omni, Wan2.1, VILA-U, NeXT-GPT, Open-Sora, benchmark design, QA generation, provenance, dedupe, error analysis.
- **Languages**: Chinese native; English IELTS Academic Overall 6.5 (CEFR B2).

## Honors

- National Scholarship for Postgraduates, 2024-2025.
- Beijing Outstanding Graduate, 2026.
- BUPT Outstanding Graduate, 2026.
- Outstanding Graduate Student, BUPT, 2024.
- Outstanding Graduate Student, State Key Laboratory of Networking and Switching Technology, 2024.
- First-Class Academic Scholarship for Postgraduates, BUPT, 2023-2024, 2024-2025, 2025-2026.
- Silver Medal, National Internet+ Innovation and Entrepreneurship Competition for Express Delivery, 2022.

*Last updated: May 2026*
