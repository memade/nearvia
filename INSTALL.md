# 直予 / Zhiyu RC2 安装

版本：0.1.0-rc.2（build 13）。下载 Release 附件并核对 `SHA256SUMS`。这是候选版。

- **Android arm64 / Android 7.0+**：安装 APK，允许当前下载器或文件管理器安装应用。已有版本直接覆盖；遇到签名冲突请停止并反馈，不要先卸载。
- **macOS Apple Silicon / macOS 13+**：退出旧版，打开 DMG，将 `Zhiyu.app` 拖入 Applications，弹出映像后启动。应用与 DMG 均已 Developer ID 签名、公证并附加票据。旧版名为 `Nearvia.app` 时，替换旧应用并保留应用数据，不要同时运行两份。
- **Windows x64 / Windows 11**：完整解压 ZIP 到可写目录，退出旧版后运行 `Zhiyu/sovkit.exe`。保留同目录 DLL、data 和许可文件；换目录不需要迁移或清除已有应用数据。当前 EXE 未做 Authenticode 签名，可能出现 SmartScreen 提示；请核对来源和摘要，不要关闭系统保护。
- **iOS 15+**：登记设备后通过 Ad Hoc 定向提供。IPA 不在公开附件中；请[邮件联系](mailto:k34ubll5@gmail.com?subject=Zhiyu%20iOS%20Ad%20Hoc)，勿公开提交设备标识。

升级保留联系人、会话、配对和草稿所在的数据目录；不要使用清理工具删除数据。更名不改变应用标识。重要文件请保留原件。RC2 的更多机型、权限恢复和休眠恢复仍需验证。

## 繁體中文

下載後核對 `SHA256SUMS`，升級前結束舊版並保留應用程式資料。

- Android：直接覆蓋安裝 APK；如遇簽章衝突，請停止並回報，勿先解除安裝。
- macOS：開啟已簽章、公證的 DMG，將 `Zhiyu.app` 複製到 Applications 後退出映像。從 `Nearvia.app` 升級時替換舊應用程式並保留資料，勿同時執行兩份。
- Windows：完整解壓縮，執行 `Zhiyu/sovkit.exe`，保留 DLL、data 及授權檔案。EXE 尚未做 Authenticode 簽章；如出現 SmartScreen 提示，請核對來源與摘要，勿關閉系統保護。
- iOS：僅向已登記裝置定向提供，請透過電子郵件聯絡。

## English

Version 0.1.0-rc.2, build 13. Verify `SHA256SUMS`. Quit the previous version and preserve app data before upgrading.

- **Android arm64 / Android 7.0+**: install the APK over the existing app. If signatures conflict, stop and report it; do not uninstall first.
- **Apple Silicon / macOS 13+**: open the DMG, copy `Zhiyu.app` into Applications, eject the image, then launch the installed copy. Both the app and DMG are Developer ID signed, notarized and stapled. Replace an older `Nearvia.app` while retaining its data; do not run both copies.
- **Windows x64 / Windows 11**: extract the entire ZIP into a writable directory and run `Zhiyu/sovkit.exe`. Keep its DLLs, data folder and notices. Existing app data remains in its original location. The EXE is not Authenticode signed and SmartScreen may appear; verify the source and checksum without disabling system protections.
- **iOS 15+**: private Ad Hoc distribution to registered devices only. Contact the developer by email; do not post identifiers publicly.

Application IDs and data paths are unchanged. Retain important original files. More devices, permission recovery and sleep recovery still need testing. GitHub source archives are not installers.
