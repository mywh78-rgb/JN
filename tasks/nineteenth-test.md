# 第十九次 Codex 测试记录

## 测试目的

验证 Codex 是否可以在竞品与市场调研 SOP 合并后，更新 README 和 `docs/index.md`，将 `docs/market-competitor-research-sop.md` 正式纳入仓库文档导航体系。

## 已确认事项

- 已确认 PR #18 合并成功。
- `main` 分支已经存在 `docs/market-competitor-research-sop.md`。
- `main` 分支已经存在 `tasks/eighteenth-test.md`。
- 当前 README 和 `docs/index.md` 尚未同步竞品与市场调研 SOP。

## 本次计划

本次计划修改和新增 3 个文件：

- 更新 `README.md`
- 更新 `docs/index.md`
- 新增 `tasks/nineteenth-test.md`

## README 更新目标

本次计划在 README 中补齐以下内容：

- 当前文档目录加入 `docs/market-competitor-research-sop.md`
- tasks 目录加入 `tasks/eighteenth-test.md` 和 `tasks/nineteenth-test.md`
- docs 文档说明加入竞品与市场调研 SOP 说明
- tasks 测试记录说明加入第十八次和第十九次测试记录
- 推荐阅读顺序中将竞品与市场调研 SOP 放在选品 SOP 之前

## docs/index.md 更新目标

本次计划将 `docs/index.md` 更新为包含前置调研入口的业务导航：

1. 当前文档覆盖范围加入竞品与市场调研。
2. 将 `market-competitor-research-sop.md` 放入“选品、供应链与调研决策”分类。
3. 推荐使用顺序中将调研 SOP 放在选品 SOP 之前。
4. 业务流程关系中加入“竞品与市场调研 → 选品决策”。
5. 保持店铺周报、商品测试复盘和其他已完成文档导航不变。

## 分支策略

本次使用新分支进行修改：

```text
codex/update-market-research-navigation
```

不直接修改 `main` 分支。

## 后续合并方式

完成导航更新后，建议通过 Pull Request 合并到 `main`。

合并前应检查：

- README 是否已经包含竞品与市场调研 SOP 和第十八、十九次任务记录。
- `docs/index.md` 是否已经将调研 SOP 放在业务流程最前面。
- 推荐使用顺序是否符合“调研 → 选品 → 核价 → 上架”的业务逻辑。
- 业务流程关系是否加入“竞品与市场调研 → 选品决策”。
