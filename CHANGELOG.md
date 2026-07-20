# 更新日志

## 2026-07-20

### 优化
- 优化 `initGame` 中的布雷逻辑：增加重复检测与无猜验证的回退机制，减少无效重试开销
- 优化 `revealCell` 中连锁展开的 DFS 递归路径，避免深层盘面的调用栈溢出风险
- 优化 `handleCellClick` 中长按/短按判断的时序容差，提升移动端触控响应精准度
- 优化 `updateTimer` 定时器：增加页面不可见时自动暂停计时（`visibilitychange` 监听），减少后台空转
- 优化 `NOGUESS_TIMEOUT` 的计时粒度，支持 0.1s 步进配置
- 优化进度条（`updateProgress`）在问号标记/取消时的增量计算，避免越界
- 优化 toast 在软键盘弹起时的位置自适应（使用 `visualViewport`）
- 优化撤销栈（`actionHistory`）存储结构：合并连续标记操作以减少内存占用
- 优化键盘焦点模式下 `kbFocus` 的边界回绕逻辑
- 优化 `applyCustom` 输入验证：加入 max mines 公式与实时提示
