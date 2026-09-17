# Nearvia RC1 · Desktop packages / 桌面安装包 / 桌面安裝包

0.1.0-rc.1 · build 10 · added 2026-09-17. Release candidate, not stable.

## 简体中文

- **Windows x64 ZIP**：本轮验证环境为 Windows 11 x64。完整解压到可写目录，打开 `Nearvia/sovkit.exe`。保留同目录 DLL、`data`、许可文件，不要只复制 EXE。若 Windows 显示 SmartScreen 等提示，请先核对下载来源和完整 SHA-256；无需关闭系统安全保护。
- **macOS Apple Silicon DMG / macOS 13+**：退出旧版，打开 DMG，把 `Nearvia.app` 拖入 `Applications`。完成复制后弹出磁盘映像，再从“应用程序”打开。应用与磁盘映像均使用 Developer ID 签名；DMG 已通过 Apple 公证并附加票据，包内应用与已验收 RC1 一致。
- 升级请勿先卸载或清除数据；Windows 请退出旧进程后再替换完整程序目录。重要文件保留原件。
- 在可信局域网内按需允许应用的网络访问，再发现对方并双方确认安全码。Windows 跨设备消息、文件、蓝牙硬件及休眠恢复仍待验收；能够启动不等于全部功能已测。

## 繁體中文

- **Windows x64 ZIP**：本次驗證環境為 Windows 11 x64。完整解壓縮至可寫入目錄，開啟 `Nearvia/sovkit.exe`。保留同目錄 DLL、`data` 與授權文件，勿只複製 EXE。若 Windows 顯示 SmartScreen 等提示，請先核驗下載來源及完整 SHA-256；無需關閉系統安全保護。
- **macOS Apple Silicon DMG / macOS 13+**：結束舊版，開啟 DMG，將 `Nearvia.app` 拖入 `Applications`。完成複製後退出磁碟映像，再從「應用程式」開啟。應用程式與磁碟映像均使用 Developer ID 簽章；DMG 已通過 Apple 公證並附加票據，包內應用程式與已驗收 RC1 相同。
- 升級請勿先解除安裝或清除資料；Windows 請結束舊程序後再替換完整程式目錄。重要檔案請保留原件。
- 在可信區域網路內依需要允許應用程式存取網路，再探索對方並雙方確認安全碼。Windows 跨裝置訊息、檔案、藍牙硬體及睡眠恢復仍待驗收；能夠啟動不代表所有功能均已測試。

## English

- **Windows x64 ZIP**: validated on Windows 11 x64. Extract the entire archive into a writable directory, then open `Nearvia/sovkit.exe`. Keep its DLLs, `data` directory and licenses; do not copy only the EXE. If Windows displays a SmartScreen prompt, verify the download source and full SHA-256 first; do not disable system protections.
- **Apple Silicon macOS DMG / macOS 13+**: quit the old app, open the DMG and drag `Nearvia.app` into `Applications`. Eject the image after copying, then launch the copy in Applications. Both app and image are Developer ID signed; the DMG is Apple notarized and stapled. Its application is unchanged from the previously accepted RC1.
- Do not uninstall or clear data before upgrading. On Windows, quit the old process before replacing the complete program directory. Keep important originals.
- Allow the app's network access as needed on a trusted local network, discover the peer, and confirm the security code on both devices. Windows cross-device messaging/files, Bluetooth hardware and sleep recovery still await acceptance. Startup validation does not establish full functional coverage.

## SHA-256

Use the new `SHA256SUMS-desktop-20260917.txt` for these desktop attachments. The original `SHA256SUMS`, `INSTALL.md`, `RELEASE_NOTES.md` and macOS ZIP remain available as the historical 16 Sep release set; this addendum supplies current desktop installation steps. Android and private iOS distribution are unchanged. GitHub-generated Source code archives are repository documents, not installers.

```powershell
Get-FileHash .\Nearvia-0.1.0-rc.1-windows-x64.zip -Algorithm SHA256
```

```sh
shasum -a 256 Nearvia-0.1.0-rc.1-macos-arm64.dmg
```

Compare all 64 hexadecimal characters with the corresponding checksum line. Download all files listed in the desktop checksum document before using `shasum -a 256 -c SHA256SUMS-desktop-20260917.txt`.
