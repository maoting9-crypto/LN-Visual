# 2026-618-Running-9Grid-Test

这是李宁 618 跑步品类九宫格朋友圈海报测试项目。

## 当前版本说明

- 旧版文件保留，用于对比。
- V3 文件用于测试“参考图先分析再转写”和“最终外部 AI 提示词禁止本地路径”规则。
- V3 优先使用用户指定的 `0527-18点-朋友圈-示意图.jpg` 作为结构布局参考。
- 最终可复制到外部 AI 生图平台的文件是 `Final-External-AI-Prompt-V3.md`。
- V4 文件用于测试“需求文案唯一来源”和“没有价格权益时禁止生成价格类文案”规则。
- V4 当前可复制到外部 AI 生图平台的文件是 `Final-External-AI-Prompt-V4.md`。
- V5 文件用于测试“参考图强锁定模式”，只重塑视觉风格，不重构版式结构。
- V6 文件用于测试“需求原文读取”和“禁止自动补全”，没有写出的内容统一标记为“需求未提供”。

## V3 文件

- `Reference-Layout-Analysis-V3.md`：内部参考图版式结构分析，可以记录本地路径。
- `Final-External-AI-Prompt-V3.md`：外部 AI 平台可用提示词，不允许出现本地路径。
- `Grid-Prompts-V3.md`：九宫格内部每格结构规划。
- `Quality-Check-V3.md`：V3 简洁检查表。

## V4 文件

- `Demand-Analysis-V4.md`：重新判断当前需求是否提供价格、权益、折扣、券包、促销标签、产品名和货号。
- `Reference-Layout-Analysis-V4.md`：说明参考图中的价格区只作为结构参考。
- `Final-External-AI-Prompt-V4.md`：外部 AI 平台可用提示词，不生成未提供的价格权益文案。
- `Quality-Check-V4.md`：V4 简洁检查表。

## V5 文件

- `Demand-Analysis-V5.md`：强锁定模式需求分析。
- `Reference-Layout-Analysis-V5.md`：强锁定模式参考图结构分析。
- `Final-External-AI-Prompt-V5.md`：强锁定模式外部 AI 平台可用提示词。
- `Quality-Check-V5.md`：V5 简洁检查表。

## V6 文件

- `Demand-Analysis-V6.md`：只读取需求原文，不自动补全。
- `Missing-Info-Need-Confirm-V6.md`：缺失信息与需要用户确认清单。
- `Final-External-AI-Prompt-V6.md`：基于需求原文的结构测试提示词。
- `Quality-Check-V6.md`：V6 简洁检查表。
