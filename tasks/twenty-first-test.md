# 第二十一次 Codex 测试记录

## 测试目的

验证 Codex 是否可以在 SKU 单品项目总控交付 SOP 合并后，更新 README 和 `docs/index.md`，将 `docs/sku-launch-master-sop.md` 正式纳入仓库文档导航体系。

## 已确认事项

- 已确认 PR #20 合并成功。
- `main` 分支已经存在 `docs/sku-launch-master-sop.md`。
- `main` 分支已经存在 `tasks/twentieth-test.md`。
- 当前 README 和 `docs/index.md` 尚未同步 SKU 单品项目总控交付 SOP。

## 本次计划

本次计划修改和新增 3 个文件：

- 更新 `README.md`
- 更新 `docs/index.md`
- 新增 `tasks/twenty-first-test.md`

## README 更新目标

本次计划在 README 中补齐以下内容：

- 当前文档目录加入 `docs/sku-launch-master-sop.md`
- tasks 目录加入 `tasks/twentieth-test.md` 和 `tasks/twenty-first-test.md`
- docs 文档说明加入 SKU 单品项目总控交付 SOP 说明
- tasks 测试记录说明加入第二十次和第二十一次测试记录
- 推荐阅读顺序中将 SKU 总控 SOP 放在具体业务 SOP 之前

## docs/index.md 更新目标

本次计划将 `docs/index.md` 更新为包含 SKU 总控入口的业务导航：

1. 当前文档覆盖范围加入 SKU 单品项目总控。
2. 新增“SKU 项目总控入口”分类。
3. 将 `sku-launch-master-sop.md` 放在选品、竞品调研、供应链核价、商品上架、图片、视频、达人、运营、订单、复盘等流程之前。
4. 推荐使用顺序中将 SKU 总控 SOP 放在业务 SOP 前面。
5. 业务流程关系中加入“SKU 项目总控 → 竞品与市场调研”。
6. 不修改任何业务 SOP 内容。

## 分支策略

本次使用新分支进行修改：

```text
codex/update-sku-launch-navigation
```

不直接修改 `main` 分支。

## 后续合并方式

完成导航更新后，建议通过 Pull Request 合并到 `main`。

合并前应检查：

- README 是否已经包含 SKU 总控 SOP 和第二十、二十一次任务记录。
- `docs/index.md` 是否已经将 SKU 总控 SOP 放在业务流程最前面。
- 推荐使用顺序是否符合“总控入口 → 调研 → 选品 → 核价 → 上架 → 复盘”的业务逻辑。
- 本轮是否只做导航同步，没有修改业务 SOP 内容。
