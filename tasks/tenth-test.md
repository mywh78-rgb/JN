# 第十次 Codex 测试记录

## 测试目的

验证 Codex 是否可以基于已经升级的短视频脚本 SOP，继续升级达人联盟 BD 文档，使其适合美国 TikTok Shop 达人建联、联盟营销、样品寄送、佣金设置、直播专属价和合作复盘。

## 已确认事项

- 已确认 PR #9 合并成功。
- `main` 分支已经包含升级后的 `docs/tiktok-video-script-sop.md`。
- 当前 `docs/creator-affiliate-bd.md` 为基础版，需要升级为更完整的达人联盟执行 SOP。

## 本次计划

本次计划修改和新增 2 个文件：

- 升级 `docs/creator-affiliate-bd.md`
- 新增 `tasks/tenth-test.md`

## 达人联盟 SOP 升级目标

本次计划将 `docs/creator-affiliate-bd.md` 升级为适合美国 TikTok Shop 达人合作和联盟营销的执行 SOP，包含：

- 文档用途
- 达人筛选标准
- 达人邀约话术
- 样品寄送流程
- 佣金与专属价设置
- 短视频达人 / 直播达人差异化合作方式
- 达人内容审核与合规检查
- 达人效果复盘表
- 与其他专项文档的引用关系

## 分支策略

本次使用新分支进行修改：

```text
codex/upgrade-creator-affiliate-sop
```

不直接修改 `main` 分支。

## 后续合并方式

完成达人联盟 SOP 升级后，建议通过 Pull Request 合并到 `main`。

合并前应检查：

- `docs/creator-affiliate-bd.md` 是否覆盖达人筛选和分层。
- 是否包含英文邀约话术。
- 样品寄送流程是否可执行。
- 佣金、专属价和直播专属价设置是否清晰。
- 是否区分短视频达人和直播达人合作方式。
- 内容审核与合规检查是否完整。
- 达人效果复盘表是否便于后续追踪。
