# PromptAtlas
![](./assets/images/banner.png "PromptAtlas")

一个持续积累、整理、迭代的高质量提示词库（Prompt Library）。

- [提示词列表页](./indexes/prompt-index.md)

这个仓库用于沉淀我在 AI 应用、内容分析、企业场景、产品设计、技术研究、Agent 指令设计等方向中的高价值提示词，方便后续复用、优化、检索与版本管理。

---

## 仓库目标

本仓库希望解决以下问题：

- 提示词分散在聊天记录、文档、笔记中，不方便统一管理
- 同类提示词不断重复编写，效率低
- 提示词缺少版本迭代与效果沉淀，难以持续优化
- 缺少统一结构，后期提示词一多就难以查找和复用

因此，这个仓库将提示词作为一种可积累、可复用、可维护的“资产”进行管理。

---

## 适用场景

本仓库中的提示词主要面向以下场景：

- 文章分析与深度总结
- 技术报告解析
- AI / 大模型 / Agent 相关研究
- 企业级方案设计
- 产品需求分析与 PRD 编写
- 架构设计与技术路线规划
- 行业研究与商业洞察
- 演讲稿 / 汇报材料 / PPT 内容生成
- 知识抽取、结构化整理与内容重写
- 智能体系统指令（System Prompt / Agent Instruction）

---

## 设计原则

为了保证提示词库长期可维护，本仓库遵循以下原则：

1. **结构化**  
   每个提示词都尽量包含名称、用途、适用模型、输入要求、输出要求、使用示例等信息。

2. **可复用**  
   尽量将提示词写成模板化结构，而不是一次性文本。

3. **可迭代**  
   提示词不是一成不变的，需要持续优化版本与效果。

4. **可检索**  
   通过清晰的目录、命名规范、标签与索引，保证后期能够快速找到需要的提示词。

5. **场景优先**  
   以真实业务场景为核心组织提示词，而不是仅按理论分类。

---

## 仓库结构（示例）

```bash
prompt-library/
├── README.md
├── prompts/
│   ├── analysis/
│   ├── writing/
│   ├── coding/
│   ├── agent/
│   ├── product/
│   ├── research/
│   ├── business/
│   └── templates/
├── docs/
│   ├── naming-rules.md
│   ├── writing-guidelines.md
│   └── prompt-methodology.md
├── examples/
│   ├── input-examples/
│   └── output-examples/
├── assets/
│   └── images/
└── index/
    ├── prompt-index.md
    └── tags.md