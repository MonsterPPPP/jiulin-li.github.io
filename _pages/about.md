---
permalink: /
title: "李九林 / Jiulin Li"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## 你好，我是李九林

我是一个 **AI-native 产品工程与算法实践者**，正在北京邮电大学攻读计算机技术硕士。我的工作横跨 AI Agent、AI 产品工程、多模态大模型、垂直领域数据资产和应用研究：既能阅读论文、部署评测模型、设计 benchmark，也能把一个 AI 产品从需求、算法、后端、前端、支付、运营看板到线上部署闭环做出来。

我曾在北京通用人工智能研究院（BIGAI）参与 Any2Any 多模态理解与生成系统和 MAGUS 多智能体多模态框架；同时创办并主导建设六艺AI，把传统文化场景中的个性化报告、支付转化、报告生成、运营工具和部署验收组织成可迭代的全栈系统。我也长期使用 Codex、Claude Code、OpenClaw、nanobot 等 AI 工具组织真实研发、数据采集、知识治理和发布流程，关注 AI 不只是“调用模型”，而是如何改变研发组织、产品交付和数据生产。

[查看完整项目集]({{ '/projects/' | relative_url }}) ｜ [CV]({{ '/cv/' | relative_url }}) ｜ [English version]({{ '/en/' | relative_url }}) ｜ [Google Scholar](https://scholar.google.com/citations?user=730nEoQAAAAJ&hl=zh-CN&oi=ao) ｜ [六艺AI](https://www.liuyi.life)

## 能力关键词

- **AI Agent 与 AI 编程工作流**：Multi-Agent、Context Engineering、任务拆解、tool calling / Function Call、MCP 使用、skill workflow、browser snapshot、prompt/workflow 约束、代码生成验收、长上下文压缩、飞书日报和知识库治理。
- **AI 产品工程与商业化闭环**：AI workflow、MVP/PRD、SKU 化内容产品、结构化问卷、免费预览、支付/兑换解锁、报告权限、我的报告找回、运营看板、内部工作台、服务协议与隐私边界。
- **全栈与平台工程**：React 19、Vite、TypeScript、FastAPI、Postgres、REST API、内部鉴权、任务调度、GenService、Dulupay、Linux、systemd、nginx、rsync、CDN、健康检查和部署验收。
- **多模态与大模型算法**：LLM/MLLM、VLM、Any2Any、Qwen2.5-Omni、Wan2.1 / Wan2.1-VACE、VILA-U、NeXT-GPT、Open-Sora、Diffusion、instruction tuning、模型部署评测和误差分析。
- **数据集与评测**：中文垂直领域 benchmark、结构化知识抽取、QA generation、provenance、去重缓存、模型评测标准、Agentic Pipeline、RAG/Agent 评测数据和反馈闭环。
- **研究与表达**：视觉语言模型、测试时增强、视频理解、即时配送优化；已发表 ACM MM 2024（CCF-A）、PRCV 2023（CCF-C）、IET ITS（JCR Q2）论文，并拥有授权专利。

## 我正在寻找的方向

我更适合需要“技术理解 + 产品判断 + 工程落地 + AI-native 工作方式”的岗位，尤其是：

- AI Agent / AI 工具链研发，Agent 平台、AI 编程产品、开发者工具
- 大模型应用、AI 策略产品工程、AI workflow 和业务闭环设计
- 多模态大模型算法工程、模型部署评测和数据/benchmark 构建
- AI 产品从 0 到 1、支付交付、运营工具、生成服务和部署工程
- 垂直领域数据资产、RAG/Agent 评测、结构化知识抽取和模型误差分析

## 代表项目

### 六艺AI / FateRipple：AI 内容产品与商业化交付闭环

我主导建设了六艺AI，一个面向传统文化和个性化报告场景的 AI 内容产品，公开站点已上线：[www.liuyi.life](https://www.liuyi.life)。产品链路覆盖热门议题、出生信息输入、结构化问卷、免费预览、微信/支付宝支付、兑换码、完整报告生成、我的报告找回、服务协议和隐私政策。

工程侧，FateRipple 拆分为 React 19 + Vite + TypeScript 前端、FastAPI Base 后端、FastAPI GenService 生成服务和 Postgres 数据库。Base 后端负责认证、档案、报告、订单、支付、钱包、活动、staff 工具和运营看板；GenService 负责热门议题、批量运势、报告生成和调度任务。围绕 SKU-Settings、SKU_DEV、Ops Dashboard、GenMonitor、礼品券码脚本和 HARNESS 部署文档，我把产品内容、AI 生成、商业化交付和运维验收串成一个可持续迭代系统。

### OpenClaw 多 Agent 指挥与数据资产构建

我长期维护并调度 OpenClaw agent，把复杂任务拆解为主对话、subagent task、cron task 和 skill workflow，组织 agent 执行 B站/社媒命理内容采集、作者发现、作者池扩展、JSONL 增量写入、去重、状态更新、飞书日报回传和历史压缩。

这套流程不是单次聊天，而是一种 agent operations：任务中明确要求读取 skill 文档、使用 browser snapshot、避免把完整作者池塞入上下文、预去重、处理 retry queue、更新 `author_pool.json` / `author_status.json` / `stats_summary.json`，并在 SIGTERM 中断、数据不一致、权限和上传问题出现时继续排障。后续我又把历史会话和文件压缩为 archive index、session summaries、command digest 和项目事实卡，沉淀到简历与项目事实库。

### DingMing / YiWorld：垂直领域算法平台与多应用入口

DingMing 是我主导沉淀的 Python 核心库，按“核心库 + 外置应用”组织，把传统文化推理中的规则计算、结构化中间结果、prompt 模板和报告生成边界沉淀为可复用能力。核心模块包括 `Ming`、`PanEngine`、`ReportManager`、`ReportStreamManager`、Romance/Career/SelfRomance/Hepan 报告服务和君臣 COT 分析链路。

在应用层，我将排盘与报告能力封装为 YiWorld FastAPI 基础算法服务、AWS Lambda + Supabase 异步报告生成服务、React 前端和飞书机器人后端，让同一套规则计算、结构化中间结果和 LLM 报告能力可以服务多个产品入口。

### BIGAI Any2Any 与 MAGUS 多智能体多模态系统

在 BIGAI，我参与 Any2Any 多模态大模型系统建设，调研 2023 至 2025 年前沿多模态模型、模态编码器和数据集，部署评测 VILA-U、NeXT-GPT、Wan2.1、Open-Sora，并参与 Qwen2.5-Omni、Wan2.1-VACE、AudioLDM2、EmotiVoice 等模块化模型编排，探索 VAE projector、多模态指令数据构建和 MLLM 微调。

该工作进一步发展为 **MAGUS: A Unified Multi-Agent Framework for Universal Multimodal Understanding and Generation**。MAGUS 将多模态理解与生成拆为 Cognition 与 Deliberation 两阶段，通过 Perceiver、Planner、Reflector 等角色化 MLLM agents 完成协作理解与规划，并用 Growth-Aware Search 协调 LLM 推理与 diffusion 生成，支持 text、image、audio、video 的可插拔 Any2Any 转换。论文已在 arXiv 发布：[arXiv:2508.10494](https://arxiv.org/abs/2508.10494)。

### 命理 Benchmark 与 QA 数据管线

我建设了中文垂直领域 benchmark 数据集与 QA 生成管线，从原始书籍、章节切分、结构化抽取、知识单元、命例抽取、QA 生成到 provenance 和去重缓存，形成 `stage0_raw_books -> stage1_chapter_texts -> stage2_fine_text -> stage3_qa_data` 的数据流程。当前内部事实库记录 `qa_summary.json` 中包含 76,431 条 QA 数据，其中 `mingli_question` 68,095 条、`mingli_example` 8,336 条。公开使用该规模前仍需确认版权和披露边界。

### WaveDN / AdaDN：视觉语言模型零样本增强

我以第一作者完成 **WaveDN: A Wavelet-based Training-free Zero-shot Enhancement for Vision-Language Models**，从信号处理和小波变换视角缓解视觉语言模型后处理过程中的信息损失，在无需额外训练的情况下提升零样本图像分类和图文检索表现，论文发表于 ACM MM 2024（CCF-A）。

我也参与 AdaDN 研究，针对 distribution-normalization 方法忽略图文模态分布差异的问题，提出基于特征熵动态调整归一化强度的思路：文本端弱归一化保护语义，图像端强归一化增强对齐。该工作当前为 manuscript under review。

## 教育与荣誉

- 北京邮电大学，计算机技术硕士，2023.09-2026.06（预计）；GPA 3.63/4.0，均分 86.33/100。
- 北京邮电大学 + Queen Mary University of London，物联网工程本科，2019.09-2023.06；First Class Honours，GPA 3.69/4.0，均分 88.34/100。
- IELTS Academic Overall 6.5（CEFR B2）。
- 硕士研究生国家奖学金，2024-2025。
- 北京市级优秀毕业生、北京邮电大学校级优秀毕业生，2026。
- 北京邮电大学优秀研究生、网络与交换技术全国重点实验室优秀研究生，2024。
- 北京邮电大学硕士研究生一等奖学业奖学金，2023-2024、2024-2025、2025-2026。
- 全国“互联网+”快递业创新创业大赛银奖，2022。

## 论文与专利

- **MAGUS: A Unified Multi-Agent Framework for Universal Multimodal Understanding and Generation**, arXiv, 2025. [link](https://arxiv.org/abs/2508.10494)
- **WaveDN: A Wavelet-based Training-free Zero-shot Enhancement for Vision-Language Models**, ACM MM 2024, CCF-A. [link](https://dl.acm.org/doi/10.1145/3664647.3681559)
- **Enhancing the Zero-shot Capability of Vision-Language Models from the Perspective of Modality Divergence / AdaDN**, manuscript under review, 2025.
- **A Fuzzy Error Based Fine-Tune Method for Spatio-Temporal Recognition Model**, PRCV 2023, CCF-C. [link](https://link.springer.com/chapter/10.1007/978-981-99-8429-9_8)
- **Meal delivery routing optimization with order allocation strategy based on transfer stations for instant logistics services**, IET Intelligent Transport Systems, JCR Q2, 2022. [link](https://ietresearch.onlinelibrary.wiley.com/doi/pdf/10.1049/itr2.12206)
- **Real-time logistics order splitting method, apparatus, device, and storage medium**, CN112950119B, 2022. [link](https://patents.google.com/patent/CN112950119B/zh)

*Last updated: May 2026*
