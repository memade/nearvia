# 咫间 · Nearvia

文件与消息，直接到你。 / 檔案與訊息，直接到你。  
Files & messages. Straight to you.

[官网 / 官網 / Website](https://skstu.com) · [RC1](https://github.com/memade/nearvia/releases/tag/v0.1.0-rc.1) · [安装 / 安裝 / Installation](INSTALL.md) · [桌面补充 / Desktop additions](INSTALL-DESKTOP.md) · [发行说明 / 發行說明 / Release notes](releases/v0.1.0-rc.1.md) · [Issues](https://github.com/memade/nearvia/issues)

## 简体中文

Nearvia 提供免费的近场通信：局域网消息与文件传输，蓝牙短文字和送达回执。双方核对安全码后建立信任。蓝牙不传文件；RC1 不包含跨网、中继、网络分享与发送文件夹。

当前候选版 **0.1.0-rc.1 / build 10**：

- Android arm64，Android 7.0（API 24）及以上：长期发行密钥签名 APK。
- macOS Apple Silicon，macOS 13 及以上：Developer ID 签名、Apple 公证并附加票据的 DMG。
- iOS 15 及以上：登记设备后通过 Ad Hoc 定向提供，公开 Release 不提供 IPA。请[联系开发者](mailto:k34ubll5@gmail.com?subject=Nearvia%20iOS%20Ad%20Hoc)，不要公开提交设备标识。
- Windows x64：ZIP，已在 Windows 11 验证构建、包完整性、DLL 加载与界面启动；跨设备互通和蓝牙硬件验收待补。
- Linux、Intel Mac 本轮没有安装包。

这是候选版。最终三端升级和消息/文件冒烟已通过，完整测试矩阵仍有待测项；详见发行说明。下载后核对 `SHA256SUMS`（Android）/ `SHA256SUMS-desktop-20260917.txt`（Windows / macOS DMG），升级前不要先卸载或清除数据。首次进入无需个人密码，可在设置中启用；接收文件本体不属于数据库加密范围，重要资料保留原件。

本仓库只分发客户端安装包、说明和许可文件，不包含完整客户端或 SovKit SDK 源码。GitHub 自动生成的 Source code ZIP/TAR 仅是本仓库文档，不能安装。开源 [sovkit-devtools](https://github.com/memade/sovkit-devtools) 工作台与 [sovkit-stun](https://github.com/memade/sovkit-stun) 组件各有独立许可与范围。

## 繁體中文

Nearvia 提供免費近場通訊：區域網路訊息與檔案傳輸，藍牙短文字與送達回覆。雙方核對安全碼後建立信任。藍牙不傳檔案；RC1 不包含跨網路、中繼、網路分享與傳送資料夾。

目前候選版 **0.1.0-rc.1 / build 10**：

- Android arm64，Android 7.0（API 24）以上：長期發行金鑰簽章 APK。
- macOS Apple Silicon，macOS 13 以上：Developer ID 簽章、Apple 公證並附加票據的 DMG。
- iOS 15 以上：登記裝置後透過 Ad Hoc 定向提供，公開 Release 不提供 IPA。請[聯絡開發者](mailto:k34ubll5@gmail.com?subject=Nearvia%20iOS%20Ad%20Hoc)，勿公開提交裝置識別碼。
- Windows x64：ZIP，已在 Windows 11 驗證建置、安裝包完整性、DLL 載入與介面啟動；跨裝置互通與藍牙硬體驗收待補。
- 本次沒有 Linux 或 Intel Mac 安裝包。

這是候選版。最終三端升級與訊息/檔案冒煙測試已通過，完整測試矩陣仍有待測項，詳見發行說明。下載後核驗 `SHA256SUMS`（Android）或 `SHA256SUMS-desktop-20260917.txt`（Windows / macOS DMG），升級前請勿先解除安裝或清除資料。首次進入不需個人密碼，可在設定啟用；接收檔案本體不在資料庫加密範圍內，重要資料請保留原件。

此儲存庫僅分發安裝包、文件及授權，不包含完整客戶端或 SovKit SDK 原始碼。GitHub 自動產生的 Source code ZIP/TAR 只含儲存庫文件，並非安裝包。[sovkit-devtools](https://github.com/memade/sovkit-devtools) 與 [sovkit-stun](https://github.com/memade/sovkit-stun) 各有獨立授權及範圍。

## English

Nearvia offers free nearby communication: local-network files and messages, plus Bluetooth short text and delivery receipts. Both devices check and confirm a security code. Bluetooth does not carry files. RC1 excludes internet-wide connectivity, relay, network sharing and folder sending.

Current candidate: **0.1.0-rc.1 / build 10**.

- Android arm64, Android 7.0 (API 24)+: APK signed with the persistent release key.
- Apple Silicon macOS, macOS 13+: Developer ID-signed, Apple-notarized and stapled DMG.
- iOS 15+: private Ad Hoc distribution after device registration. No public IPA attachment. [Contact the developer](mailto:k34ubll5@gmail.com?subject=Nearvia%20iOS%20Ad%20Hoc); never post device identifiers publicly.
- Windows x64: ZIP, with build, package integrity, DLL loading and UI startup checked on Windows 11. Cross-device and Bluetooth hardware acceptance remains pending.
- No Linux or Intel Mac installers in this release.

This is a release candidate. Final three-device upgrade and communication smoke checks passed; the full test matrix still has untested cases. Read the release notes and verify `SHA256SUMS` for Android or `SHA256SUMS-desktop-20260917.txt` for Windows / macOS DMG. Do not uninstall or clear data before upgrading. First launch needs no personal password; one can be enabled in Settings. Received files are outside database encryption; retain important originals.

This repository distributes installers, documentation and notices, not full client or SDK source. GitHub's automatic source archives contain repository documents, not installers. [sovkit-devtools](https://github.com/memade/sovkit-devtools) and [sovkit-stun](https://github.com/memade/sovkit-stun) have separate licenses and scopes.

## License / 许可 / 授權

Original SovKit code is Apache-2.0. Third-party components retain their own licenses. Preserve [LICENSE](LICENSE), [NOTICE.md](NOTICE.md) and the notices and covered-source overlays included in application bundles. Names and logos are not licensed as trademarks by the code license.

Apple application ID: `com.skstu.nearvia`. Android application ID: `com.skstu.sovkit`. Older releases retain their original scope and identifiers; current notes do not change historical packages.
