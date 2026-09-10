# 咫间 · Nearvia

文件与消息，直接到你。  
Files & messages. Straight to you.

[官网 / Website](https://skstu.com) · [预览版 / Previews](https://github.com/memade/nearvia/releases)

本仓库用于客户端安装包、发行说明和许可文件，不包含完整客户端或 SovKit SDK 源码。
独立 STUN 组件在 [sovkit-stun](https://github.com/memade/sovkit-stun) 开源，范围和许可与客户端分开。
GitHub 自动生成的 Source code 压缩包只包含本发行仓库文档，不是客户端源码或安装包。

## 预览范围

- Android arm64 APK：长期发布密钥签名。旧 Debug 签名研发包可能存在签名冲突；不要直接清除旧数据。
- macOS Apple Silicon：ad-hoc 签名、未公证，非 Intel 包，首次启动可能被系统拦截。
- 暂无 iOS、Windows、Linux 客户端安装包。本仓库不把 STUN 或节点组件当作客户端交付。

仅下载 GitHub Release 中明确标出的安装包，并核对 SHA-256；预览版不是稳定版。
具体版本、最低系统、已测范围和已知限制，以对应发行说明为准。
首次使用须设置独立数据密码。数据库加密不包含已接收文件，不要仅用预览软件保存重要资料。

## English

This repository hosts client installers, release notes and notices, not the full client or SovKit SDK source.
The separate [STUN component](https://github.com/memade/sovkit-stun) has its own source and license.
GitHub's automatic source archives contain this distribution repository's documentation, not client sources.

Preview targets are Android arm64 (persistent release-key APK) and Apple Silicon macOS
(ad-hoc signed, **not notarized**, not Intel). There are no iOS, Windows or Linux client installers here.
Use the exact release notes for requirements and tested scope. Verify checksums before installing.
Previews are not stable releases; keep independent copies of important files.

The application ID remains `com.skstu.sovkit`. Original SovKit code is Apache-2.0; third-party
components retain their own licenses. Keep the notices and covered-source overlays included in each package.
