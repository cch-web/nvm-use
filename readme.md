# windows为例
## 首先卸载已安装的node
### 1.[下载nvm-setup.exe](https://github.com/coreybutler/nvm-windows/releases/tag/1.1.9)
### 2.nvm ls available 命令列出可用的node版本
### 3.一般首先会下载LTS稳定版本列中第一个版本 比如:nvm install 16.16.0 或者 nvm install 16（默认安装16版本中最新的版本）
### 4.nvm ls 命令会列出已经安装好的node版本
### 5.nvm use xxx.xxx.xxx指定/切换node版本号,如果报错exit status 1则使用win+R然后ctrl+shift+enter使用管理员身份打开窗口执行命令
### 6.nvm current命令查看当前node版本号
### 7.nvm uninstall xxx.xxx.xxx卸载指定node版本
