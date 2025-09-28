## 官方版本已经对多语言有了完整的支持，这个汉化版本不会再更新
## 请前往官方仓库安装最新版本 [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher)

# ExplorerPatcher
该项目旨在增强 Windows 上的工作环境.

本fork项目为我所翻译的中文版本，官方版本现在已经支持了简体中文，该版本只有部分文本和官方的翻译不同

给原作者赞助PayPal: [here](https://www.paypal.com/donate?business=valentingabrielradu%40gmail.com&no_recurring=0&item_name=ExplorerPatcher&currency_code=EUR) ，邮箱 valentingabrielradu@gmail.com

源repo英文[wiki](https://github.com/valinet/ExplorerPatcher/wiki)

ExplorerPatcher Discord [here](https://discord.gg/gsPcfqHTD2)

![Build status](https://github.com/Yukari316/ExplorerPatcher_zh-CN/actions/workflows/build.yml/badge.svg)

此为对gui进行翻译并适配字符后的汉化版本，目前只汉化了在`Windows 11`系统下运行的GUI文本，`Windows 10`环境暂无计划进行汉化，如果有时间会尽量完成所有汉化并保持更新

### 本地化的部分
> 如果有遗漏可以通过issue或PR进行补充
- Windows11 GUI文本(ExplorerPatcher/settings.reg)
- ~~Windows10 GUI文本(ExplorerPatcher/settings.reg)~~
- 更新相关动态文本及系统通知(ExplorerPatcher/update.c)
- GUI自动生成的文本`swprintf_s函数相关`(ExplorerPatcher/GUI.c)
- GUI自动生成的文本`MessageBoxW对话框`(ExplorerPatcher/GUI.c)
- 更新服务器(ExplorerPatcher/update.h)

## 如何使用

> ⚠⚠⚠⚠
> 
> **安装过程中将会终止`Windows资源管理器(explorer.exe)`的运行，显示器上可能不会显示任何画面（包括桌面）**
>
> **安装过程必须联网！(最好挂梯)**
> 
> ⚠⚠⚠⚠

> 双击安装后如果超过`1分钟`都妹有看到`Windows资源管理器(explorer.exe)`重启，请使用`Win+R`输入`explorer.exe`进行手动重启

1. 在releases中下载最新的版本（或预发布版本） [ep_setup.exe](https://github.com/Yukari316/ExplorerPatcher_zh-CN/releases/).

2. 运行安装程序。安装程序会自动进行系统组件的修改。

3. 安装完成后，程序将重新启动`Windows资源管理器(explorer.exe)`,您将看到熟悉的Windows10任务栏。

4. 需要修改设置选项，右键任务栏并选择“属性”选项进行修改。

## 如何卸载

进入控制面板 -> 程序和功能 -> 双击`ExplorerPatcher` -> 卸载
