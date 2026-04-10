---
name: developer-tools
description: 当用户要求以开发者工具/IDE产品的设计风格生成UI时激活。例如："用Cursor的风格做代码编辑器"、"用Vercel风格做开发者文档"、"用Raycast风格做快捷命令面板"。覆盖开发者工具、IDE、命令行界面、部署平台等UI生成场景。
---

# Developer Tools & IDEs 设计风格 Skills

## 覆盖范围
本 Skill 覆盖以下 7 个开发者工具与 IDE 产品的设计风格：

| 产品 | 风格描述 | 核心配色 | 字体 |
|------|---------|---------|------|
| Cursor | Sleek dark interface, gradient accents | Dark #1E1E1E, Gradient Purple-Blue | Inter |
| Expo | Dark theme, tight letter-spacing, code-centric | Dark, Expo Pink #000020 | Inter / Mono |
| Lovable | Playful gradients, friendly dev aesthetic | Gradient Blue-Purple, White | Inter |
| Raycast | Sleek dark chrome, vibrant gradient accents | Dark Chrome, Gradient Blue | SF Pro |
| Superhuman | Premium dark UI, keyboard-first, purple glow | Deep Dark, Purple Glow | Inter |
| Vercel | Black and white precision, Geist font | Pure White, Pure Black | Geist |
| Warp | Dark IDE-like interface, block-based command UI | Dark #0D0D0D, Accent Green | JetBrains Mono |

## 通用设计原则

开发者工具类产品有以下共同设计语言：

- **深色优先**：大多数采用深色主题，保护开发者眼睛
- **代码美学**：Monospace 字体在代码展示区域，等宽精确
- **键盘优先**：快捷键提示、keyboard-first 交互设计
- **信息密度**：高密度信息展示但保持清晰可读
- **精致细节**：光标、滚动条、选中状态等细节打磨到位

## 各产品详细设计规范

### Cursor
- **核心特征**：极简深色界面，渐变紫色点缀，IDE 感强
- **按钮**：圆角，渐变填充，hover 时轻微发光
- **编辑器区域**：深色背景，语法高亮，流畅动画
- **侧边栏**：暗色折叠面板，图标 + 文字标签
- **特点**：Tab 切换、代码补全浮层、命令面板

### Vercel
- **核心特征**：黑白精度，Geist 字体，极简主义
- **按钮**：纯黑/纯白，无圆角，直角矩形
- **卡片**：白色背景，细黑边框，极简
- **字体**：Geist（Vercel 专属字体），无衬线
- **特点**：Dashboard 以网格为主，部署卡片式展示

### Raycast
- **核心特征**：类 macOS 窗口风格，渐变高亮，暗铬质感
- **弹出面板**：半透明深色毛玻璃效果
- **搜索栏**：顶部居中，大圆角，图标在左
- **列表项**：左侧图标 + 右侧快捷键提示
- **特点**：键盘导航优先，command 菜单风格

### Warp
- **核心特征**：终端块状命令 UI，IDE 质感
- **终端输出**：块状分隔，每个命令-输出一个 block
- **输入**：块底部闪烁光标，zsh 风格
- **侧边栏**：目录树，文件图标，代码结构
- **特点**：Rust 代码编辑器级别的高亮与动画

## 触发方式

用户说以下内容时激活本 Skill：
- "用 Cursor/Vercel/Warp 风格"
- "做一个类似 Raycast 的命令面板"
- "生成一个开发者文档首页"
- "做一个 IDE 风格的代码编辑器界面"
- 任何提及上述 7 个开发者工具设计风格的需求

## 示例 Prompt

```
"帮我用 Cursor 的设计风格做一个 AI 代码编辑器界面，深色主题带紫色渐变"
"生成一个类似 Vercel 的开发者部署 Dashboard，黑白极简风格"
"做一个类似 Raycast 的命令搜索面板，半透明毛玻璃效果"
"帮我用 Warp 的终端风格做一个命令行工具管理界面"
"做一个类似 Superhuman 的快捷键优先邮件客户端界面"
```
