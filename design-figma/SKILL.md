---
name: design-figma
description: 当用户要求以 Figma 的设计风格生成 UI 时激活。覆盖设计工具、协作平台、UI 编辑器等场景。Figma 是设计工具标杆，多彩活泼、专业精准、紫色品牌色。
---

# Design Figma — 设计工具标杆

Figma 设计风格：多彩活泼，专业精准，紫色品牌（#A259FF），深色工具栏 + 白色画布。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #A259FF | Figma 紫，品牌核心 |
| Primary Light | #E8D5FF | 浅色变体 |
| Background | #FFFFFF | 画布背景 |
| Toolbar | #1E1E1E | 工具栏深色 |
| Surface | #2C2C2C | 侧边栏背景 |
| Surface Light | #F5F5F5 | 面板背景 |
| Border | #E5E5E5 | 边框线 |
| Border Dark | #3D3D3D | 深色边框 |
| Text Dark BG | #CCCCCC | 深色背景上的文字 |
| Text Primary | #333333 | 主文字 |
| Text Secondary | #999999 | 次级文字 |
| Text Inverse | #FFFFFF | 反色文字 |

## Typography

| 层级 | 字体 | 字号 | 字重 | 行高 |
|------|------|------|------|------|
| Display | Inter | 13px | 500 | 1.3 |
| Body | Inter | 13px | 400 | 1.4 |
| Small | Inter | 11px | 400 | 1.3 |
| Label | Inter | 11px | 500 | 1.2 |
| Tiny | Inter | 10px | 400 | 1.2 |

**关键原则**：Figma 使用统一的 13px 字号体系。字体偏小以适应工具密度，所有层级通过字重和颜色区分。

## Component 风格

### 工具栏
- 深色 #1E1E1E，宽度 48px，图标为主
- 图标：24x24px，#CCCCCC，激活时 #FFFFFF
- 选中态：紫色圆点 #A259FF 指示

### 画布
- 白色背景，支持网格
- 设计框带圆角和阴影

### 属性面板
- 白色背景，右侧
- 分组标题：11px 大写，灰色
- 输入框：深色边框，聚焦时紫色边框

### 组件/样式卡片
- 缩略图 + 标签，圆角 8px
- Hover：边框变为紫色

### 侧边栏（图层面板）
- 深灰背景 #2C2C2C
- 图层名称：13px 白色，右侧操作图标
- 展开/折叠：箭头图标

## Layout 原则

- **三栏布局**：左侧工具栏 48px + 左侧面板 240px + 画布（自适应）+ 右侧属性面板 280px
- **间距基准**：4px 系统
- **密度**：高密度信息，元素紧凑
- **动画**：拖拽流畅，属性切换快速

## 触发方式

用户说"用 Figma 风格"、"做一个设计工具界面"、"生成协作设计平台"时激活。

## 示例 Prompt

```
"帮我用 Figma 的深色工具栏 + 白色画布风格做一个设计编辑器界面"
"生成一个类似 Figma 的图层管理面板，深灰背景，紫色选中态"
"做一个 Figma 风格的属性编辑面板，三栏布局，图标驱动"
```
