
## Windows+Cmder+Chocolatey+Nodejs

系统环境

win10


### chocolatey 安装

[安装文档](https://www.chocolatey.org/install)


以管理员身份打开`CMD`终端，（搜索cmd命令，右键*命令提示符*以管理员身份运行），执行下面命令

```
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```


### cmder 安装


[官方网站](http://cmder.net/)

下载安装即可


`ctrl + t `打开可设置以管理员身份运行cmder



### nodejs 安装


```
choco search nodejs
```

选择版本并安装

```
choco install nodejs 9.2.1
```


### npm 淘宝镜像安装

```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```