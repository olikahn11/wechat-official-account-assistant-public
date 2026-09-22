# 下载与安装

## 当前版本：Mac、Windows 0.3.2（2026-09-22）

两个下载地址的安装包完全一样：

- 国内下载（推荐）：<https://wx.xiaohuang365.com/download/>
- GitHub：[v0.3.2 Release](https://github.com/olikahn11/wechat-official-account-assistant-public/releases/tag/v0.3.2)

文件：

- Mac 安装包：`Xiaohuang-Content-Assistant-macOS-0.3.2.dmg`（需要 macOS 14 或更新版本）
- Mac 备用压缩包：`Xiaohuang-Content-Assistant-macOS-0.3.2.zip`
- Windows 安装程序：`Xiaohuang-Content-Assistant-Windows-0.3.2-Setup.exe`（需要 Windows 10 或 11，64 位）
- Windows 免安装压缩包：`Xiaohuang-Content-Assistant-Windows-0.3.2.zip`
- 文件校验：`SHA256SUMS-0.3.2.txt`

## Mac 安装

1. 双击打开下载的 DMG。
2. 把「小黄内容助手」拖进旁边的「应用程序」文件夹。
3. 打开「应用程序」，双击「小黄内容助手」。
4. 当前版本还没有做苹果公证，第一次打开会被拦：打开「系统设置 → 隐私与安全性」，往下拉到「安全性」，
   找到「小黄内容助手」，点「仍要打开」，再输入这台 Mac 的开机密码确认。之后打开就不会再拦了。

注意：新版 macOS 已经不能用「按住 Control 点图标 → 打开」绕过，请按第 4 步操作。

升级到新版本后，如果弹出「小黄内容助手想要使用你的钥匙串」，输入开机密码、点「始终允许」即可
（软件把连接公众号的凭据存在钥匙串里）。

## Windows 安装

1. 双击下载的安装程序，按提示安装（可以改安装位置）。
2. 如果弹出「Windows 已保护你的电脑」：点「更多信息」，再点「仍要运行」。
   被拦是因为安装包还没有做微软的代码签名，不代表软件有问题；不放心可以先按下面「安全提示」核对文件。
3. 装好后，桌面上会有「小黄内容助手」图标，双击打开。

免安装压缩包：解压后双击里面的「小黄内容助手.exe」。

Windows 这一版能写文章、套模板、插模块和挂件、导入 Word / PDF，写好后一键复制排好版的正文和发布字段，
到公众号后台粘贴发布。扫码连接公众号、一键存进草稿箱在下一个版本加上。

以前装过旧版「小黄公众号助手」（Windows 0.2.1）的：新版装在另一个位置，两个互不影响，旧版里的文章不会自动带过来。
需要在 Windows 上直接连接公众号的，可以先继续用旧版 [Windows 0.2.1](https://github.com/olikahn11/wechat-official-account-assistant-public/releases/tag/v0.2.1)
（`Xiaohuang-WeChat-Assistant-Windows-0.2.1.exe`，只支持填写开发者接口连接）。

## 安全提示

- 只从本仓库 Release 页面、上面的国内下载地址，或「拾用集」公众号给的入口下载。
- 安装前可以核对文件：Mac 在「终端」里运行 `shasum -a 256 下载的文件`，Windows 在 PowerShell 里运行 `Get-FileHash 下载的文件`，
  结果应和 `SHA256SUMS-0.3.2.txt` 里的一致（Windows 显示的是大写字母，大小写不同没关系）。
- 不要向任何人发送公众号的登录密码、开发者密码（AppSecret）或验证码。
