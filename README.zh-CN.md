[![Language](https://img.shields.io/badge/Language-English-blue)](README.md)
[![语言](https://img.shields.io/badge/语言-中文-red)](README.zh-CN.md)

# 学术论文专业摘要 · V3 微调 / PEFT

本仓库展示了为研究机构打造的工作流与关键实现，用于生成专业的约 25 词学术摘要。

- 任务：每周为多篇论文生成约 25 词摘要，用于 weekly Research alerts。
- 核心成果：
  - 时间成本：改造前每周 >40 小时 → 改造后每周 ≤2 小时
  - 质量保障：方法/主题准确、风格一致
  - 可复用：MCP 流水线 + 修改数据
- 背景与目标：
  - 时间限制：摘要需在 4 天内定稿
- 现实挑战：
  - 数量多且紧急
  - 主题与方法广，理解成本高
  - 内部标准反复修改、沟通成本高

## 版本说明（V3 · 微调 / PEFT）
- 为何尝试：通过全量微调与 PEFT（Adapter/LoRA/P‑tuning）提升可控性与一致性。
- 为何放弃：缺少可用 GPU，仅能评测社区微调模型；效果与成本不匹配，遂转向 MCP 工作流。

## 链接
- 主仓库：https://github.com/B-Snowii/Research-Paper-Summary-Collection
- 许可证：MIT
