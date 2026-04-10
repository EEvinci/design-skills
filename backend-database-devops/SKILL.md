---
name: backend-database-devops
description: 当用户要求以后端/数据库/DevOps产品的设计风格生成UI时激活。例如："用PostHog的风格做数据分析仪表盘"、"用Supabase风格做数据库管理界面"。覆盖数据可视化、监控、数据库管理等UI场景。
---

# Backend, Database & DevOps 设计风格 Skills

## 覆盖范围
本 Skill 覆盖以下 8 个后端/数据库/DevOps 产品的设计风格：

| 产品 | 风格描述 | 核心配色 | 字体 |
|------|---------|---------|------|
| ClickHouse | Yellow-accented, technical documentation style | Dark #0D0D0D, Yellow #FFCC00 | Inter / JetBrains Mono |
| Composio | Modern dark with colorful integration icons | Dark, Multi-color Icons | Inter |
| HashiCorp | Enterprise-clean, black and white | Pure Black, Pure White | Hashi Sans |
| MongoDB | Green leaf branding, developer documentation focus | Green #00ED64, Dark | MongoDB Font / Inter |
| PostHog | Playful hedgehog branding, developer-friendly dark UI | Orange #F9BD2B, Dark | Inter |
| Sanity | Red accent, content-first editorial layout | Red #E63329, White | Inter |
| Sentry | Dark dashboard, data-dense, pink-purple accent | Dark #1A1A2E, Pink #FF6B9D | Inter |
| Supabase | Dark emerald theme, code-first | Emerald #1B873F, Dark | Inter / Mono |

## 通用设计原则

后端/DevOps 产品的设计语言：

- **深色 + 数据密集**：Dashboard 是核心界面类型
- **代码展示优先**：SQL、JSON、代码块样式完善
- **图表丰富**：折线图、柱状图、表格等数据可视化
- **企业感**：Clean、专业、可信，不花哨
- **功能分区明确**：侧边导航 + 主内容区 + 顶部状态栏

## 各产品详细设计规范

### Supabase
- **核心特征**：深翡翠绿主题，代码优先理念
- **按钮**：翡翠绿填充，白色文字，直角
- **代码块**：深色背景 + 翡翠绿语法高亮
- **侧边栏**：深色，绿色图标激活态
- **特点**：Table Editor、SQL Editor、API Docs 风格

### PostHog
- **核心特征**：橙黄色品牌，俏皮的品牌形象
- **按钮**：橙色填充，hover 变深
- **卡片**：深灰背景 + 橙色顶部细边
- **图表**：橙黄色数据线，深色网格背景
- **特点**：Product Analytics、Cohort 表格、Funnel 可视化

### Sentry
- **核心特征**：深色 Dashboard，数据密度高，粉紫色点缀
- **按钮**：粉紫渐变，圆角，精致
- **错误卡片**：深色背景，红色错误级别标签
- **侧边栏**：窄，图标为主，悬停显示标签
- **特点**：Error Tracking、Performance、面包屑导航

## 触发方式

用户说以下内容时激活：
- "用 Supabase/PostHog/Sentry 风格"
- "做一个数据分析仪表盘"
- "生成一个数据库管理界面"
- "做一个类似 HashiCorp 的企业级界面"

## 示例 Prompt

```
"帮我用 Supabase 的翡翠绿风格做一个开源数据库管理界面"
"生成一个类似 PostHog 的产品数据分析 Dashboard，深色主题"
"做一个类似 Sentry 的错误监控界面，数据密集型深色布局"
"帮我用 ClickHouse 的黄黑配色做一个 SQL 查询编辑器界面"
```
