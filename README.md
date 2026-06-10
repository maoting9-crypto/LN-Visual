# LN-Visual｜李宁 4A 平面设计创意总监系统

`E:\LN-Visual` 是李宁相关 AI 视觉项目的项目组总目录，用于统一管理品牌规范、多宫格视觉、测试海报和后续新增的李宁设计子项目。

它不是单一项目，而是一个“李宁 4A 平面设计创意总监系统”：通过总控 Skill 自动判断任务类型，并调用对应子项目、品牌规范和本地素材路径，帮助输出可直接用于 AI 生图的视觉方向与提示词。

## 当前子项目

- `Li-Ning-Brand-AI-Visual-Guidelines`：李宁品牌 AI 视觉规范项目，负责品牌基础规范、品类规范、活动规范、节日规范和视觉规范加权融合。
- `Li-Ning-Multi-Grid-Visual-Guidelines`：李宁朋友圈多宫格视觉规范项目，负责九宫格、六宫格、四宫格、多宫格布局学习、参考素材学习、提示词输出和质量检查。
- `LN-Test-Poster`：测试海报项目，用于临时测试海报提示词、出图流程和规范调用效果。

## 总控 Skill

项目组总控 Skill：

`E:\LN-Visual\.agents\skills\ln-visual-4a-director\SKILL.md`

它负责自动判断：

- 是否需要调用品牌规范项目
- 是否需要调用多宫格项目
- 是否需要读取 `G:\Reference-Library`
- 是否需要读取运营需求表、参考素材、产品图、模特图或背景素材
- 最终应该输出提示词、内部规划、检查表，还是沉淀到项目文件

## 外部素材库

默认素材库：

`G:\Reference-Library`

素材子路径：

- 多宫格参考素材：`G:\Reference-Library\01_Multi-grid-reference`
- 产品图：`G:\Reference-Library\02_Product-Images`
- 模特图：`G:\Reference-Library\03_Model-Images`
- 背景素材：`G:\Reference-Library\04_Background-Assets`
- 运营需求：`G:\Reference-Library\05_Operation-Briefs`

## 使用原则

- 根目录只负责项目组级说明和总控路由。
- 每个子项目可以拥有自己的 `README.md`、`AGENTS.md` 和 Skill。
- 具体品牌规范、活动规范、多宫格规则和测试案例放在对应子项目中。
- 不把大型素材文件直接放进 `E:\LN-Visual`。
- 外部素材统一从 `G:\Reference-Library` 调用。
- 最终给外部 AI 平台使用的提示词中，不写本地路径。
