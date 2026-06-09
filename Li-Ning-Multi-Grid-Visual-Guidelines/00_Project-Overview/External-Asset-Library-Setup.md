# External Asset Library Setup

## 本地共享素材库的作用

本地共享素材库是本项目默认读取的原始素材存放位置，用于统一管理多宫格参考图、产品图、模特图、背景素材和运营需求资料。

当前项目本身只保存规则、索引、分析报告、模板拆解、模板编号和提示词，不默认保存原始图片素材。

## 当前素材库根路径

```text
G:\Reference-Library
```

## 子文件夹用途

### 01_Multi-grid-reference

路径：

```text
G:\Reference-Library\01_Multi-grid-reference
```

用于存放多宫格视觉参考图，包括九宫格、六宫格、四宫格、三宫格、双图组合、竞品参考、历史案例、AI 优秀案例等。

### 02_Product-Images

路径：

```text
G:\Reference-Library\02_Product-Images
```

用于存放产品图，包括跑鞋、篮球鞋、儿童产品、服装、配件、产品白底图、产品场景图等。

后续 AI 出图时，必须尽量精准还原产品颜色、结构、Logo 位置、材质、图案和细节。

### 03_Model-Images

路径：

```text
G:\Reference-Library\03_Model-Images
```

用于存放模特图和人物参考，包括跑步人物、篮球人物、儿童模特、亲子人物、训练人物、运动生活人物等。

### 04_Background-Assets

路径：

```text
G:\Reference-Library\04_Background-Assets
```

用于存放背景素材和场景素材，包括跑道、篮球场、城市运动场景、健身房、节日氛围背景、促销背景、抽象光效、速度线、粒子等。

### 05_Operation-Briefs

路径：

```text
G:\Reference-Library\05_Operation-Briefs
```

用于存放运营需求资料，包括运营表格、活动需求文档、截图、产品清单、价格权益信息、文案信息等。

## Codex 如何读取素材

1. 用户说明要分析哪类素材，或提供具体文件路径。
2. Codex 检查对应路径是否可访问。
3. Codex 读取素材进行分析、索引、模板匹配和提示词生成。
4. 分析报告和索引保存在当前项目中。
5. 原始素材继续保留在 `G:\Reference-Library` 中。

## Codex 禁止操作

Codex 不得修改、删除、移动、重命名 `G:\Reference-Library` 中的任何原始素材。

如果路径无法访问，Codex 必须提示用户检查路径或权限，不得编造素材内容。

## 推荐素材命名方式

建议文件名尽量包含：

```text
品牌_宫格类型_活动_品类_素材类型_版本
```

示例：

```text
LN_9Grid_618_Running_Reference_v01.png
LN_Product_RunningShoes_BlueWhite_v01.png
LN_Model_Basketball_Action_v01.jpg
```

## 推荐素材标签方式

建议素材标签包含：

```text
九宫格
六宫格
四宫格
促销
品宣
产品矩阵
大场景拼接
中间主题
跑步
篮球
儿童
618
端午
奥莱
```

## 后续调用示例

```text
请调用 li-ning-multi-grid-director Skill，读取 G:\Reference-Library\01_Multi-grid-reference 中的多宫格参考图，进行入库分析，判断是否匹配已有模板，并更新 External-Reference-Index.md。
```

```text
请调用 li-ning-multi-grid-director Skill，读取 G:\Reference-Library\02_Product-Images 中的产品图，后续生成提示词时要求 AI 尽量精准还原产品颜色、结构、Logo 位置、材质、图案和细节。
```
