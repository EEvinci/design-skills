---
name: design-linear
description: 当用户要求以 Linear 的设计风格生成 UI 时激活。覆盖项目管理、Bug 追踪、开发者工具等场景。Linear 是项目管理标杆，极致简约、精准对齐、紫色点缀。
---

# Design Linear — 项目管理标杆

Linear 设计风格：极致简约，精准对齐，紫色强调，键盘优先，Dark-first。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Background | #0D0D0F | 主背景（极深黑） |
| Surface | #16161A | 次级背景 |
| Surface Elevated | #1E1E24 | 浮层背景 |
| Border | #29292F | 边框线 |
| Border Subtle | #1F1F26 | 细边框 |
| Text Primary | #EDEDEF | 主文字 |
| Text Secondary | #8A8A8E | 次级文字 |
| Text Muted | #55555A | 弱化文字 |
| Accent | #8B5CF6 | 品牌紫 |
| Accent Hover | #7C3AED | Hover |
| Accent Subtle | rgba(139,92,246,0.15) | 紫色浮层背景 |
| Success | #22C55E | 成功 |
| Warning | #F59E0B | 警告 |
| Error | #EF4444 | 错误 |
| Critical | #DC2626 | 紧急/关键 |

## Typography

| 层级 | 字体 | 字号 | 字重 | 行高 |
|------|------|------|------|------|
| Display | Inter | 24px | 600 | 1.3 |
| H1 | Inter | 16px | 600 | 1.4 |
| H2 | Inter | 14px | 500 | 1.4 |
| Body | Inter | 14px | 400 | 1.5 |
| Small | Inter | 12px | 400 | 1.4 |
| Tiny | Inter | 11px | 500 | 1.3 |
| Mono | Inter | 13px | 400 | 1.5 |

**关键原则**：字号整体偏小（Body 14px），极窄行高，精确间距，按钮可无文字仅图标。

## Component 风格

### 按钮
- **Primary**：紫色填充 #8B5CF6，白色文字，圆角 6px
- **Secondary**：透明背景，#29292F 边框，灰色文字
- **Ghost**：透明背景，无边框，灰色文字
- **Icon Button**：24x24px，透明背景，图标灰色，hover 紫色

### Issue 行（核心组件）
- 行高 32px，极窄 padding
- 左侧：状态图标（彩色圆点）+ 标题
- 右侧：优先级图标 + 负责人头像
- Hover：整行 background → Surface

### 状态图标
- 圆角方形，8x8px，带颜色
- Backlog：灰 #55555A，Todo：蓝 #3B82F6，In Progress：紫 #8B5CF6，Done：绿 #22C55E

### 侧边栏
- 宽度 240px，可折叠
- 图标 + 文字，行高 28px
- 当前选中：紫色背景浮层

### 表格
- 无边框，行之间用细虚线分隔
- 表头：小号大写文字，#55555A

## Layout 原则

- **间距基准**：4px 系统，极窄间距
- **最大内容宽度**：无限制，全屏利用
- **Grid**：紧凑网格，信息密度高
- **极简哲学**：能用一个字不用两个词

## 触发方式

用户说"用 Linear 风格"、"做一个项目管理工具"、"生成极致简约 Dark UI"时激活。

## 示例 Prompt

```
"帮我用 Linear 的极致简约风格做一个 Bug 追踪界面，深色主题，紫色强调"
"生成一个类似 Linear 的 Issue 列表，32px 行高，状态图标驱动"
"做一个 Linear 风格的侧边栏导航，极窄间距，键盘优先"
```
