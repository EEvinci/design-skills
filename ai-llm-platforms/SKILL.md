---
name: ai-llm-platforms
description: 当用户要求以某个特定网站/产品的设计风格生成UI时激活。例如："用Claude的风格做聊天界面"、"生成一个Minimax风格的AI交互页面"、"用RunwayML风格做视频生成界面"。覆盖AI coding、设计风格迁移、UI生成场景。
---

# AI & LLM Platforms 设计风格 Skills

## 覆盖范围
本 Skill 覆盖以下 12 个 AI/LLM 平台产品的设计风格：

| 产品 | 风格描述 | 核心配色 | 字体 |
|------|---------|---------|------|
| Claude | Warm terracotta accent, clean editorial layout | Terracotta #C9544E, Warm White | Inter / Editorial Serif |
| Cohere | Vibrant gradients, data-rich dashboard aesthetic | Gradient Blue-Purple, Deep Navy | Inter |
| ElevenLabs | Dark cinematic UI, audio-waveform aesthetics | Deep Black, Electric Purple | Inter |
| Minimax | Bold dark interface with neon accents | Dark #0D0D0D, Neon Blue #00BFFF | Inter |
| Mistral AI | French-engineered minimalism, purple-toned | Deep Purple #7C3AED, Light Lavender | Inter |
| Ollama | Terminal-first, monochrome simplicity | Pure Black, Pure White | SF Mono / JetBrains Mono |
| OpenCode AI | Developer-centric dark theme | Dark Gray, Green Accent | JetBrains Mono |
| Replicate | Clean white canvas, code-forward | White, Blue Accent #2563EB | Inter / Mono |
| RunwayML | Cinematic dark UI, media-rich layout | Deep Black, Gradient Purple | Inter |
| Together AI | Technical, blueprint-style design | Blueprint Blue #1E40AF, White | JetBrains Mono |
| VoltAgent | Void-black canvas, emerald accent, terminal-native | Pure Black #000000, Emerald #10B981 | JetBrains Mono |
| xAI | Stark monochrome, futuristic minimalism | Pure Black, White | Inter |

## 通用设计原则

AI & LLM 平台类产品的设计语言有以下共同特征：

- **深色为主**：大多数平台采用深色主题，强调专业感与技术深度
- **代码友好**：Monospace 字体广泛用于代码展示区域
- **AI 元素**：波形图、光晕效果、渐变光效常见于交互元素
- **数据密度**：Dashboard 风格的信息展示，表格与卡片并存
- **精准克制**：不花哨，功能性与美学平衡

## 各产品详细设计规范

### Claude（Anthropic）
- **核心特征**：温暖赤陶色点缀、编辑感布局、大量留白
- **按钮**：圆角矩形，terracotta 填充色，白色文字
- **卡片**：白色/浅灰背景，轻微阴影，顶部可有赤陶色细边
- **输入框**：大圆角，浅灰背景，深色文字
- **特点**：对话气泡设计，左对齐 AI 响应，右侧对话列表

### Minimax
- **核心特征**：大胆深色界面 + 霓虹蓝/紫色点缀
- **按钮**：深灰背景 + 霓虹蓝边框 hover 发光效果
- **卡片**：几乎纯黑背景 + 霓虹蓝渐变边框
- **输入框**：深黑背景 + 细霓虹蓝边框，聚焦时发光
- **特点**：AI 交互场景感强，类似游戏 UI 的精致感

### RunwayML
- **核心特征**：电影级深色 UI，媒体富文本布局
- **按钮**：渐变紫填充，按钮文字带微光
- **卡片**：深黑背景，渐变边线，视频预览卡片为主
- **特点**：视频/图像预览占据视觉中心，timeline UI

### VoltAgent
- **核心特征**：虚空黑画布，翡翠绿高亮，终端原生感
- **按钮**：透明背景 + 翡翠绿边框，极简
- **卡片**：全黑背景 + 细翡翠绿分隔线
- **特点**：终端输出风格，代码块高亮，monospace 为主

### Ollama
- **核心特征**：终端优先，单色极简
- **按钮**：无装饰，线条按钮，纯白文字
- **卡片**：纯黑背景，纯白文字，极简分隔线
- **特点**：本地 AI，Terminal 输出风格，无多余装饰

## 触发方式

用户说以下内容时激活本 Skill：
- "用 Claude/Minimax/RunwayML 风格"
- "生成一个 AI 聊天界面"
- "做一个类似 VoltAgent 的终端界面"
- "用 Mistral AI 风格做界面"
- 任何提及上述 12 个 AI 平台设计风格的需求

## 示例 Prompt

```
"帮我用 Claude 的设计风格做一个 AI 助手聊天界面，要有温暖的赤陶色主题"
"生成一个类似 Minimax 的深色 AI 交互界面，带霓虹蓝色光效"
"做一个类似 RunwayML 的视频生成平台首页，带电影级深色主题"
"帮我用 Ollama 的终端极简风格做一个本地模型管理界面"
"做一个类似 VoltAgent 的 AI Agent 面板，黑底翡翠绿强调色"
```
