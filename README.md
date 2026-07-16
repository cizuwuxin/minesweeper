# Minesweeper扫雷

![Minesweeper扫雷](./assets/cover.svg)

<div align="center">

### 读懂数字，再走下一步。

一款纯原生、零依赖的单文件扫雷游戏。

[**在线开始 →**](https://cizuwuxin.github.io/minesweeper/) · [查看源码](./index.html)

</div>

---

## 为什么是它

**经典与无猜**  
经典模式保留随机与风险；无猜模式会尝试生成能靠逻辑继续推进的棋盘。

**下载即玩**  
游戏完整封装在 `index.html`，没有框架、构建步骤或外部运行依赖。

**为触控而做**  
点击、长按、缩放、拖动与键盘操作都能完成一局游戏。

## 游戏能力

- 五种棋盘：简单、中等、困难、自定义、随机
- 辅助操作：提示、撤销、问号标记、进度显示、键盘焦点
- 个性设置：深色主题、声音、左右键互换、长按延迟
- 本地保存：设置保留在当前浏览器，不上传游戏数据

## 快捷操作

| 目标 | 操作 |
| :-- | :-- |
| 打开格子 | 点击 / 左键 / `Enter` / `Space` |
| 标记格子 | 长按 / 右键 / `F` |
| 提示 | `H` |
| 撤销 | `Ctrl + Z` |
| 重开 | `R` |

<details>
<summary><strong>本地打开</strong></summary>

<br>

下载 `index.html` 后直接用现代浏览器打开即可。若需要本地 HTTP 服务：

```bash
git clone https://github.com/cizuwuxin/minesweeper.git
cd minesweeper
python3 -m http.server 8000
```

访问 `http://localhost:8000`。

</details>

<details>
<summary><strong>实现</strong></summary>

<br>

原生 HTML、CSS、JavaScript；无猜模式的求解在 Web Worker 中执行；设置由 `localStorage` 保存；页面通过 GitHub Pages 部署。

</details>

---

<div align="center">

[在线游玩](https://cizuwuxin.github.io/minesweeper/) · [反馈问题](https://github.com/cizuwuxin/minesweeper/issues)

</div>
