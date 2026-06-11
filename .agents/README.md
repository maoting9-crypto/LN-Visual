# .agents

`E:\LN-Visual\.agents` 是 LN-Visual 项目组根目录级 Codex 配置区。

根目录级 Skill 用于项目组总控，不替代子项目 Skill。

## 根目录总控 Skill

当前计划或已经创建的总控 Skill 为：

`E:\LN-Visual\.agents\skills\ln-visual-4a-director\SKILL.md`

`ln-visual-4a-director` 是李宁 4A 平面设计创意总监总控 Skill。

它负责判断用户需求类型，并调度对应子项目 Skill，例如品牌规范 Skill 或多宫格 Skill。

## 子项目 Skill 仍然保留

品牌规范项目仍然使用：

`Li-Ning-Brand-AI-Visual-Guidelines\.agents\skills\li-ning-visual-director`

多宫格项目仍然使用：

`Li-Ning-Multi-Grid-Visual-Guidelines\.agents\skills\li-ning-multi-grid-director`

## 使用原则

- 根目录总控 Skill 负责判断需求、选择调用路径和协调子项目。
- 子项目 Skill 负责各自项目内的专业规则和执行细节。
- 根目录总控 Skill 不直接取代品牌规范 Skill。
- 根目录总控 Skill 不直接取代多宫格 Skill。
- 处理具体项目任务时，仍应遵守对应子项目内的 `AGENTS.md` 和 Skill 规则。
