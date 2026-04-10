---
name: design-vercel
description: 当用户要求以 Vercel 的设计风格生成 UI 时激活。覆盖开发者平台、部署工具、API 文档等场景。Vercel 是开发者平台标杆，黑白精度 + Geist 字体。
---

# Design Vercel — 开发者平台标杆

Vercel 设计风格：黑白精度，Geist 字体，极简主义，开发者美学。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #000000 | 纯黑，品牌核心 |
| Background | #FFFFFF | 主背景（纯白） |
| Surface | #F7F7F8 | 次级背景 |
| Border | #E5E5E5 | 边框线 |
| Border Dark | #333333 | 深色边框 |
| Text Primary | #000000 | 主文字 |
| Text Secondary | #666666 | 次级文字 |
| Text Muted | #999999 | 弱化文字 |
| Accent | #000000 | 黑色强调 |

## Typography

| 层级 | 字体 | 字号 | 字重 | 行高 |
|------|------|------|------|------|
| Display | Geist | 64px | 500 | 1.1 |
| H1 | Geist | 40px | 500 | 1.15 |
| H2 | Geist | 28px | 500 | 1.2 |
| H3 | Geist | 20px | 500 | 1.3 |
| Body | Geist | 16px | 400 | 1.5 |
| Small | Geist | 14px | 400 | 1.5 |
| Mono | Geist Mono | 14px | 400 | 1.5 |

**关键原则**：纯黑白双色，无灰色渐变区域。Geist 字体是 Vercel 标志（无免费版，可用 Inter 近似）。

## Component 风格

### 按钮
- **Primary**：纯黑填充，白色文字，无圆角（直角）
- **Secondary**：白色背景，纯黑边框，纯黑文字
- **Ghost**：透明背景，无边框，黑色文字
- **无圆角**：所有按钮均用直角矩形

### 卡片
- 白色背景，1px 纯黑边框 #000000
- 无阴影，无圆角
- 可选：顶部黑色粗线

### 部署卡片
- 白色背景，黑框
- 状态标签：彩色圆点（成功绿/错误红）

### Dashboard 布局
- 网格卡片系统，gutter 16px
- 数字大而醒目（Display size）

### Logo
- 纯黑 Vercel Logo，白色文字版本用于深色背景

## Layout 原则

- **间距基准**：4px 系统，紧凑间距
- **最大内容宽度**：1200px
- **精度哲学**：每个元素位置都精确对齐
- **无装饰**：没有阴影、没有渐变、没有多余圆角

## 触发方式

用户说"用 Vercel 风格"、"做一个开发者平台界面"、"生成黑白极简 UI"时激活。

## 示例 Prompt

```
"帮我用 Vercel 的纯黑白精度风格做一个开发者部署平台界面"
"生成一个类似 Vercel Dashboard 的卡片式管理界面，直角边框，无阴影"
```
