# gallery releases

gallery 的 Windows 客户端发布仓库，提供安装包、版本说明和校验文件。

## 下载

打开 [最新正式版本](https://github.com/galgallery/gallery-releases/releases/latest)，在 **Assets** 中下载 Windows x64 安装器，并阅读同页的 `INSTALLATION.txt`。历史版本见 [Releases](https://github.com/galgallery/gallery-releases/releases)。

安装包文件名格式为 `gallery-<版本>-windows-x64-setup.exe`。同版本的 `SHA256SUMS.txt` 可用于核对下载文件。GitHub 自动生成的 `Source code` 压缩包不是客户端安装包。

## 安装与升级

安装时需要 Windows 管理员确认，可以选择程序目录。升级已有安装时，关闭 gallery 后运行新版安装器，并沿用原安装目录。

游戏库、收藏和下载记录保存在 `%ProgramData%\gallery\data`。升级、修复和卸载保留这些数据；具体操作以所下载版本的 `INSTALLATION.txt` 为准。

## 更新提示

从 0.2.2 开始，客户端启动后会检查本仓库的最新正式版本，也可以在“设置 → 程序更新”手动检查。发现新版本时会显示全局提示，并提供打开版本页面或浏览器下载安装包的入口。安装包需要用户运行，客户端不会自动执行安装器。

0.2.1 不支持 GitHub 检查，需先从 Releases 手动安装一次 0.2.2。GitHub 版本检查与原有签名更新清单属于不同机制；未升级的 0.2.1 不会因本仓库发布新版本而自动收到提示。

这个仓库用于分发客户端发行文件和说明。各版本的功能、测试范围及已知限制见对应 Release 的发布说明。
