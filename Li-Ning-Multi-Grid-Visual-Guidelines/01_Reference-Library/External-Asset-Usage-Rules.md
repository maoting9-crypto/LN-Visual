# External Asset Usage Rules

## 本地共享素材库调用规则

- 本项目默认使用 `G:\Reference-Library` 作为外部素材库。
- 项目内部不保存原始图片素材。
- Codex 只读取外部素材路径，不修改原始素材。
- Codex 不得移动、删除、重命名外部素材。
- 如果路径无法访问，必须提示用户检查路径或权限。
- 分析报告、索引、模板编号、模板拆解和提示词保存在当前项目内。
- 原始素材继续保留在 `G:\Reference-Library` 中。

## 分析后保存位置

外部素材分析报告保存到：

```text
01_Reference-Library/07_Reference-Analysis-Reports
```

外部参考图索引保存到：

```text
01_Reference-Library/External-Reference-Index.md
```

## 产品图提示词要求

如果产品图来自外部路径，生成提示词时必须写明：

```text
参考外部产品图，尽量精准还原产品颜色、结构、Logo 位置、材质、图案和细节。
```
