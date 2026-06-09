# Common Commands

## 解析运营需求

```text
请调用 li-ning-multi-grid-director Skill，解析这个运营需求，只输出【需求已提供内容】【需求未提供内容】【需要用户确认内容】，不要自动补全。
```

## 只读取原文解析运营需求

```text
请调用 li-ning-multi-grid-director Skill，读取运营需求表或需求图片，只提取其中明确写出的需求内容。不要自动添加、自动推断或自动补全任何信息。没有写出的内容统一标记为“需求未提供”。如果缺失内容会影响最终提示词，请列为“需要用户确认”，不要擅自继续生成。
```

## 生成九宫格提示词

```text
请调用 li-ning-multi-grid-director Skill，为这个李宁九宫格朋友圈任务生成一张完整九宫格海报提示词、内部 3x3 格子功能规划和简洁检查表。不要默认输出 9 张单独图片，除非我明确要求每格单独生成。
```

## 分析多宫格参考图

```text
请调用 li-ning-multi-grid-director Skill，读取以下多宫格参考图路径：
G:\Reference-Library\01_Multi-grid-reference

请只提取参考图的信息布局和模块关系，不要照搬原图风格、配色、背景、人物、光影和装饰元素。请判断是否已有相似布局模板；如果没有相似布局模板，请拆解版式并沉淀为新模板编号，同时更新 External-Reference-Index.md。
```

## 分析产品图

```text
请调用 li-ning-multi-grid-director Skill，读取以下产品图路径：
G:\Reference-Library\02_Product-Images

请在后续多宫格提示词中要求 AI 尽量精准还原产品颜色、结构、Logo 位置、材质、图案和细节。
```

## 使用外部素材生成多宫格提示词

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

输出文件统一保存到：

```text
08_Projects
```

## 生成外部平台可用提示词

```text
请调用 li-ning-multi-grid-director Skill，先读取并分析我指定的多宫格参考图，把参考图转写成版式结构分析文字，再生成可直接复制到外部 AI 生图平台的完整提示词。

要求：
- 最终生图提示词中不要出现任何本地路径。
- 不要写“参考某文件”“参考上图”“参考本地图片”。
- 必须用文字描述整体构图、每格功能、主标题区、产品区、二维码区、价格权益区和信息层级。
- 必须保持参考图的信息布局和模块关系，但重新设计为李宁品牌视觉风格。
- 不允许照搬原图风格、配色、背景、人物、光影和装饰元素。
- 如果参考图不确定，请先列出候选图让我确认。
```

## 只提取参考图结构并生成外部平台提示词

```text
请调用 li-ning-multi-grid-director Skill，读取参考图库：
G:\Reference-Library\01_Multi-grid-reference

请只提取参考图的信息布局和模块关系，不要照搬原图风格、配色、背景和人物。请将参考图结构转写成可用于外部 AI 平台的完整提示词结构，再结合李宁品牌规范、运营需求和产品信息，输出最终多宫格海报提示词。
```

## 强锁定参考图生成多宫格提示词

```text
请调用 li-ning-multi-grid-director Skill，严格按照指定参考图的原有信息布局和模块关系生成多宫格海报提示词。参考图进入强锁定模式，只允许修改配色、字体设计、图片内元素、整体风格调性、人物素材和背景，其他结构、位置、模块关系全部保持不变。
```

## 分析模特图

```text
请调用 li-ning-multi-grid-director Skill，读取以下模特图路径：
G:\Reference-Library\03_Model-Images

请分析人物姿态、品类适配、运动状态和可用于哪类多宫格画面。
```

## 分析背景素材

```text
请调用 li-ning-multi-grid-director Skill，读取以下背景素材路径：
G:\Reference-Library\04_Background-Assets

请分析背景适合的品类、活动、节日、画面氛围和多宫格结构。
```
