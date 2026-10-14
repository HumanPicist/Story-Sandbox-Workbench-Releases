# Story Sandbox Workbench 下载

这里是 Story Sandbox Workbench 的公开下载仓库，只提供安装包、校验文件和版本说明，不公开应用源码。

## 最新版本

### v0.72.1 · 存储与创作体验完整整合

- macOS 通用安装包，同时支持 Apple Silicon 与 Intel Mac
- 文件大小：14,852,196 bytes
- SHA-256：`afcac7f76d2d69c8e922f6ff4ccd276712f38902cb335661dcbf5f78a1be4092`
- 签名状态：ad-hoc 签名，未经 Apple Developer ID 签名与公证
- 发布状态：公开预发布版，供实际体验与反馈

[前往 v0.72.1 下载页面](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.72.1) · [版本说明](release-notes/v0.72.1.md)

本版累积包含 **0.71.0 的存储升级与 0.72.0 的全部界面优化**：旧任务记录恢复与历史复用、手记保存并加入工作集、安全维护，以及更轻巧的园丁引用、关键词搜索和双侧栏布局。

## 校验安装包

下载 DMG 和对应的 `.sha256` 文件后，可在 macOS 终端运行：

```bash
shasum -a 256 Story-Sandbox-Workbench_0.72.1_macOS_universal.dmg
```

输出应与本页列出的 SHA-256 完全一致。

安装包尚未经过 Apple Developer ID 签名与公证，macOS 可能显示安全提醒。更新前请备份自己的沙盒文件夹；本次发布不会自动替换本机安装或迁移沙盒。

## 历史版本

- [v0.72.0 · 更轻盈的园丁与协作布局](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.72.0)（界面优化，未含 0.71 存储升级）
- [v0.70.0 · 创作工作区与园丁引用](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.70.0)
- [v0.59.0 · Mature Experience](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.59.0)
- [v0.53.0 · Creative Space](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.53.0)

## 关于“Source code”下载项

GitHub 会为每个 Release 自动生成 `Source code (zip)` 和 `Source code (tar.gz)`。这些压缩包只包含本下载仓库的说明和校验信息，不包含 Story Sandbox Workbench 的应用源码。
