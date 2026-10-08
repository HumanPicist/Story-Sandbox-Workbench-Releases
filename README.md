# Story Sandbox Workbench 下载

这里是 Story Sandbox Workbench 的公开下载仓库，只提供安装包、校验文件和版本说明，不公开应用源码。

## 最新版本

### v0.70.0 · 创作工作区与园丁引用

- macOS 通用安装包，同时支持 Apple Silicon 与 Intel Mac
- 文件大小：13,805,734 bytes
- SHA-256：`fd760aad1313c696b543dc6cf615bd9f48fdedf0b938ee9029a1d71f8f459bb0`
- 签名状态：ad-hoc 签名，未经 Apple Developer ID 签名与公证
- 发布状态：公开预发布快照；保留现有未完成的体验验收项

[前往 v0.70.0 下载页面](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.70.0) · [版本说明](release-notes/v0.70.0.md)

本版更新统一创作工作区、内容保护和手记多窗口，改进中文选词回车、工作集材料卡、园丁讨论保存与未读提示，并支持在阅读中选段引用到园丁。

## 校验安装包

下载 DMG 和对应的 `.sha256` 文件后，可在 macOS 终端运行：

```bash
shasum -a 256 Story-Sandbox-Workbench_0.70.0_macOS_universal.dmg
```

输出应与本页列出的 SHA-256 完全一致。

安装包尚未经过 Apple Developer ID 签名与公证，macOS 可能显示安全提醒。更新前请备份自己的沙盒文件夹；本次发布不会自动替换本机安装或迁移沙盒。

## 历史版本

- [v0.59.0 · Mature Experience](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.59.0)
- [v0.53.0 · Creative Space](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.53.0)

## 关于“Source code”下载项

GitHub 会为每个 Release 自动生成 `Source code (zip)` 和 `Source code (tar.gz)`。这些压缩包只包含本下载仓库的说明和校验信息，不包含 Story Sandbox Workbench 的应用源码。
