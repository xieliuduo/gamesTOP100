# 经典街机游戏精选 TOP 100 | Classic Arcade Games TOP 100

> 一份精心整理的经典街机游戏榜单，支持多维度筛选与评分展示。
> A curated list of the greatest classic arcade games with multi-dimensional ratings and filtering.

**在线预览 | Live Demo**: [https://xieliuduo.github.io/gamesTOP100/](https://xieliuduo.github.io/gamesTOP100/)

---

## 项目简介 | About

本项目收录了 100 款经典街机游戏，数据来源于真实街机历史资料，涵盖格斗、射击、动作、益智等多种类型。页面以卡片形式展示每款游戏的综合评分、人气、经典度、推荐度等维度数据，并支持多种筛选与排序方式。

This project features 100 classic arcade games sourced from real arcade history, spanning genres such as fighting, shooting, action, and puzzle. Each game is displayed as a card with scores across popularity, classic rating, recommendation, and fun score, with flexible filtering and sorting options.

---

## 功能特性 | Features

- **TOP 100 榜单** — 按综合评分排序，真实数据支撑
  **TOP 100 Ranking** — Sorted by composite score, backed by real data
- **多维度评分** — 人气、经典度、推荐度、趣味分全面呈现
  **Multi-dimensional Scores** — Popularity, Classic Rating, Recommendation & Fun Score
- **分类筛选** — 按游戏类型（格斗、射击、动作等）快速过滤
  **Category Filter** — Quickly filter by genre (Fighting, Shooting, Action, etc.)
- **多种排序** — 支持按综合分、人气、经典度、年份等排序
  **Multiple Sort Options** — Sort by overall score, popularity, classic rating, year, etc.
- **双语展示** — 游戏名称中英文对照
  **Bilingual Display** — Chinese & English game names side by side
- **暗黑主题** — 赛博朋克风格 UI，沉浸式街机体验
  **Dark Theme** — Cyberpunk-style UI for an immersive arcade feel

---

## 技术栈 | Tech Stack

| 技术 | 说明 |
|------|------|
| HTML5 | 页面结构 |
| CSS3 | 动画、渐变、响应式布局 |
| Vanilla JS | 数据渲染、筛选逻辑 |
| GitHub Pages | 静态托管 |

No frameworks, no dependencies — pure HTML/CSS/JS.

---

## 本地运行 | Run Locally

```bash
git clone https://github.com/xieliuduo/gamesTOP100.git
cd gamesTOP100
# 用浏览器直接打开 index.html
open index.html
```

---

## 数据说明 | Data

游戏数据存储于 `games-data.js`，每条记录包含：

| 字段 | 说明 | Field | Description |
|------|------|-------|-------------|
| `zh` | 中文名 | `en` | English name |
| `category` | 游戏类型 | `year` | 发行年份 |
| `popularity` | 人气评分 (0-100) | `classic` | 经典度 (0-100) |
| `recommendation` | 推荐度 (0-100) | `fun_score` | 综合趣味分 |
| `manufacturer` | 厂商 | `players` | 游戏模式 |

---

## License

MIT
