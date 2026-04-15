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
├── planning/                          # 规划与推理
├── memory/                            # 记忆机制
├── tool-use/                          # 工具使用
├── multi-agent/                       # 多智能体
├── evaluation/                        # 评估与基准
├── application/                       # 应用场景
└── survey/                            # 综述
```

## 分类说明

| 分类 | 目录 | 说明 |
|------|------|------|
| 规划与推理 | `planning/` | 任务分解、推理链、计划生成 |
| 记忆机制 | `memory/` | 短期/长期记忆、检索增强 |
| 工具使用 | `tool-use/` | API调用、函数调用、工具学习 |
| 多智能体 | `multi-agent/` | 多Agent协作、通信、博弈 |
| 评估与基准 | `evaluation/` | 基准测试、评估框架 |
| 应用场景 | `application/` | 代码生成、Web、机器人等 |
| 综述 | `survey/` | 领域综述与全景分析 |

## 快速开始

1. 选择合适的分类目录（如 `planning/`）
2. 在分类目录下为新论文创建文件夹，文件夹名为论文主题（简短英文）
3. 按 [WORKFLOW.md](WORKFLOW.md) 规范完成翻译和总结
4. 将论文中的图片按出现顺序保存为 `image-1.png`, `image-2.png`, ...
5. 更新分类目录的 README

详细规范见 [WORKFLOW.md](WORKFLOW.md)。
