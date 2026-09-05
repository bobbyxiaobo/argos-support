# 阿戈斯——本地 HTML 收纳盒

如果你已经开始熟练使用 Codex、Claude Code、WorkBuddy 等 Agent 进行工作，你一定会发现：HTML 在很多时候是一种更好的产出形式——格式丰富、支持交互、可读性强。

但零散任务产出的 HTML 往往非常难找。

所以，没有任何代码基础的我，花了一周的碎片时间写了这样一个小工具。它的功能很简单：帮你收纳本地 HTML，方便日常查看和找回。也许未来它还可以结合 AI 和插件做更多事情，但当下，我希望它只是一个轻量的收纳盒。

你也可以直接调用 CLI 写入和管理数据。因为我没有足够的 token 给大家使用“AI + Argos”，你可以把它和自己的 Agent 结合起来，例如让 Agent 根据 HTML 内容重新设置分类。

至于它为什么叫阿戈斯，哈宝在伊萨卡的故事会告诉你答案。

## 下载

[下载阿戈斯普通版 1.0.0（构建 19）](https://github.com/bobbyye19890223-bit/argos-support/releases/tag/standard-v1.0.0-build19)

适用于 macOS 13 或更新版本，支持 Intel 与 Apple Silicon。安装包已使用 Developer ID 签名并通过 Apple 公证。

独立版不启用 macOS App Sandbox，以减少本地资料库的沙盒授权步骤；macOS 自身的隐私权限仍然有效。独立版默认发送匿名使用统计，不显示首次同意流程，也不提供关闭开关；App Store 版不包含该统计 SDK。请在下载前阅读[隐私政策](https://bobbyye19890223-bit.github.io/argos-support/privacy.html)。

## 界面预览

<img width="2560" height="1600" alt="自动收纳散落的 HTML 文件" src="https://github.com/user-attachments/assets/acf72ef0-9175-46dc-90b4-46611c19bd17" />

<img width="2560" height="1600" alt="分类展示更加清晰" src="https://github.com/user-attachments/assets/a80bcef7-dd61-4f4a-8283-a37ad710203e" />

<img width="2560" height="1600" alt="支持 CLI 新增和管理" src="https://github.com/user-attachments/assets/a56350fa-0472-4a6c-89b4-643a160fa581" />

## 支持与隐私

- [产品与支持主页](https://bobbyye19890223-bit.github.io/argos-support/)
- [使用支持](https://bobbyye19890223-bit.github.io/argos-support/support.html)
- [隐私政策](https://bobbyye19890223-bit.github.io/argos-support/privacy.html)
- 联系邮箱：bobbyye2026@qq.com

## 本仓库范围

本仓库只托管公开支持网页、品牌图片、独立版更新清单及 GitHub Release，不包含应用源代码、用户文档、私钥或其他凭据。安装包只放在 GitHub Releases，不写入 Git 文件历史。

应用的统计、联网、权限、账户或文件处理行为发生变化时，应同步更新中英文政策、支持说明及应用内声明。网站内容不替代对实际上架版本行为和商店隐私申报的核对。
