# Nearvia 0.1.0-rc.1 · Installation / 安装 / 安裝

Release candidate, version 0.1.0, build 10. Supported public packages: Android arm64 (API 24+) and macOS Apple Silicon (macOS 13+). iOS 15+ uses private, registered-device Ad Hoc distribution.

## 简体中文

1. 从 [RC1 Release](https://github.com/memade/nearvia/releases/tag/v0.1.0-rc.1) 下载对应安装包与 `SHA256SUMS`。GitHub 自动生成的 Source code ZIP/TAR 不是安装包。
2. 按下方命令核对 SHA-256。升级时先退出旧版，保留应用与数据；不要先卸载。Android 若报签名冲突，先停止并反馈。
3. Android：打开 APK，只为实际使用的下载器或文件管理器允许“安装未知应用”。macOS：解压 ZIP，将 Nearvia.app 拖入“应用程序”，使用 Finder 打开。正常安装不需要关闭 Gatekeeper 或系统安全保护；若系统报告包损坏/身份异常，停止并重新核对来源和摘要。
4. 两端连接同一 Wi-Fi，打开 Nearvia 并按需允许本地网络与蓝牙权限；在“附近”找到对方，双方核对安全码后分别确认，再发送消息或文件。访客网络隔离可能阻止发现。蓝牙仅支持附近短文字与回执，不传文件。
5. 进入设置可启用个人启动密码。请自行保管密码；已接收文件不属于数据库加密范围。保留重要文件原件。

iOS：先通过 [邮件](mailto:k34ubll5@gmail.com?subject=Nearvia%20iOS%20Ad%20Hoc) 申请体验，再通过私下约定的方式登记设备。收到匹配的 Ad Hoc 包后，使用 Mac 上的 Xcode「Window → Devices and Simulators」连接已解锁、已信任的 iPhone，在 Installed Apps 中添加 IPA。未登记设备无法安装；注册范围或证书变化后需要新包。不要在公开 Issue 提交设备标识。

## 繁體中文

1. 在 [RC1 Release](https://github.com/memade/nearvia/releases/tag/v0.1.0-rc.1) 下載相符的安裝包與 `SHA256SUMS`。Source code ZIP/TAR 不是安裝包。
2. 使用下方命令核驗 SHA-256。升級前結束舊版，保留應用程式與資料；請勿先解除安裝。Android 若出現簽章衝突，請停止並回報。
3. Android：開啟 APK，僅對實際使用的下載器或檔案管理器允許安裝未知應用程式。macOS：解壓縮後將 Nearvia.app 拖入「應用程式」，透過 Finder 開啟。正常安裝不需關閉 Gatekeeper 或系統安全保護；若系統回報損壞或身分異常，請停止並重新核驗來源與摘要。
4. 兩端連上同一 Wi-Fi，開啟 Nearvia 並依需要允許區域網路與藍牙權限。在「附近」找到對方，雙方核對安全碼並確認後，即可傳送訊息或檔案。訪客網路隔離可能阻擋探索；藍牙僅支援附近短文字與送達回覆，不傳檔案。
5. 可在設定啟用個人啟動密碼，請自行妥善保管。已接收檔案不在資料庫加密範圍內，重要檔案請保留原件。

iOS：先以 [電子郵件](mailto:k34ubll5@gmail.com?subject=Nearvia%20iOS%20Ad%20Hoc) 申請體驗，再透過私下約定的方式登記裝置。取得相符的 Ad Hoc 安裝包後，於 Mac 的 Xcode「Window → Devices and Simulators」連接已解鎖並信任電腦的 iPhone，在 Installed Apps 加入 IPA。未登記裝置無法安裝；登記範圍或憑證變更後需要新包。請勿在公開 Issue 提交裝置識別碼。

## English

1. Download the matching package and `SHA256SUMS` from [RC1 Release](https://github.com/memade/nearvia/releases/tag/v0.1.0-rc.1). GitHub's Source code ZIP/TAR files are not installers.
2. Verify SHA-256 using the commands below. Quit the old application before upgrading. Do not uninstall or clear data. Stop and report an Android signing conflict.
3. Android: open the APK and allow installation only for the downloader/file manager you actually use. macOS: unzip, move Nearvia.app into Applications, then open it in Finder. Installation does not require disabling Gatekeeper or system protections. If the system reports damage or an unexpected identity, stop and verify the source and checksum.
4. Connect both devices to the same Wi-Fi, open Nearvia and allow local-network/Bluetooth permissions as needed. Find the other device under Nearby, compare the security code, and confirm on both ends. Guest-network isolation can prevent discovery. Bluetooth supports short text and receipts, not files.
5. An optional personal startup password is available in Settings. Keep it safe. Received files are outside database encryption; retain important originals.

iOS: [email the developer](mailto:k34ubll5@gmail.com?subject=Nearvia%20iOS%20Ad%20Hoc) to request access and arrange private device registration. After receiving a matching Ad Hoc IPA, connect the unlocked, trusted iPhone to Xcode on a Mac, choose Window → Devices and Simulators, and add the IPA under Installed Apps. Unregistered devices cannot install it. Changed registration or certificates require a new package. Never post device identifiers publicly.

## SHA-256

macOS:

```sh
shasum -a 256 Nearvia-0.1.0-rc.1-macos-arm64.zip
shasum -a 256 Nearvia-0.1.0-rc.1-android-arm64.apk
```

Linux:

```sh
sha256sum Nearvia-0.1.0-rc.1-android-arm64.apk
```

Windows PowerShell:

```powershell
Get-FileHash .\Nearvia-0.1.0-rc.1-android-arm64.apk -Algorithm SHA256
```

Compare the complete digest with the matching line in `SHA256SUMS`. To verify all attachments together, download every listed file into one directory and run `shasum -a 256 -c SHA256SUMS` on macOS, or `sha256sum -c SHA256SUMS` on Linux.

## Feedback / 反馈 / 回饋

Use [Issues](https://github.com/memade/nearvia/issues). Include your platform, OS version, build number, connection type, and steps to reproduce. Keep passwords, keys, device identifiers, personal messages and unredacted logs private.
