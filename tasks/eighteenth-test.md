# 第十八次 Codex 测试记录

## 测试目的

验证 Codex 是否可以在当前跨境电商 SOP 文档体系基础上，新增竞品与市场调研 SOP，用于规范选品、供应链核价、商品上架、图片素材、短视频脚本、达人 BD 和运营复盘之前的调研流程。

## 已确认事项

- 已确认 PR #17 合并成功。
- `README.md` 已经包含 `docs/store-weekly-report-template.md`。
- `docs/index.md` 已经包含 `docs/store-weekly-report-template.md`。
- 当前文档体系已经形成“选品 → 核价 → 上架 → 图片/视频 → 达人/内容 → 订单 → 日常运营 → 商品测试复盘 → 店铺周报复盘”的流程。

## 本次计划

本次计划新增 2 个文件：

- `docs/market-competitor-research-sop.md`
- `tasks/eighteenth-test.md`

本轮不更新以下文件：

- `README.md`
- `docs/index.md`

## 文档目标

`docs/market-competitor-research-sop.md` 用于作为当前业务流程之前的调研入口，覆盖：

- 参考图/产品图识别
- TikTok Shop 竞品调研
- Amazon 竞品调研
- Temu / Walmart / Etsy / Shopify 竞品调研
- Google Trends / Reddit / Pinterest / YouTube Shorts 趋势观察
- 竞品标题与关键词拆解
- 主图/A+详情图视觉拆解
- 短视频内容结构拆解
- 用户评论痛点提炼
- 核心卖点提炼
- 价格带与利润空间判断
- 合规风险与禁词风险检查
- 输出给选品、上架、图片、视频、达人和供应链模块的资料格式
- 调研结论输出模板
- 与现有 docs 文档的引用关系

## 分支策略

本次使用新分支进行修改：

```text
codex/add-market-competitor-research-sop
```

不直接修改 `main` 分支。

## 后续合并方式

完成竞品与市场调研 SOP 新增后，建议通过 Pull Request 合并到 `main`。

合并前应检查：

- 调研 SOP 是否能作为选品、核价、上架、图片、视频、达人和供应链判断前的入口。
- 调研字段是否方便复制填写。
- 是否包含合规、禁词、侵权、虚假宣传和平台审核风险检查。
- `tasks/eighteenth-test.md` 是否完整记录本轮测试。

## 后续建议

本轮合并后，可单独规划下一轮任务，用于更新 README 和 `docs/index.md`，将竞品与市场调研 SOP 正式纳入仓库导航。
