# Story Sandbox Workbench 下载

这里是 Story Sandbox Workbench 的公开下载仓库，只提供安装包、校验文件和版本说明，不公开应用源码。

## 最新版本

### v0.72.0 · 更轻盈的园丁与协作布局

- macOS 通用安装包，同时支持 Apple Silicon 与 Intel Mac
- 文件大小：13,811,051 bytes
- SHA-256：`ce5292b800ed7aec1b6fa6b6a1e1e3d30594619e2601064e774e32347b4f33c9`
- 签名状态：ad-hoc 签名，未经 Apple Developer ID 签名与公证
- 发布状态：公开预发布版，供实际体验与反馈

[前往 v0.72.0 下载页面](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.72.0) · [版本说明](release-notes/v0.72.0.md)

本版精简园丁的附属信息与菜单，支持输入 `@` 搜索引用材料，修复画布资源卡片的阅读入口。工作集与园丁侧栏现在可以同时打开，方便一边整理材料一边对话。

## 校验安装包

下载 DMG 和对应的 `.sha256` 文件后，可在 macOS 终端运行：

```bash
shasum -a 256 Story-Sandbox-Workbench_0.72.0_macOS_universal.dmg
```

输出应与本页列出的 SHA-256 完全一致。

安装包尚未经过 Apple Developer ID 签名与公证，macOS 可能显示安全提醒。更新前请备份自己的沙盒文件夹；本次发布不会自动替换本机安装或迁移沙盒。

## 历史版本

- [v0.70.0 · 创作工作区与园丁引用](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.70.0)
- [v0.59.0 · Mature Experience](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.59.0)
- [v0.53.0 · Creative Space](https://github.com/HumanPicist/Story-Sandbox-Workbench-Releases/releases/tag/v0.53.0)

## 关于“Source code”下载项

GitHub 会为每个 Release 自动生成 `Source code (zip)` 和 `Source code (tar.gz)`。这些压缩包只包含本下载仓库的说明和校验信息，不包含 Story Sandbox Workbench 的应用源码。
