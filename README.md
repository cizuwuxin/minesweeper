<div align="center">

# 扫雷

**一个纯原生、零依赖的单文件扫雷游戏**

经典规则与无猜模式 · Material 3 界面 · 桌面端与移动端适配

[在线游玩](https://cizuwuxin.github.io/minesweeper/) · [查看源码](./index.html) · [反馈问题](https://github.com/cizuwuxin/minesweeper/issues)

![HTML5](https://img.shields.io/badge/HTML5-single--file-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
![Dependencies](https://img.shields.io/badge/dependencies-0-2E7D32?style=flat-square)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-online-6750A4?style=flat-square&logo=github)

</div>

![游戏预览](./screenshot.png)

## 特性

- **两种规则**：传统随机布局与可逻辑推导的无猜模式
- **多种难度**：简单、中等、困难、自定义及随机棋盘
- **完整操作**：插旗、问号、提示、撤销、快捷键、缩放与拖拽
- **移动端友好**：支持触控、长按时间调节和左右键行为切换
- **舒适体验**：深色模式、声音反馈、进度显示与本地设置保存
- **开箱即用**：HTML、CSS、JavaScript 全部封装在 `index.html`，无外部运行依赖

## 快速开始

直接打开 [在线版本](https://cizuwuxin.github.io/minesweeper/)，或下载 `index.html` 后使用现代浏览器打开。

```bash
git clone https://github.com/cizuwuxin/minesweeper.git
cd minesweeper
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 操作

| 操作 | 鼠标 / 触控 | 键盘 |
|---|---|---|
| 打开格子 | 左键 / 点击 | `Enter` / `Space` |
| 标记格子 | 右键 / 长按 | `F` |
| 提示 | 顶栏提示按钮 | `H` |
| 撤销 | 顶栏撤销按钮 | `Ctrl + Z` |
| 重新开始 | 顶栏重新开始 | `R` |
| 移动焦点 | — | 方向键 |

## 项目结构

```text
.
├── index.html      # 游戏全部源码
├── screenshot.png  # 界面预览
└── README.md       # 项目说明
```

> 游戏进度与偏好保存在浏览器本地存储中。不同浏览器、无痕模式或清理站点数据后不会共享。
