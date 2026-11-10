# LumePlay Releases

LumePlay 的 Windows x64 绿色版发布与自动更新仓库。源码保存在私有仓库中。

前往 [最新正式版](https://github.com/lengend0/LumePlay-Releases/releases/latest)，下载附件中的 `LumePlay-版本号-win-x64-portable.zip`。GitHub 自动生成的 `Source code` 压缩包不是运行程序。

首次使用或从旧绿色版升级：正常退出 LumePlay，将完整 ZIP 解压到所选目录，运行根目录的 `LumePlay.exe`；保留完整的 `runtime` 和 `licenses` 文件夹。

从 2.0.2 开始，应用启动后会检查正式版本，在确认后下载并重启更新；也可在“设置 → 应用更新”中手动检查。个人账号、设置、弹幕绑定与缓存保存在本机数据目录，更新只替换程序文件。受保护的安装目录可能请求 Windows 管理员权限。

`update.json` 与 `update.sig` 用于应用内签名验证，请使用对应正式版本的原始附件。
