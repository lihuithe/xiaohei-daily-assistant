# 小黑日报助手

本仓库用于发布小黑日报助手安装包。

## Windows 下载

[下载 1.7.1 安装程序](https://github.com/lihuithe/xiaohei-daily-assistant/releases/download/v1.7.1/XiaoheiDailyAssistant-Setup-1.7.1.exe)

[查看全部版本](https://github.com/lihuithe/xiaohei-daily-assistant/releases)

安装包 SHA-256 可在对应 Release 的 `SHA256SUMS.txt` 中查看。

## 自动更新

安装包下载可直接使用 Release 附件 URL。接入 electron-updater 时，还需发布与安装包同次构建的更新元数据（Windows 为 `latest.yml`），建议同时发布 `.blockmap` 以支持差分下载。

国内建议使用自有对象存储与 CDN，海外使用 GitHub Releases；发布时先同步安装包并核验哈希，再更新版本清单。
