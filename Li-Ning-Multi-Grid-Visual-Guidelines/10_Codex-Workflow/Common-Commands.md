# Common Commands

## 分析多宫格参考素材

```text
请调用 li-ning-multi-grid-director Skill，只读取以下多宫格参考素材路径：
G:\Reference-Library\01_Multi-grid-reference

请学习并保持参考素材中的布局规律和位置关系，包括整体宫格结构、每格功能关系、主标题区位置、副标题区位置、产品区位置、产品标签位置、鞋品摆放位置、模特 / 人物素材位置、场景素材使用位置、二维码区域位置、信息层级结构、背景延展关系和裁切规则。不要学习原图品牌、配色、字体、背景、人物、文案、光影、装饰元素和具体视觉风格。
```

## 使用本地共享素材生成完整多宫格提示词

```text
请调用 li-ning-multi-grid-director Skill，基于以下素材路径和运营需求，生成一张完整多宫格海报提示词、内部格子功能规划和简洁检查表。不要默认拆成每格单独生图，除非我明确要求切图或每格单独生成。

参考图路径：G:\Reference-Library\01_Multi-grid-reference
产品图路径：G:\Reference-Library\02_Product-Images
模特图路径：G:\Reference-Library\03_Model-Images
背景素材路径：G:\Reference-Library\04_Background-Assets
运营需求路径：G:\Reference-Library\05_Operation-Briefs

运营需求：
输出形式：
```

## 只读取运营需求

```text
请调用 li-ning-multi-grid-director Skill，读取运营需求表或需求图片，只提取其中明确写出的需求内容。不要自动添加、自动推断或自动补全任何信息。没有写出的内容统一标记为“需求未提供”。如果缺失内容会影响最终提示词，请列为“需要用户确认”，不要擅自继续生成。
```

## 最终提示词表达方式

```text
请把多宫格参考素材转写为外部 AI 平台可理解的结构化描述。不要在最终提示词中出现本地路径，不要写“参考 G:”，不要自由重构版式，不要移动二维码位置，不要重新设计产品卡排列方式。请使用表达：“从多宫格参考素材中学习并保持布局规律和位置关系，再结合李宁品牌需求重塑视觉风格。”
```
