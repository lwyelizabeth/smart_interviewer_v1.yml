# smart_interviewer_v1.yml
# 智能金融面试评估助手 (Smart FinTech Interviewer)

🚀 **本项目为 [CUFE] [人工智能A] 期末作业**

## 🌟 项目简介
这是一个基于 Dify 开发的智能 Agent，旨在通过 RAG（检索增强生成）技术，辅助求职者进行高质量的行为面试训练。系统深度对标“宝洁八大问”标准，并采用 KSAO 素质模型进行客观评估。

## 🔗 在线演示地址
[点击这里开始模拟面试](https://udify.app/chat/ZKewrObm5KKN1vBz)
*(注：若链接失效，可能是 API 额度耗尽)*

## 🛠️ 技术栈
- **核心引擎**: DeepSeek-V3
- **开发平台**: Dify (Workflow 模式)
- **知识库策略**: RAG (倒排索引 / STAR 原则)
- **评估模型**: KSAO (Knowledge, Skills, Abilities, Other)

## 📂 仓库内容
- `smart_interviewer_v1.yml`: 项目导出的 DSL 逻辑文件，可导入 Dify 复现。
- `期末论文.pdf`: 详尽的项目设计文档、技术挑战调优及心得。
- `/screenshots`: 包含系统拓扑图及实验结果截图。

## ⚙️ 如何复现本项目
1. 登录你的 [Dify](https://dify.ai) 账号。
2. 点击“创建应用” -> “导入 DSL 文件”。
3. 选择本仓库中的 `.yml` 文件。
4. 在“模型供应商”中配置你的 DeepSeek 或 硅基流动 API Key。
5. 发布应用并开始对话。

## 📈 核心亮点
- **拒绝“老好人”幻觉**：通过 Prompt 工程实现了极其严苛的评分逻辑。
- **动态表现评估**：实现了静态背景分与动态表现分的逻辑解耦。
- **状态机管理**：解决了工作流多轮对话中的“开场白重复”问题。
