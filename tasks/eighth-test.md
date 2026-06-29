# 第八次 Codex 测试记录

## 测试目的

验证 Codex 是否可以基于已经升级的商品上架 SOP，继续升级商品图片 brief，使其成为适合 TikTok Shop、Amazon、Temu 和 Shopify 商品图片制作的视觉执行 SOP。

## 已确认事项

- 已确认 PR #7 合并成功。
- `main` 分支已经包含升级后的 `docs/product-listing-guide.md`。
- 当前 `docs/product-image-brief.md` 为基础版，需要升级为视觉执行 SOP。

## 本次计划

本次计划修改和新增 2 个文件：

- 升级 `docs/product-image-brief.md`
- 新增 `tasks/eighth-test.md`

## 图片 brief 升级目标

本次计划将 `docs/product-image-brief.md` 升级为适合 TikTok Shop、Amazon、Temu 和 Shopify 的商品视觉执行 SOP，包含：

- 文档用途
- 固定交付标准
- 禁止输出形式
- 清晰度与尺寸规范
- 标准执行流程
- 参考图识别要求
- 竞品调研要求
- 卖点与痛点提炼
- 宠物类目图片要求
- 泳装类目图片要求
- 图片交付检查清单
- 与其他专项文档的引用关系

## 分支策略

本次使用新分支进行修改：

```text
codex/upgrade-product-image-brief
```

不直接修改 `main` 分支。

## 后续合并方式

完成商品图片 brief 升级后，建议通过 Pull Request 合并到 `main`。

合并前应检查：

- `docs/product-image-brief.md` 是否明确 9 张主图和 6 张 A+详情图交付标准。
- 是否明确禁止九宫格、拼图、合集图、长图合集等输出形式。
- 是否说明 4K 高清质感和 800x800 导出关系。
- 是否包含参考图识别、竞品调研、卖点痛点提炼、合规检查和图片规划流程。
- 是否覆盖宠物类目和泳装类目的差异化要求。
- 引用关系是否覆盖商品上架 SOP、日常运营 SOP 和短视频脚本 SOP。
