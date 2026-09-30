---
id: knowledge-readme
title: knowledge/ 目录说明（公开版）
category: devflow
status: verified
confidence: offline
verified_at: 2026-09-30
stale_days: 365
origin: total
source: 2026-09-30 公开版索引说明（release 同步时生成）
platforms: []
tags: [知识目录, 索引, 公开版, 检索]
evidence: []
---
# knowledge/ 目录说明（公开版）

本目录是 FlyThings MCP 的**实践知识库**（随检索索引 `rag_index.json` 一起分发）：

| 子目录 | 内容 |
|---|---|
| `uicontrols/` | 基础控件字段/API/坑位（button / textview / listview / pagewindow / seekbar / qrcode / videoview …） |
| `devflow/` | 工程配置、布局流水线、自定义控件与渲染、资源出图、部署与验收、多语言 |
| `hardware/` | 跨平台硬件 API 与型号速查（USB OTG 切换、UVC 通用接入层等） |
| `inbox/` | 候选条目（**不进检索**，供评审用） |

- 文档带 front-matter（`status / confidence / verified_at / evidence`）：`review` 可检索但需核对，`verified` 才可直接引用。
- 检索走 MCP 工具 `flythings_knowledge_search`；查不到就是未收录 —— **不要用其它 GUI 框架类推**。
- 内部/方案类深度内容不在公开版（以平台方 SDK 与官方文档 `developer.flythings.cn` 为准）。
