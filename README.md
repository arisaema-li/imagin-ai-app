# 绘梦 App · 发布仓库

**本仓库仅用于分发 Android APK 安装包与版本更新文件，不包含应用源码。**

## 下载

前往 [Releases](https://github.com/arisaema-li/imagin-ai-app/releases) 下载，在对应版本的 **Assets** 中选择 `huimeng-app-<版本>.apk`。

当前内测版：[绘梦 App 0.2.1](https://github.com/arisaema-li/imagin-ai-app/releases/tag/v0.2.1)。

## 每次发布的文件

| 文件 | 用途 |
| --- | --- |
| `huimeng-app-<版本>.apk` | 已签名的 Android 安装包 |
| `huimeng-app-<版本>.apk.sha256` | 安装包完整性校验值 |
| `latest.json` | 应用内更新使用的版本清单 |
| `release-notes-<版本>.md` | 更新说明与验证记录 |

安装包和更新文件仅放在 Releases 的 Assets 中。

## 系统要求与安装

- Android 7.0（API 24）及以上。
- 下载 APK 后按系统提示安装；可能需要允许下载来源安装应用。
- 升级请使用相同包名、相同签名的新版安装包，以保留本地数据。
- 旧调试版与当前内测版的签名可能不同；遇到安装冲突时，先确认数据备份与迁移方式，勿直接卸载旧版。

## 数据与更新

- 会话、图片和模型配置保存在手机本地，与桌面版分别存储。
- 卸载应用可能删除本地数据，请提前妥善备份。
- 应用内更新以 Cloudflare R2 为发布源；GitHub Release 仅作同版产物存档。
- 内测期间的真机使用反馈可提交到 [Issues](https://github.com/arisaema-li/imagin-ai-app/issues)。
