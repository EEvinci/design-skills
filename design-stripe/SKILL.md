---
name: design-stripe
description: 当用户要求以 Stripe 的设计风格生成 UI 时激活。覆盖支付界面、API 文档、金融 SaaS 等场景。Stripe 是支付 UI 标杆，紫色渐变 + 300 字重优雅风格。
---

# Design Stripe — 支付 UI 标杆

Stripe 设计风格：标志性紫色渐变，weight-300 优雅字体，精密克制。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #635BFF | Stripe 紫，品牌核心 |
| Primary Dark | #5147C5 | Hover 状态 |
| Primary Light | #8B7FFF | 浅色变体 |
| Gradient Start | #635BFF | 渐变起点 |
| Gradient End | #A259FF | 渐变终点（45deg） |
| Background | #FFFFFF | 主背景 |
| Surface | #F6F9FC | 次级背景 |
| Border | #E6E8EF | 边框线 |
| Text Primary | #1A1A2E | 主文字 |
| Text Secondary | #6B7A99 | 次级文字 |
| Success | #30D158 | 成功状态 |
| Error | #FF3B30 | 错误状态 |

## Typography

| 层级 | 字体 | 字号 | 字重 | 行高 |
|------|------|------|------|------|
| Display | Inter | 40px | 300 | 1.2 |
| H1 | Inter | 28px | 300 | 1.3 |
| H2 | Inter | 22px | 300 | 1.4 |
| H3 | Inter | 17px | 400 | 1.4 |
| Body | Inter | 15px | 300 | 1.6 |
| Small | Inter | 13px | 400 | 1.5 |
| Mono | JetBrains Mono | 14px | 400 | 1.5 |

**关键原则**：300 字重（Light/Thin）是 Stripe 的标志性特征。所有标题和正文都用极细字重。

## Component 风格

### 按钮
- **Primary**：紫色渐变填充（135deg #635BFF → #A259FF），白色文字 weight-300，圆角 6px，无阴影
- **Secondary**：白色背景，紫色边框，紫色文字，圆角 6px
- **Hover**：渐变更饱和，轻微上移（translateY -1px）

### 卡片
- 白色背景，边框 1px solid #E6E8EF
- 圆角 8px，阴影 0 1px 3px rgba(0,0,0,0.08)
- 可选：顶部 2px 紫色渐变条

### 输入框
- 白色背景，边框 1px solid #E6E8EF
- 圆角 6px，内边距 12px 16px
- Focus：边框 2px solid #635BFF

## Layout 原则

- **间距基准**：8px 系统，间距层级 8/16/24/32/48/64px
- **最大内容宽度**：1200px
- **Grid**：12 列网格，gutter 24px

## 触发方式

用户说"用 Stripe 风格"、"做一个支付界面"、"生成紫色渐变 Fintech 界面"时激活。

## 示例 Prompt

```
"帮我用 Stripe 的紫色渐变风格做一个支付结账页面，300 字重字体"
"生成一个类似 Stripe Dashboard 的金融 SaaS 界面，卡片式网格布局"
```
