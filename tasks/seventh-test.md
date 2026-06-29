# 第七次 Codex 测试记录

## 测试目的

验证 Codex 是否可以基于已经升级的 TikTok Shop 日常运营 SOP，继续升级商品上架文档，使其更适合美国 TikTok Shop 商品发布和审核前检查。

## 已确认事项

- 已确认 PR #6 合并成功。
- `main` 分支已经包含升级后的 `docs/tiktok-shop-sop.md`。
- 当前 `docs/product-listing-guide.md` 为基础版，需要升级为适合执行的商品上架 SOP。

## 本次计划

本次计划修改和新增 2 个文件：

- 升级 `docs/product-listing-guide.md`
- 新增 `tasks/seventh-test.md`

## 商品上架 SOP 升级目标

本次计划将 `docs/product-listing-guide.md` 升级为美国 TikTok Shop 商品上架执行 SOP，包含：

- 文档用途
- 商品上架前资料清单
- 标题结构模板
- 图片与视频素材检查清单
- 禁词与合规风险检查
- 上架后复查清单
- 与其他专项文档的引用关系

## 分支策略

本次使用新分支进行修改：

```text
codex/upgrade-product-listing-sop
```

不直接修改 `main` 分支。

## 后续合并方式

完成商品上架 SOP 升级后，建议通过 Pull Request 合并到 `main`。

合并前应检查：

- `docs/product-listing-guide.md` 是否覆盖上架前资料准备。
- 标题结构模板是否清晰可复用。
- 图片与视频素材检查清单是否完整。
- 禁词与合规风险检查是否适合美国 TikTok Shop 场景。
- 上架后复查清单是否能帮助发现异常问题。
- 引用关系是否覆盖日常运营 SOP、图片 brief 和短视频脚本 SOP。
