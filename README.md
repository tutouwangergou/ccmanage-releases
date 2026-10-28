# Claude 账号切换器 (macOS) 发布仓库 (`ccmanage-releases`)

当前最新版本：**`2.0.0-mac-20261026`**（Node.js `22.23.3` + Electron `44.4.5` Universal）

## 立即下载（v2.0.0-mac-20261026）

- **完整离线安装包（Universal Setup ZIP，324 MB）**：
  [ClaudeSwitcher-Mac-2.0.0-mac-20261026-Universal-Setup.zip](https://github.com/tutouwangergou/ccmanage-releases/releases/download/v2.0.0-mac-20261026/ClaudeSwitcher-Mac-2.0.0-mac-20261026-Universal-Setup.zip)
  - SHA256: `e03a532308591f0675f2996912c9d7a7b44eab5f3b43df4bc502b24f970000e4`
- **应用内热更新包（Update ZIP，185 KB）**：
  [ClaudeSwitcher-Mac-2.0.0-mac-20261026-Update.zip](https://github.com/tutouwangergou/ccmanage-releases/releases/download/v2.0.0-mac-20261026/ClaudeSwitcher-Mac-2.0.0-mac-20261026-Update.zip)
  - SHA256: `ae90f46fb023b55b3209acf7e9332814693aa7c7de88795366264375987184b0`
- **签名更新清单（`latest.json`）**：
  [latest.json](https://github.com/tutouwangergou/ccmanage-releases/releases/latest/download/latest.json)
- **Release 页面**：
  https://github.com/tutouwangergou/ccmanage-releases/releases/tag/v2.0.0-mac-20261026

## 2.0.0 更新说明

- 改为云端账号分发：打开工具先用账号密码登录（服务器 `ccmanage.zhiyoulm.com`，支持记住账号密码与登录状态）。
- 管理员在「账号管理」里上传账号快照（自动按 `C1`、`C2`、`C3`… 顺序编号）并分配给成员，支持开通服务台账（纯台账记录与快照状态独立管理）及远程指令刷新客户端额度。
- 成员在「我的账号」里只看到分配给自己的账号，点击「同步云端」拉取后即可切换；本机自有快照（如本机 kyc）保留在本地互不干扰。
