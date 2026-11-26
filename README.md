# Octavo 下载中心

公开提供安装包、钢琴音色、更新说明和签名更新清单。应用源码分别保存在私有的 OctavoScore 与 OctavoPDF 仓库。

| 平台 | 当前版本 | 下载 | 更新说明 |
| --- | --- | --- | --- |
| Android 8.0+ | 1.5.1 | [安装包](https://github.com/kyrianhu/Octavo-releases/releases/download/android-1.5.1/Octavo-Android-1.5.1.apk) | [查看说明](notes/android-1.5.1.md) |
| macOS 13+ · Apple Silicon / Intel | 1.0.0 | [安装包](https://github.com/kyrianhu/Octavo-releases/releases/download/macos-1.0.0/Octavo-macOS-1.0.0-Universal.dmg) | [查看说明](notes/macos-1.0.0.md) |

## 钢琴音色

[下载 OctavoPiano.sf2](https://github.com/kyrianhu/Octavo-releases/releases/download/piano-sound-1/OctavoPiano.sf2)，约 35.7 MiB。已有文件和发行记录保留原样，Android 应用可按需下载。

SHA-256：`5239d9f227b2b2771790dc91731a052f8a579b7d4929e8c62e3f52942c7ba860`

## 安装与更新

Android：下载 APK 安装，沿用既有应用 ID 与签名，可覆盖安装并保留资料。

macOS：打开 DMG，将 OctavoPDF 拖入应用程序；更新前请保存文档并正常退出应用。当前安装包尚未做 Apple 公证，若被系统阻止可在“隐私与安全性”中确认打开。

旧版读取旧账号 kyrariiovo 的更新地址，新账号无法接管这些地址。请手动安装迁移后的新版一次，之后 Android 和 macOS 更新检查使用本仓库。

清单位于 `updates/android.json` 和 `updates/macos.xml`，分别经过 RSA / Sparkle EdDSA 签名。安装包校验值见 [SHA256SUMS.txt](updates/SHA256SUMS.txt)。签名私钥、用户文件和应用源码不在公开库。

Windows、iPhone／iPad 安装包不包含在本次发布中。
