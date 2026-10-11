---
name: eastern-minimal-exhibition-poster
description: 中式极简展览海报：融合东方山水留白、现代编辑设计、抽象色域绘画与纸艺质感，根据【主题】【主色域】【地景】【微型叙事】【中文题跋】【画幅】生成一张高完成度艺术展览海报。当用户提到"中式极简展览海报 / 留白色域海报 / 东方极简海报 / 展览海报"时使用。Use when the user asks for an Eastern/Chinese minimalist exhibition poster, a negative-space color-field poster, or provides 主题/主色域/地景 inputs — produces one refined poster with a large irregular color field, a hairline ink landscape, a tiny narrative, vertical Song-style title and a cinnabar seal.
license: MIT
---

# 中式极简展览海报 · Eastern Minimal Exhibition Poster

远看极简，近看有层次：大色域 × 微地景 × 极小人物/建筑。
Minimal from afar, layered up close: large color field × micro landscape × tiny figure or building.

## 输入 · Inputs

```
【主题】：
【主色域】：
【地景】：
【微型叙事】：
【中文题跋】：
【画幅】：9:16（默认）
```

**缺失字段不要追问**：只给了主题（或部分字段）时，由你根据主题自行补全其余字段，并保证色域、地景、叙事、题跋彼此协调、指向同一意境。画幅缺省为 9:16。
If any field is missing, fill it yourself coherently from the theme — never ask. Default aspect ratio 9:16.

## 使用方法 · How to use
1. 读取输入，补全缺失字段（内部完成，不输出分析）。
2. 按 [prompt.md](prompt.md) 的完整规则组合提示词，交给图像生成工具，只输出一张海报。
3. 若当前环境不能生图，输出已填好的 prompt.md 模板供用户粘贴到 ChatGPT / 其他图像模型。

示例输入见 [examples/themes.md](examples/themes.md)。

## 核心规则 · Core rules

### 目标 · Goal
高完成度中式极简艺术展览海报，融合：东方山水留白、现代编辑设计、抽象色域绘画、纸艺质感。

### 底与色域 · Ground & color field
- 背景：干净的暖象牙白艺术纸（warm ivory art paper）。
- 一块不规则【主色域】，占画面约 **40–55%**，奠定情绪。
- 色域质感：细腻矿物颜料 / 水粉 / 丝网印刷 / 纸张洇色；边缘自然，内部有轻微水痕与色阶变化——但保持干净，不做脏旧。

### 地景 · Landscape
在色域与留白交界处，用极细的墨黑线描绘【地景】：海岸线、山脊、林带、堤道、建筑剪影等。细、轻、精准，不做巨大黑山。

### 叙事 · Narrative
极小的【微型叙事】（小人物、小船、小屋、小鸟等）。以"大色域 × 微地景 × 极小人物/建筑"的尺度反差讲故事。

### 文字 · Typography
- 中文主标题：瘦高宋体或现代明朝体，优先竖排。
- 小号英文衬线体、日期、FIELD NOTES 等微型编辑信息。
- 【中文题跋】，少量手写注记，一枚极小的朱砂红印章。
- 文字必须是真实可读的字，不要 AI 乱码。

### 原则 · Principles
- "简单的大结构，丰富的微细节"：远看极简，近看有层次。
- 每个主题都要重新设计色域走向、地景结构与叙事，不能只换颜色或换标题。

### 避免 · Avoid
粗糙的空、粗暴平涂、模板换色、巨大黑山、旅游插画、过度仿古、脏污做旧、随机裂纹、AI 乱码文字、UI、logo、水印、编号、四角星光与闪光点。

### 执行 · Execution
不提问、不展示分析、不出多版本，直接输出一张海报。
