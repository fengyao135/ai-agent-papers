# AI Agent 论文阅读笔记

本仓库用于系统性地记录 AI Agent 相关领域的论文阅读笔记。每篇论文包含两份笔记：

| 文件类型 | 命名格式 | 说明 |
|---------|---------|------|
| 中文翻译 | `论文主题_中文翻译.md` | 论文全文的中文翻译，保留原文结构 |
| 论文总结 | `论文主题_论文总结.md` | 结构化的论文分析与总结 |

## 目录结构

```
ai-agent-papers/
├── README.md                          # 本文件
├── WORKFLOW.md                        # 工作流规范
├── templates/
│   ├── 翻译模板.md                     # 翻译文件模板
│   └── 总结模板.md                     # 总结文件模板
└── papers/
    ├── planning/                      # 规划与推理
    ├── memory/                        # 记忆机制
    ├── tool-use/                      # 工具使用
    ├── multi-agent/                   # 多智能体
    ├── evaluation/                    # 评估与基准
    ├── application/                   # 应用场景
    ├── survey/                        # 综述
    └── <分类>/<论文主题>/              # 每篇论文一个文件夹
        ├── 论文主题_中文翻译.md
        ├── 论文主题_论文总结.md
        ├── image-1.png                # 论文截图
        ├── image-2.png
        └── ...
```

## 论文索引

<!-- 按添加时间倒序排列，新论文添加到表格顶部 -->

| # | 论文标题 | 分类 | 日期 | 翻译 | 总结 |
|---|---------|------|------|------|------|
| 1 | Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering | 综述 | 2026-04 | [翻译](papers/survey/LLM_Agent_Externalization/LLM_Agent_Externalization_中文翻译.md) | [总结](papers/survey/LLM_Agent_Externalization/LLM_Agent_Externalization_论文总结.md) |

**分类说明**：

| 分类 | 目录 | 说明 |
|------|------|------|
| 规划与推理 | `papers/planning/` | 任务分解、推理链、计划生成 |
| 记忆机制 | `papers/memory/` | 短期/长期记忆、检索增强 |
| 工具使用 | `papers/tool-use/` | API调用、函数调用、工具学习 |
| 多智能体 | `papers/multi-agent/` | 多Agent协作、通信、博弈 |
| 评估与基准 | `papers/evaluation/` | 基准测试、评估框架 |
| 应用场景 | `papers/application/` | 代码生成、Web、机器人等 |
| 综述 | `papers/survey/` | 领域综述与全景分析 |

## 快速开始

1. 选择合适的分类目录（如 `papers/planning/`）
2. 在分类目录下为新论文创建文件夹，文件夹名为论文主题（简短英文）
3. 复制 `templates/翻译模板.md` → `论文主题_中文翻译.md`，完成翻译
4. 复制 `templates/总结模板.md` → `论文主题_论文总结.md`，完成总结
5. 将论文中的图片按出现顺序保存为 `image-1.png`, `image-2.png`, ...
6. 更新本 README 的论文索引表格及分类目录的 README

详细规范见 [WORKFLOW.md](WORKFLOW.md)。
