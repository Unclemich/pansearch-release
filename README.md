# pansearch-release

网盘聚合搜索 App 的 APK 发布仓（**更新兜底出口**）。

主更新链路走自建后端；当后端不可达时，App 内「检查更新」失败后会出现「去网页手动下载」，指向的就是这里的 latest release。

[>> 下载最新版（latest）](https://github.com/Unclemich/pansearch-release/releases/tag/latest)

- 安装：下载 `app-release.apk` -> 手机上打开 -> 允许「安装未知来源应用」。
- 校验：每个 release 的说明里附当前 APK 的 SHA-256。
- 本仓库只存放 APK 本体，不提供、不托管任何资源内容；App 的检索结果均来自第三方公开索引，使用者自行甄别并承担风险。