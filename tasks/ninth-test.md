# 第九次 Codex 测试记录

## 测试目的

验证 Codex 是否可以基于已经升级的商品图片视觉 SOP，继续升级 TikTok 短视频脚本 SOP，使其适合美国 TikTok Shop 带货短视频、Seedance / Dreamina AI 视频生成、英文字幕和 3 秒 Hook 规划。

## 已确认事项

- 已确认 PR #8 合并成功。
- `main` 分支已经包含升级后的 `docs/product-image-brief.md`。
- 当前 `docs/tiktok-video-script-sop.md` 为基础版，需要升级为更完整的短视频脚本执行 SOP。

## 本次计划

本次计划修改和新增 2 个文件：

- 升级 `docs/tiktok-video-script-sop.md`
- 新增 `tasks/ninth-test.md`

## 短视频脚本 SOP 升级目标

本次计划将 `docs/tiktok-video-script-sop.md` 升级为适合美国 TikTok Shop 带货短视频和 AI 视频生成的执行 SOP，包含：

- 文档用途
- 15 秒、20 秒、30 秒短视频结构
- 前 3 秒 Hook 写法
- 英文字幕与口播规范
- TikTok 自然流视频节奏
- Seedance / Dreamina 提示词结构
- 宠物类目视频要求
- 泳装类目视频要求
- 发布前合规检查清单
- 与其他专项文档的引用关系

## 分支策略

本次使用新分支进行修改：

```text
codex/upgrade-video-script-sop
```

不直接修改 `main` 分支。

## 后续合并方式

完成短视频脚本 SOP 升级后，建议通过 Pull Request 合并到 `main`。

合并前应检查：

- `docs/tiktok-video-script-sop.md` 是否包含 15 秒、20 秒、30 秒脚本结构。
- 是否明确前 3 秒 Hook 写法和禁用开头。
- 是否包含英文字幕与口播规范。
- 是否覆盖 TikTok 自然流视频节奏。
- 是否包含 Seedance / Dreamina 提示词结构。
- 是否覆盖宠物类目和泳装类目视频差异化要求。
- 发布前合规检查清单是否完整。
- 引用关系是否覆盖日常运营 SOP、商品图片 SOP、商品上架 SOP 和文档导航。
