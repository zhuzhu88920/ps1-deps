# ps1-deps

PowerShell 脚本（powershell-script 项目）运行时下载的程序文件冗余镜像。

主分发源为网盘 `pan.zhuyongfu.cn /raw/soft/`。当主源不可达时，脚本（`lib.ps1` 的 `Invoke-Aria2`）会自动回退到本仓库 Release `assets-v1` 的同名文件，下载 URL 经 `gh-proxy.org` 前缀代理：

    https://gh-proxy.org/https://github.com/zhuzhu88920/ps1-deps/releases/download/assets-v1/<文件名>

本仓库仅存二进制安装包，不含任何 .ps1 脚本源码。
