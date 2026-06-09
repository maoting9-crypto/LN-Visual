# Reference Library

## 目录作用

本目录用于管理多宫格参考库的索引、分析报告、标签规则和模板沉淀记录。

本项目默认使用本地共享素材库：

```text
G:\Reference-Library
```

不要要求用户把参考图、产品图、模特图、背景图复制进项目文件夹。

## 默认素材来源

- 多宫格参考图：`G:\Reference-Library\01_Multi-grid-reference`
- 产品图：`G:\Reference-Library\02_Product-Images`
- 模特图：`G:\Reference-Library\03_Model-Images`
- 背景素材：`G:\Reference-Library\04_Background-Assets`
- 运营需求：`G:\Reference-Library\05_Operation-Briefs`

## 本项目保存什么

当前项目是规则、分析、模板和提示词系统，只保存：

- 参考图索引
- 外部素材索引
- 参考图拆解报告
- 模板匹配记录
- 新增模板编号
- 多宫格提示词
- 项目执行记录

## 本项目不默认保存什么

本项目不默认保存原始素材，包括：

- 原始参考图
- 原始产品图
- 原始模特图
- 原始背景图
- 原始运营截图或表格

原始素材继续保留在 `G:\Reference-Library` 中。

## Codex 如何读取素材

1. 用户提供外部素材路径，或指定读取 `G:\Reference-Library` 下的某个子文件夹。
2. Codex 先检查路径是否可访问。
3. 可访问时，Codex 读取素材并生成分析报告。
4. Codex 更新 `External-Reference-Index.md`。
5. 如果参考图可沉淀为模板，Codex 只保存模板拆解和模板编号，不复制原图。

## 安全规则

Codex 可以读取 `G:\Reference-Library` 中的素材，但不得修改、删除、移动、重命名任何原始素材。

如果路径无法访问，必须明确告诉用户，并请用户检查路径或权限；在没有读取到图片前，不得编造图片内容。
