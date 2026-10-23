# AllinOne for macOS

本仓库提供 AllinOne 成品下载、版本说明、问题反馈与功能建议，不包含应用源码，使用独立 Git 历史。

## 下载与升级

当前内测版本为 **[v0.4.4](https://github.com/LazyBoom/AllinOne-Releases/releases/tag/v0.4.4)**，支持 Apple Silicon 和 macOS 14 及以上。

- [下载 v0.4.4 安装包](https://github.com/LazyBoom/AllinOne-Releases/releases/download/v0.4.4/AllinOne-0.4.4-macOS-arm64.zip)
- [下载 SHA-256 校验文件](https://github.com/LazyBoom/AllinOne-Releases/releases/download/v0.4.4/AllinOne-0.4.4-macOS-arm64.zip.sha256)
- [查看所有版本](https://github.com/LazyBoom/AllinOne-Releases/releases)

v0.4.4 已提供以下能力：

- 直接从此公开仓库检查、下载并安装更新，无需配置更新 Token；安装前验证更新包和签名，并正常保存退出。
- 在应用内为现有模块、新模块或整体体验提交问题与建议，预览并确认后创建公开 Issue，返回提交链接。
- 在本机保存崩溃摘要与异常退出记录，区分已确认崩溃、异常退出和升级退出；本地记录不会自动上传。

当前为内测阶段，使用固定本地证书签名，尚未完成 Developer ID 签名与 Apple 公证。macOS 14 及以上；首批成品为 Apple Silicon。

## 问题与建议

在 [Issues](https://github.com/LazyBoom/AllinOne-Releases/issues/new/choose) 选择问题反馈、功能建议或新模块建议。请说明应用版本、macOS 版本、相关模块、复现步骤与预期结果。

Issue 正文与附件对公众可见，请不要上传 Token、密码、私人截图、剪贴板、便签、文件原文或未脱敏的完整崩溃报告。应用内反馈会明确展示将要提交的内容。

本内测安装包包含一个**仅授权本公开仓库 Issues 的共享反馈凭据**，用于在应用内提交反馈。该凭据可以从安装包中提取，也可以由维护者撤销或轮换；它不应被视为客户端能够保密的秘密。更新下载不使用该凭据。

反馈与主动提交的崩溃摘要均须在应用内预览、确认后发送。本地崩溃记录不会自动上传；用户未选择提交的记录保留在本机。

## 仓库范围

本仓库的 Git 内容仅维护公开分发说明与反馈模板，不包含应用源码、开发机数据或源码 Git 历史。成品通过 Releases 分发；公开提供二进制不等于应用源码采用开源许可证。
