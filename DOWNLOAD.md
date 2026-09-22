# 下载与安装

## 当前版本：Mac 0.3.1（2026-09-22）

两个下载地址的安装包完全一样：

- 国内下载（推荐）：<https://wx.xiaohuang365.com/download/>
- GitHub：[v0.3.1 Release](https://github.com/olikahn11/wechat-official-account-assistant-public/releases/tag/v0.3.1)

文件：

- Mac 安装包：`Xiaohuang-Content-Assistant-macOS-0.3.1.dmg`
- Mac 备用压缩包：`Xiaohuang-Content-Assistant-macOS-0.3.1.zip`
- 文件校验：`SHA256SUMS-0.3.1.txt`

需要 macOS 14 或更新版本。

## Mac 安装

1. 双击打开下载的 DMG。
2. 把「小黄内容助手」拖进旁边的「应用程序」文件夹。
3. 打开「应用程序」，双击「小黄内容助手」。
4. 当前版本还没有做苹果公证，第一次打开会被拦：打开「系统设置 → 隐私与安全性」，往下拉到「安全性」，
   找到「小黄内容助手」，点「仍要打开」，再输入这台 Mac 的开机密码确认。之后打开就不会再拦了。

注意：新版 macOS 已经不能用「按住 Control 点图标 → 打开」绕过，请按第 4 步操作。

升级到新版本后，如果弹出「小黄内容助手想要使用你的钥匙串」，输入开机密码、点「始终允许」即可
（软件把连接公众号的凭据存在钥匙串里）。

## Windows

新版 Windows 正在开发。完成前可以先用旧版 [Windows 0.2.1](https://github.com/olikahn11/wechat-official-account-assistant-public/releases/tag/v0.2.1)：
`Xiaohuang-WeChat-Assistant-Windows-0.2.1.exe`（旧版只支持填写开发者接口连接公众号）。
如 SmartScreen 提示未知发布者，请先核对下载地址和 SHA-256，再决定是否继续。

## 安全提示

- 只从本仓库 Release 页面、上面的国内下载地址，或「拾用集」公众号给的入口下载。
- 安装前可以核对文件：在 Mac 的「终端」里运行 `shasum -a 256 下载的文件`，结果应和 `SHA256SUMS-0.3.1.txt` 里的一致。
- 不要向任何人发送公众号的登录密码、开发者密码（AppSecret）或验证码。
