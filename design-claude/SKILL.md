---
name: design-claude
description: 当用户要求以 Claude（Anthropic）的设计风格生成 UI 时激活。覆盖 AI 聊天界面、温情编辑风格、温暖赤陶色主题的各类 UI 生成场景。
---

# Design Claude — Anthropic 设计风格

Anthropic 的 AI 助手 Claude 的设计风格：温暖赤陶色强调，编辑感布局，大量留白。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #C9544E | 温暖赤陶色，品牌核心色 |
| Primary Dark | #A33D35 | Hover 状态 |
| Background | #FFFFFF | 主背景 |
| Surface | #F7F5F4 | 次级背景 |
| Border | #E8E5E3 | 边框线 |
| Text Primary | #1A1A1A | 主文字 |
| Text Secondary | #6B6B6B | 次级文字 |
| Text Muted | #9B9B9B | 弱化文字 |
| Code Background | #F0EFEE | 代码块背景 |

## Typography

| 层级 | 字体 | 字号 | 字重 | 行高 |
|------|------|------|------|------|
| Display | Georgia | 32px | 400 | 1.3 |
| H1 | Georgia | 28px | 400 | 1.3 |
| H2 | Inter | 22px | 500 | 1.4 |
| H3 | Inter | 18px | 500 | 1.4 |
| Body | Inter | 15px | 400 | 1.6 |
| Small | Inter | 13px | 400 | 1.5 |
| Mono | JetBrains Mono | 14px | 400 | 1.5 |

**关键原则**：标题用 Georgia（衬线），正文用 Inter（无衬线）。这是 Claude 风格的核心对比。

## Component 风格

### 按钮
- **Primary**：赤陶色填充 #C9544E，白色文字，圆角 8px，无阴影
- **Secondary**：白色背景，赤陶色边框，赤陶色文字，圆角 8px
- **Ghost**：透明背景，深色文字，无边框
- **Hover**：Primary 按钮加深 10%

### 对话气泡（AI 响应）
- 背景 #F7F5F4，文字 #1A1A1A
- 左对齐，大圆角 16px
- 顶部无头像位置，左侧留白显示 AI 标识

### 输入框
- 背景 #F7F5F4，边框 1px solid #E8E5E3
- 圆角 12px，内边距 16px
- Focus：边框变为 #C9544E，无阴影

### 卡片
- 白色背景，边框 1px solid #E8E5E3
- 圆角 12px，轻微阴影（0 2px 8px rgba(0,0,0,0.04)）
- 可选：顶部 3px 赤陶色条

### 头像
- 圆形，32px（AI）/ 32px（用户）
- AI 头像：Claude Logo 简化版或圆圈

## Layout 原则

- **间距基准**：4px 系统，间距层级 8/16/24/32/48/64px
- **最大内容宽度**：720px（对话区），1120px（文档区）
- **留白哲学**：大量留白，内容四周至少 24px 边距
- **网格**：12 列网格，卡片宽度 1/2/3/4 列

## 触发方式

用户说以下内容时激活：
- "用 Claude 风格"
- "做一个 Anthropic 风格的 AI 聊天界面"
- "生成赤陶色主题的温暖界面"
- 任何以 Claude 为参考的 UI 生成需求

## 示例 Prompt

```
"帮我用 Claude 的设计风格做一个 AI 助手聊天界面，赤陶色主题，Georgia 标题，温暖留白"
"生成一个类似 Anthropic 官网的 AI 产品 Landing Page，赤陶色按钮，编辑感布局"
"做一个 Claude 风格的对话气泡设计，带赤陶色强调，白色对话背景"
```
