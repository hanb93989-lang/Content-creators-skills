# AI Script Workflow

## Use Case

Use this when the user wants to use AI to generate or evaluate short-video scripts, especially product-selling scripts. This is not a generic prompt library. It is a thinking workflow: product -> audience -> context -> JTBD -> scoring -> script generation.

## Step 1: Set The Thinking Frame

Ask for:

- Product name
- Price
- Simple product description
- Main selling points

Then analyze through:

- Douyin recommendation logic: content is targeting.
- Target audience segments.
- Key contexts where the audience feels the need.
- JTBD: what job the product is hired to do.
- Problems, doubts, value, and emotions solved by the product.

Use a stance of strict analysis, not pleasing the user.

## Step 2: Score Audience-Context Opportunities

Score each audience-context pair with a 10-point model:

- Pain intensity: 3.0 points
  - 0-1.0 minor trouble
  - 1.1-2.0 clear discomfort
  - 2.1-3.0 strong pain affecting core behavior
- Audience scale: 2.0 points
  - 0-1.0 niche
  - 1.1-1.5 medium
  - 1.6-2.0 large core audience
- Content spreadability: 2.5 points
  - 0-1.0 weak
  - 1.1-2.0 medium
  - 2.1-2.5 strong resonance and short-video suitability
- Value perception: 2.5 points
  - 0-1.0 weak
  - 1.1-2.0 medium
  - 2.1-2.5 product value directly solves the pain and is easy to perceive

Adjust the scoring weights by purpose:

- For seeding and audience expansion: raise audience scale and spreadability.
- For pain-point selling: raise pain intensity and value perception.

Be strict. Scores should show real differences.

## Step 3: Generate Script Directions

Generate multiple script types only after scoring. For each script direction, include:

- Script name
- Narrative logic
- Copy framework
- Language style
- Emotional hook
- Target audience fit
- Product selling fit
- Core口播金句

Useful script direction families:

- 反向吐槽 + 理性安利
- 专业/老师/专家视角 + 权威背书
- 细节拆解 + 实测验证
- 同伴互动 + 真实测评
- 性价比算账 + 多场景适配
- 痛点共鸣 + 场景对比
- 时间焦虑 + 高效救赎
- 长期体验 + 回购安利
- 成就感 + 情绪升华
- 专业视角 + 功能拆解

## Step 4: Script Output Requirements

For each generated script, include:

- Script dialogue
- Shot reference
- Narrative logic with arrows
- Copy framework with arrows
- Language style
- Emotional hook

Do not let AI skip audience-context reasoning and jump directly to scripts.
