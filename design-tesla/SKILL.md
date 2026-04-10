---
name: design-tesla
description: 当用户要求以 Tesla 的设计风格生成 UI 时激活。覆盖汽车科技、产品官网、高端硬件等场景。Tesla 是汽车科技标杆，激进减法、电影级全视口摄影、接近零 UI。
---

# Design Tesla — 汽车科技标杆

Tesla 设计风格：激进减法，电影级全视口摄影，接近零 UI，大字体，功能即形式。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #000000 | 纯黑，品牌核心 |
| Primary Dark | #0A0A0A | 深黑背景 |
| Background | #FFFFFF | 主背景（亮色） |
| Text on Dark | #FFFFFF | 深色背景上的文字 |
| Text on Light | #000000 | 亮色背景上的文字 |
| Text Secondary | #5C5C5C | 次级文字（灰） |
| Accent | #CC0000 | Tesla 红（极少使用） |

## Typography

| 层级 | 字体 | 字号 | 字重 |
|------|------|------|------|
| Hero | Tesla Gothic | 72-96px | 300 |
| H1 | Tesla Gothic | 48px | 300 |
| H2 | Tesla Gothic | 36px | 300 |
| Body | Inter | 17px | 400 |
| Caption | Inter | 12px | 400 |

**关键原则**：Tesla Gothic（定制字体，无免费替代，可用 Inter/Geist 近似）。超大字重极轻（300）。大量留白。

## Component 风格

### Hero 首屏
- 全视口高度（100vh），车身大图覆盖
- 文字叠加：白色文字在暗色区域，黑色文字在亮色区域
- 无导航栏装饰，极简

### 按钮
- **Primary**：纯黑填充，白色文字，圆角 4px
- **Secondary**：白色背景，黑色边框，黑色文字，圆角 4px
- **极简**：无阴影、无发光、无多余样式

### 导航栏
- 固定顶部，透明背景
- Logo 左，链接居中，菜单右
- 滚动时背景变黑

### 配置器
- 全屏界面，左侧参数选项，右侧大图
- 数字显示参数值，简洁

### 卡片/产品块
- 无边框，无阴影
- 大图 + 小标题 + 简短描述

## Layout 原则

- **间距基准**：8px 系统，但大量负空间
- **全屏理念**：Hero 和关键 section 充满整个视口
- **减法哲学**：能去掉的元素就去掉
- **摄影主导**：汽车图片是绝对视觉中心

## 触发方式

用户说"用 Tesla 风格"、"做一个科技产品官网"、"生成全屏摄影界面"时激活。

## 示例 Prompt

```
"帮我用 Tesla 的激进减法风格做一个科技产品官网，全屏大图，极少 UI"
"生成一个类似 Tesla 官网的 Hero 首屏，车身大图覆盖 100vh"
"做一个 Tesla 风格的产品配置器，左侧参数，右侧全屏图"
```
