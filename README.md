<div align="center">

# Minesweeper扫雷

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=1200&color=6750A4&center=true&vCenter=true&width=520&lines=%E8%AF%BB%E6%87%82%E6%95%B0%E5%AD%97%EF%BC%8C%E5%86%8D%E8%B5%B0%E4%B8%8B%E4%B8%80%E6%AD%A5%EF%BC%9B%E7%BA%AF%E5%8E%9F%E7%94%9F%E5%8D%95%E6%96%87%E4%BB%B6%E6%89%AB%E9%9B%B7%EF%BC%9B%E7%BB%8F%E5%85%B8+%2F+%E6%97%A0%E7%8C%9C%E5%8F%8C%E6%A8%A1%E5%BC%8F%EF%BC%9B%E4%B8%8B%E8%BD%BD%E5%8D%B3%E7%8E%A9%EF%BC%8C%E9%9B%B6%E4%BE%9D%E8%B5%96)](https://cizuwuxin.github.io/minesweeper/)

![Minesweeper扫雷](./assets/cover.svg)

一款纯原生、零依赖的单文件扫雷游戏。

[**在线开始 →**](https://cizuwuxin.github.io/minesweeper/) · [源码](./index.html) · [反馈](https://github.com/cizuwuxin/minesweeper/issues)

</div>

---

## 特点

| | |
| :-- | :-- |
| **经典 / 无猜** | 经典保留风险；无猜尽量生成可逻辑推进的棋盘 |
| **下载即玩** | 全部封装在 `index.html`，无构建、无依赖 |
| **触控友好** | 点击、长按、缩放、拖动、键盘都能完局 |

## 能力

- 棋盘：简单 / 中等 / 困难 / 自定义 / 随机
- 辅助：提示、撤销、问号标记、进度条、键盘焦点
- 设置：深色模式、音效、左右键互换、长按延迟
- 数据：设置保存在本地浏览器，不上传

## 操作

| 目标 | 操作 |
| :-- | :-- |
| 打开格子 | 点击 / 左键 / `Enter` / `Space` |
| 标记格子 | 长按 / 右键 / `F` |
| 提示 | `H` |
| 撤销 | `Ctrl + Z` |
| 重开 | `R` |

<details>
<summary><strong>本地打开</strong></summary>

下载 `index.html` 用现代浏览器直接打开。需要本地服务时：

```bash
git clone https://github.com/cizuwuxin/minesweeper.git
cd minesweeper
python3 -m http.server 8000
```

访问 `http://localhost:8000`。
</details>

<details>
<summary><strong>实现</strong></summary>

原生 HTML / CSS / JS；无猜求解在 Web Worker 中执行；设置用 `localStorage`；通过 GitHub Pages 部署。
</details>

## 更新日志

- **2026-07-17** · 优化卡顿问题，改善操作与页面流畅度
- **2026-07-17** · README 结构整理，增加动态标题文字

---

<div align="center">

[在线游玩](https://cizuwuxin.github.io/minesweeper/) · [反馈问题](https://github.com/cizuwuxin/minesweeper/issues)

</div>
