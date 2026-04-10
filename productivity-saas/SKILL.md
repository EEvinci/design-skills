---
name: productivity-saas
description: 当用户要求以生产力工具/SaaS产品的设计风格生成UI时激活。例如："用Notion的风格做笔记应用"、"用Linear风格做项目管理工具"。覆盖知识管理、项目管理、文档工具、自动化等UI场景。
---

# Productivity & SaaS 设计风格 Skills

## 覆盖范围
本 Skill 覆盖以下 7 个生产力与 SaaS 产品的设计风格：

| 产品 | 风格描述 | 核心配色 | 字体 |
|------|---------|---------|------|
| Cal.com | Clean neutral UI, developer-oriented simplicity | White, Neutral Gray | Inter |
| Intercom | Friendly blue palette, conversational UI patterns | Blue #1F8DED, White | Inter |
| Linear | Ultra-minimal, precise, purple accent | Dark #1A1A1A, Purple #8B5CF6 | Inter |
| Mintlify | Clean, green-accented, reading-optimized | White, Green #22C55E | Inter |
| Notion | Warm minimalism, serif headings, soft surfaces | White, Warm Gray | Georgia / Inter |
| Resend | Minimal dark theme, monospace accents | Dark #09090B, White | Mono / Inter |
| Zapier | Warm orange, friendly illustration-driven | Orange #FF4A00, White | Inter |

## 通用设计原则

生产力 SaaS 产品的设计语言：

- **中性底色 + 品牌点缀**：背景多为白/灰，用品牌色做强调
- **文档友好**：Typography 层级清晰，易读性强
- **功能导向**：界面服务于任务效率，不过度装饰
- **响应式**：移动端和桌面端体验一致性好
- **协作元素**：多人编辑、评论、状态指示等协作功能突出

## 各产品详细设计规范

### Linear
- **核心特征**：极致简约，精准对齐，紫色强调
- **按钮**：纯文本按钮或细边框，紫色填充按钮罕见
- **表格**：极窄行高，精确分隔线，图标驱动
- **侧边栏**：极窄，图标为主，悬停显示文字
- **特点**：Issue 列表、Kanban、Roadmap，键盘快捷键无处不在

### Notion
- **核心特征**：温暖极简，衬线标题，柔和表面
- **按钮**：白底灰边，圆角小按钮，柔和阴影
- **卡片**：白色/浅灰背景，无边框，圆角
- **标题**：衬线字体（Georgia）做 H1/H2，正文 Inter
- **特点**：Block 编辑器、嵌套列表、数据库视图

### Resend
- **核心特征**：极简深色主题，Mono 字体点缀
- **按钮**：黑色填充，白色文字，极简
- **代码块**：Mono 字体，品牌绿边框
- **特点**：Email API Dashboard，交易邮件预览

## 触发方式

用户说以下内容时激活：
- "用 Notion/Linear 风格"
- "做一个笔记/文档编辑器"
- "生成一个项目管理界面"
- "做一个类似 Zapier 的自动化平台"

## 示例 Prompt

```
"帮我用 Notion 的温暖极简风格做一个知识管理工具"
"生成一个类似 Linear 的极致简约项目管理界面，紫色点缀"
"做一个类似 Zapier 的自动化流程编辑器，橙色友好风格"
"帮我用 Resend 的极简深色主题做一个 Email API Dashboard"
```
