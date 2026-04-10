---
name: design-apple
description: 当用户要求以 Apple 的设计风格生成 UI 时激活。覆盖高端消费电子、品牌官网、产品页面等场景。Apple 是高端消费品标杆，SF Pro + 大量留白 + 电影级摄影。
---

# Design Apple — 高端消费品标杆

Apple 设计风格：大量留白，SF Pro 字体，电影级摄影，精致克制。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #0071E3 | iOS Blue，CTA 按钮色 |
| Primary Dark | #0077ED | Hover 状态 |
| Background | #FFFFFF | 主背景 |
| Surface | #F5F5F7 | 浅灰表面 |
| Text Primary | #1D1D1F | 主文字（近黑） |
| Text Secondary | #6E6E73 | 次级文字 |
| Text Tertiary | #86868B | 弱化文字 |
| Border | #D2D2D7 | 细边框 |
| Black | #000000 | 纯黑（深色模式） |
| Accent Gray | #48484A | 深色模式文字 |

## Typography

| 层级 | 字体 | 字号 | 字重 | 行高 |
|------|------|------|------|------|
| Hero | SF Pro Display | 48-80px | 600 | 1.1 |
| H1 | SF Pro Display | 40px | 600 | 1.1 |
| H2 | SF Pro Display | 32px | 600 | 1.15 |
| H3 | SF Pro Display | 24px | 600 | 1.25 |
| Body | SF Pro Text | 17px | 400 | 1.47 |
| Caption | SF Pro Text | 12px | 400 | 1.4 |
| Label | SF Pro Text | 12px | 500 | 1.3 |

**关键原则**：SF Pro（系统字体），极细字重，大号标题，紧行高。

## Component 风格

### 按钮
- **Primary**：iOS Blue 填充 #0071E3，白色文字，圆角 22px（胶囊形）
- **Secondary**：透明背景，蓝色边框，蓝色文字，圆角 22px
- **文字链接**：蓝色文字 #0071E3，下划线 on hover
- **Hover**：背景加深 10%

### Hero Section
- 全出血大图，文字叠加在图片上
- 白色文字置中（深色背景）或左对齐
- 超大标题，简洁副标题

### 卡片
- 白色背景，无边框，圆角 18px
- 可选：轻微阴影 0 4px 16px rgba(0,0,0,0.08)
- 图文比例：图片占 60%+

### 导航栏
- 固定顶部，白色背景，底部细灰线
- 居中 Logo，右侧链接
- 滚动时背景变模糊（毛玻璃）

## Layout 原则

- **间距基准**：8px 系统，超大间距 64/80/120px
- **最大内容宽度**：980px（官网）/ 1470px（大屏）
- **留白哲学**：极大量留白，内容区占据屏幕 < 50%
- **网格**：简单 12 列，gutter 22px

## 触发方式

用户说"用 Apple 风格"、"做一个高端产品页"、"生成 SF Pro 字体界面"时激活。

## 示例 Prompt

```
"帮我用 Apple 的设计风格做一个高端科技产品官网，大量留白，SF Pro 字体"
"生成一个类似 Apple 官网的 Hero 首屏，超大标题，电影级产品摄影"
"做一个 Apple 风格的导航栏，固定顶部，毛玻璃背景"
```
