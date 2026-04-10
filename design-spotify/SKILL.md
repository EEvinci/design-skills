---
name: design-spotify
description: 当用户要求以 Spotify 的设计风格生成 UI 时激活。覆盖音乐 App、音频平台、流媒体等场景。Spotify 是音乐 App 标杆，绿色 #1DB954 + 深色主题 + 专辑封面驱动。
---

# Design Spotify — 音乐 App 标杆

Spotify 设计风格：深色 + 鲜艳绿色 #1DB954，大字体，专辑封面驱动，播放列表美学。

## Color Palette

| Token | Hex | Role |
|-------|-----|------|
| Primary | #1DB954 | Spotify 绿，品牌核心 |
| Primary Dark | #169C46 | Hover 状态 |
| Background | #000000 | 主背景（纯黑） |
| Surface | #121212 | 次级背景 |
| Surface Elevated | #181818 | 卡片面板 |
| Surface High | #1F1F1F | 高层表面 |
| Border | #282828 | 细边框 |
| Text Primary | #FFFFFF | 主文字 |
| Text Secondary | #B3B3B3 | 次级文字 |
| Text Muted | #6A6A6A | 弱化文字 |

## Typography

| 层级 | 字体 | 字号 | 字重 |
|------|------|------|------|
| Display | Spotify Circular | 48px | 700 |
| H1 | Spotify Circular | 32px | 700 |
| H2 | Spotify Circular | 24px | 700 |
| H3 | Inter | 16px | 500 |
| Body | Inter | 14px | 400 |
| Small | Inter | 11px | 400 |

## Component 风格

### 侧边栏
- 纯黑背景，宽度 280px
- 导航项：白色文字，激活时绿色左侧竖线
- Logo：Spotify 绿白 Logo

### 专辑卡片
- 正方形封面，圆角 8px
- 下方：白色标题 + 灰色艺术家名
- Hover：封面轻微放大，播放按钮从底部滑出

### 播放栏（底部固定）
- 高度 80px，纯黑背景
- 进度条：绿色 #1DB954，已播放灰色

## Layout 原则

- 三栏布局：侧边栏 280px + 主内容 + 右栏 280px
- 底部固定播放栏 80px
- 专辑卡片 5-6 列网格

## 触发方式

用户说"用 Spotify 风格"、"做一个音乐播放器"、"生成深色音乐 App"时激活。

## 示例 Prompt

```
"帮我用 Spotify 的深黑+绿色风格做一个音乐播放器界面"
"生成一个类似 Spotify 的播放列表管理页面，纯黑背景"
```
