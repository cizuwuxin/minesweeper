# 贡献指南

感谢你对这个扫雷项目感兴趣。

## 提交问题

- **Bug 报告**：请在 Issue 中描述复现步骤、预期结果、实际结果、浏览器及版本。
- **功能建议**：先搜索是否已有类似 Issue，再描述使用场景和期望行为。
- **安全问题**：请勿公开提 Issue，通过 [SECURITY.md](./SECURITY.md) 中的方式私下联系。

## 提交代码

1. Fork 仓库，创建分支：`git checkout -b feature/your-feature`
2. 保持单文件结构，所有改动集中在 `saolei.html`
3. 如有 UI 变更，请在 PR 中附上截图
4. 在 Chrome / Firefox / Safari 最新版验证可玩
5. 提交信息使用语义化：`feat: ...` / `fix: ...` / `docs: ...` / `chore: ...`
6. 发起 PR，描述改动动机和影响范围

## 代码规范

- 保持零依赖原则（无 npm / CDN）
- 使用 ES6+ 语法
- CSS 优先用 Material 3 token 变量
- 保持 360px ~ 4K 响应式可玩

## 许可

贡献的代码将以 MIT 协议发布。
