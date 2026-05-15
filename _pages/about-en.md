---
layout: single
title: "Jiulin Li"
permalink: /en/
author_profile: true
---

## About

I am an **AI-native product engineer and applied AI researcher** currently pursuing an M.Sc. in Computer Technology at Beijing University of Posts and Telecommunications. My work sits at the intersection of AI agents, multimodal systems, full-stack AI products, vertical-domain data assets, and applied research.

I previously worked at the Beijing Institute for General Artificial Intelligence (BIGAI) on Any2Any multimodal understanding/generation and MAGUS, a multi-agent multimodal framework. I also founded and led Liuyi AI, where I built an AI-powered traditional-culture report product from product definition and algorithm design to frontend, backend, payment, report generation, ops dashboards, and deployment verification.

I treat AI agents as operational engineering resources rather than one-off chat tools. In real projects, I use Codex, Claude Code, OpenClaw, and nanobot-style workflows to decompose tasks, manage context, call tools, validate code and data outputs, compress long histories, and turn project evidence into reusable knowledge.

[中文首页]({{ '/' | relative_url }}) ｜ [CV]({{ '/cv/' | relative_url }}) ｜ [Full project portfolio]({{ '/projects/' | relative_url }}) ｜ [Google Scholar](https://scholar.google.com/citations?user=730nEoQAAAAJ&hl=zh-CN&oi=ao) ｜ [Liuyi AI](https://www.liuyi.life)

## Core Strengths

- **AI agents and AI coding workflows**: multi-agent task decomposition, context engineering, tool/function calling, MCP usage, skill workflows, browser snapshots, prompt/workflow constraints, code-review style validation, Feishu reporting, and knowledge governance.
- **AI product engineering**: AI workflows, PRDs/MVPs, SKU-based content products, structured questionnaires, free previews, paid unlocks, vouchers, report permissions, report retrieval, ops dashboards, internal workbenches, service agreements, and privacy boundaries.
- **Full-stack and platform engineering**: React 19, Vite, TypeScript, FastAPI, Postgres, REST APIs, internal authentication, task scheduling, GenService, Dulupay, Linux, systemd, nginx, rsync, CDN, health checks, and deployment verification.
- **Multimodal and foundation-model engineering**: LLMs/MLLMs, VLMs, Any2Any, Qwen2.5-Omni, Wan2.1 / Wan2.1-VACE, VILA-U, NeXT-GPT, Open-Sora, diffusion models, instruction tuning, model deployment/evaluation, and error analysis.
- **Data and evaluation**: Chinese vertical-domain benchmarks, structured knowledge extraction, QA generation, provenance, deduplication, RAG/agent evaluation data, model-evaluation standards, and feedback loops.

## Selected Work

### Liuyi AI / FateRipple

I founded and led Liuyi AI, an AI-powered traditional-culture and personalized-report product. The public site is available at [www.liuyi.life](https://www.liuyi.life). The product covers hot topics, birth-data input, structured questionnaires, free preview generation, WeChat/Alipay payment, voucher redemption, full-report generation, report retrieval, service agreements, and privacy policies.

The engineering stack includes a React 19 + Vite + TypeScript frontend, a FastAPI base backend, an internal FastAPI GenService, Postgres, DingMing, Dulupay payment integration, SKU configuration, Ops Dashboard, GenMonitor, voucher scripts, and systemd/nginx/CDN deployment workflows. I designed the product and built the commercial delivery loop across content generation, payment, entitlement, operations, and deployment verification.

### OpenClaw Multi-Agent Operations

I use OpenClaw agents as long-running operational resources. The workflows include subagent task decomposition, cron-agent execution, skill-based Bilibili content/author discovery, JSONL incremental writes, deduplication, retry queues, status tracking, Feishu daily reports, and long-history compression into reusable project facts.

This work demonstrates how I design, dispatch, review, and govern agent workflows. Agents execute many subtasks, while I define goals, constraints, context boundaries, validation requirements, and reusable knowledge structures.

### DingMing / YiWorld

DingMing is a vertical-domain Python core library and algorithm platform. It packages deterministic domain logic, structured intermediate results, prompt templates, streaming/non-streaming report managers, and LLM integration boundaries into a reusable base layer.

YiWorld exposes the core charting and report capabilities as services and applications, including a FastAPI base algorithm service, AWS Lambda + Supabase asynchronous report service, React frontend, and Feishu bot backend. The same rule engine and report-generation layer can serve multiple product entries.

### BIGAI Any2Any and MAGUS

At BIGAI, I worked on Any2Any multimodal understanding and generation. The work involved surveying frontier multimodal models and datasets, deploying and evaluating VILA-U, NeXT-GPT, Wan2.1, and Open-Sora, participating in modular orchestration with Qwen2.5-Omni, Wan2.1-VACE, AudioLDM2, and EmotiVoice, exploring VAE projectors, constructing multimodal instruction data, and building hard-routed multimodal systems.

This line of work developed into **MAGUS: A Unified Multi-Agent Framework for Universal Multimodal Understanding and Generation**, an arXiv paper on a modular multi-agent framework for text, image, audio, and video understanding/generation. MAGUS splits multimodal cognition and generation into Cognition and Deliberation stages, using role-conditioned MLLM agents and Growth-Aware Search to coordinate LLM reasoning with diffusion generation. [arXiv:2508.10494](https://arxiv.org/abs/2508.10494)

### Benchmark and QA Data Pipeline

I built a Chinese vertical-domain benchmark pipeline that moves from raw books to chapter texts, structured extraction, knowledge units, example extraction, QA generation, provenance tracking, and deduplication. Internal records currently summarize 76,431 QA items, including 68,095 `mingli_question` items and 8,336 `mingli_example` items. Public use of this scale still requires careful review of copyright and disclosure boundaries.

### Vision-Language and Video Research

I am the first author of **WaveDN: A Wavelet-based Training-free Zero-shot Enhancement for Vision-Language Models**, published at ACM MM 2024. WaveDN approaches VLM test-time enhancement from a signal-processing and wavelet perspective, improving zero-shot image classification and image-text retrieval without additional model training.

I also contributed to AdaDN, a modality-divergence-aware normalization method for VLMs, and to a PRCV 2023 video-understanding paper on fuzzy-error fine-tuning for spatio-temporal recognition.

## Education and Honors

- M.Sc. in Computer Technology, BUPT, 2023.09-2026.06 expected; GPA 3.63/4.0.
- B.E. in Internet of Things Engineering, BUPT / Queen Mary University of London, 2019.09-2023.06; First Class Honours, GPA 3.69/4.0.
- IELTS Academic Overall 6.5, CEFR B2.
- National Scholarship for Postgraduates, 2024-2025.
- Beijing Outstanding Graduate and BUPT Outstanding Graduate, 2026.
- Outstanding Graduate Student, BUPT and State Key Laboratory of Networking and Switching Technology, 2024.
- First-Class Academic Scholarship for Postgraduates, BUPT, 2023-2024, 2024-2025, and 2025-2026.
- Silver Medal, National Internet+ Innovation and Entrepreneurship Competition for Express Delivery, 2022.

## Publications

- **MAGUS: A Unified Multi-Agent Framework for Universal Multimodal Understanding and Generation**, arXiv, 2025. [link](https://arxiv.org/abs/2508.10494)
- **WaveDN: A Wavelet-based Training-free Zero-shot Enhancement for Vision-Language Models**, ACM MM 2024. [link](https://dl.acm.org/doi/10.1145/3664647.3681559)
- **Enhancing the Zero-shot Capability of Vision-Language Models from the Perspective of Modality Divergence / AdaDN**, manuscript under review, 2025.
- **A Fuzzy Error Based Fine-Tune Method for Spatio-Temporal Recognition Model**, PRCV 2023. [link](https://link.springer.com/chapter/10.1007/978-981-99-8429-9_8)
- **Meal delivery routing optimization with order allocation strategy based on transfer stations for instant logistics services**, IET Intelligent Transport Systems, 2022. [link](https://ietresearch.onlinelibrary.wiley.com/doi/pdf/10.1049/itr2.12206)
- **Real-time logistics order splitting method, apparatus, device, and storage medium**, CN112950119B, 2022. [link](https://patents.google.com/patent/CN112950119B/zh)

*Last updated: May 2026*
