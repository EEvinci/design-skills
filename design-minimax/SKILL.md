---
name: design-minimax
description: 当用户要求以 Minimax 的设计风格生成 UI 时激活。覆盖 AI 产品、生成式 AI 应用、智能交互界面等场景。Minimax 是 AI 产品标杆，大胆深色界面 + 霓虹蓝/紫光效。
---

# Design Minimax — AI 产品标杆

Minimax 设计风格：大胆深色界面，霓虹蓝/紫色光效，科技感 AI 交互。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #00BFFF | 霓虹蓝，品牌核心 |
| Primary Glow | #00D4FF | 发光效果 |
| Accent | #7C3AED | 紫色点缀 |
| Accent Glow | #8B5CF6 | 紫色光晕 |
| Background | #0D0D0F | 主背景（深黑） |
| Surface | #151518 | 次级背景 |
| Surface Elevated | #1A1A1F | 浮层背景 |
| Border | #2A2A30 | 边框线 |
| Text Primary | #FFFFFF | 主文字 |
| Text Secondary | #8A8A9A | 次级文字 |
| Text Muted | #55555F | 弱化文字 |

## Typography

| 层级 | 字体 | 字号 | 字重 |
|------|------|------|------|
| Display | Inter | 48px | 700 |
| H1 | Inter | 32px | 600 |
| H2 | Inter | 24px | 600 |
| H3 | Inter | 18px | 500 |
| Body | Inter | 15px | 400 |
| Small | Inter | 13px | 400 |
| Mono | JetBrains Mono | 14px | 400 |

## Component 风格

### 按钮
- **Primary**：霓虹蓝填充 #00BFFF，深色文字，glow 效果
- **Secondary**：透明背景，霓虹蓝边框，hover 发光
- **Glow**：box-shadow 0 0 20px rgba(0,191,255,0.4)

### 输入框
- 深黑背景 #151518，细霓虹蓝边框
- Focus：霓虹蓝发光 box-shadow

### 卡片
- 深灰背景 #151518，细边框 #2A2A30
- 可选：顶部霓虹蓝/紫渐变边线
- Hover：边框变为霓虹蓝

### AI 交互元素
- 对话气泡：深灰背景 + 底部霓虹蓝细线
- 光效：渐变光晕背景，模拟 AI 处理

## Layout 原则

- **间距基准**：8px 系统
- **最大内容宽度**：1200px
- **光效原则**：可用 CSS box-shadow 模拟霓虹光晕

## 触发方式

用户说"用 Minimax 风格"、"做一个 AI 生成界面"、"生成霓虹光效深色 UI"时激活。

## 示例 Prompt

```
"帮我用 Minimax 的霓虹蓝+紫色光效风格做一个 AI 生成界面"
"生成一个类似 Minimax 的深色 AI 交互面板，带发光边框效果"
```
