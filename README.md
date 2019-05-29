# multi-platform-ssr

这是一个跨平台（支持Windows MacOS Linux系统）的`ShadowsocksR`客户端桌面应用。

## 功能特色

- 支持手动添加配置
- 支持二维码扫描添加配置
- 支持从剪贴板复制、从配置文件导入等方式添加配置
- 支持通过点击ss/ssr链接添加配置并打开应用(仅Mac和Windows)
- 支持切换系统代理模式:PAC、全局、不代理
- [内置http_proxy服务](docs/HTTP_PROXY.md)，可在选项中开启或关闭
- 支持配置项变更
- 欢迎你一起来开发完善更多的功能

## 下载

下载地址待完善

## 配置文件位置

- Windows `C:\Users\{your username}\AppData\Roaming\electron-ssr\gui-config.json`
- Mac `~/Library/Application Support/electron-ssr/gui-config.json`
- Linux `~/.config/gui-config.json`

## 快捷键

待完善


## FAQ

[FAQ](./docs/FAQ.md)


## Issus

请在发issue前先查看FAQ里的说明能不能解决你的问题。
在发issue前请先在issue中搜索是否有同类issue，如果有请跟帖。
另外发Bug类issue请详细描述你的使用环境，包括但不限于操作系统、软件版本，操作步骤，报错日志等。


## 开发和构建

``` bash
# 安装依赖
npm install

# 开发时
npm run dev

# 打包构建
npm run build

# 单元测试
npm run mocha

# 代码风格检查
npm run lint

```

## 感谢
Thanks for the electron-ssr author. Welcome developers to rebuild this project , even if you just update sth about the readme.md .  