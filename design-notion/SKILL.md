---
name: design-notion
description: 当用户要求以 Notion 的设计风格生成 UI 时激活。覆盖知识管理、笔记工具、协作文档等场景。Notion 是知识管理标杆，温暖极简、衬线标题、柔和表面。
---

# Design Notion — 知识管理标杆

Notion 设计风格：温暖极简主义，衬线标题（Georgia），柔和表面，Block 编辑理念。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Background | #FFFFFF | 主背景（亮色） |
| Background Dark | #191919 | 主背景（深色） |
| Surface | #F7F6F3 | 温暖灰表面 |
| Surface Hover | #EFEEED | Hover 状态 |
| Border | #E9E9E7 | 边框线 |
| Border Dark | #373737 | 深色边框 |
| Text Primary | #37352F | 主文字（暖灰黑） |
| Text Secondary | #9B9A97 | 次级文字 |
| Text Muted | #787774 | 弱化文字 |
| Accent | #2EAADC | Notion 蓝（链接） |
| Accent Purple | #9065B0 | 紫色标签 |
| Accent Red | #EB5757 | 红色标签 |
| Accent Green | #448361 | 绿色标签 |
| Accent Yellow | #D4A72C | 黄色标签 |
| Accent Orange | #D9730D | 橙色标签 |
| Accent Pink | #DE4AAD | 粉色标签 |

## Typography

| 层级 | 字体 | 字号 | 字重 | 行高 |
|------|------|------|------|------|
| Page Title | Georgia | 28px | 400 | 1.3 |
| H1 | Georgia | 24px | 400 | 1.3 |
| H2 | Georgia | 20px | 400 | 1.3 |
| H3 | Inter | 16px | 600 | 1.4 |
| Body | Inter | 16px | 400 | 1.6 |
| Small | Inter | 14px | 400 | 1.5 |
| Mono | SF Mono / Mono | 15px | 400 | 1.5 |

**关键原则**：Page Title 和 H1/H2 用 Georgia（衬线字体），H3 及以下用 Inter。Block 编辑器文字可内嵌切换格式。

## Component 风格

### 按钮
- **Primary**：#FFFFFF 背景，#37352F 边框，#37352F 文字，圆角 6px
- **Hover**：#F7F6F3 背景
- **Icon Button**：透明背景，灰色图标，圆角 6px

### Block 卡片
- 无边框，无阴影，灰色底部细线分隔
- 左侧拖拽手柄，右侧操作图标（hover 显示）
- 每个 Block 可独立操作

### 页面卡片（Workspace 视图）
- 白色背景，封面图片可选
- 圆角 8px，无阴影
- Emoji + 标题 + 描述

### 输入框
- 透明背景，无边框
- Placeholder 文字 #9B9A97
- Focus 时无视觉变化（融入背景）

### 侧边栏
- 宽度 240px，#FFFFFF 背景
- 灰右边线 1px
- Workspace 名称 + 工作区切换在顶部

## Layout 原则

- **间距基准**：4px 系统，内容区 padding 96px 96px（桌面）
- **最大内容宽度**：900px
- **留白哲学**：大量左右留白，内容居中
- **Block 间距**：Block 之间 2px gap

## 触发方式

用户说"用 Notion 风格"、"做一个笔记编辑器"、"生成知识管理工具"时激活。

## 示例 Prompt

```
"帮我用 Notion 的温暖极简风格做一个 Block 编辑器，Georgia 标题"
"生成一个类似 Notion 的知识管理首页，emoji 图标 + 页面卡片"
"做一个 Notion 风格的侧边栏导航，workspace 切换器"
```
