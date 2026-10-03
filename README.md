# JunoBlueMage PR

青魔法师 ACR，提供国服版与繁中服独立测试版。此仓库仅分发编译后的发布包，不包含项目源码。

支持非耀星D、FATE、副本Boss和天青斗场模式，提供独立控制条、QT、Hotkey、侧栏设置及技能装配功能。界面使用“希望之心”白昼／黑夜主题，可调整面板布局、缩放、排序与位置锁定。

## 国服下载与订阅

- [下载国服 0.3.2 安装包](https://github.com/xiaozhunuonuode/Juno-ACR-PR/releases/download/v0.3.2/JunoBlueMage.PR-0.3.2.zip)
- [国服发布说明](https://github.com/xiaozhunuonuode/Juno-ACR-PR/releases/tag/v0.3.2)

在国服 PR 的 ACR 下载源中添加下面的地址；已有订阅无需更换：

https://raw.githubusercontent.com/xiaozhunuonuode/Juno-ACR-PR/main/Juno.json

青魔在线下载需要国服 PromeRotation 1.5.10.4 或支持 BLU 下载的后续版本。

## 繁中服（TC）獨立測試版

- [下載繁中 0.3.2 測試包](https://github.com/xiaozhunuonuode/Juno-ACR-PR/releases/download/v0.3.2-tc.1/JunoBlueMage.PR-TC-0.3.2.zip)
- [繁中測試版說明與驗證範圍](https://github.com/xiaozhunuonuode/Juno-ACR-PR/releases/tag/v0.3.2-tc.1)

繁中版使用 .NET 9 / Dalamud API13，以 TC SDK 0.1.0-preview.2 編譯，SDK 內 PR 參考版本為 1.3.1.4。介面文字保留簡體中文；尚未完成繁中遊戲內實測。

目前僅提供手動安裝：SDK 對應的 PR 1.3.1.4 線上下載職業清單尚未包含青魔，沒有可用的繁中訂閱。請勿將國服 DLL 或國服訂閱用於繁中環境。

## 手动安装

下载对应客户端的 ZIP，将其中的 `Juno` 文件夹解压到该客户端 PromeRotation 的 ACR 目录，然后在 PR 中加载本地 ACR，选择作者 `Juno`、名称 `JunoBlueMage`。同一作者目录内只保留对应客户端的一份主 DLL。

适用职业：青魔法师。需要自行走位，并按实际副本设置技能装配。繁中测试版请先确认技能装配及木桩上的施法、回执和面板功能。
