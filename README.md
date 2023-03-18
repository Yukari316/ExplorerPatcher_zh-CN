# ExplorerPatcher
该项目旨在增强 Windows 上的工作环境.

给原作者赞助PayPal: [here](https://www.paypal.com/donate?business=valentingabrielradu%40gmail.com&no_recurring=0&item_name=ExplorerPatcher&currency_code=EUR) ，邮箱 valentingabrielradu@gmail.com

![Build status](https://github.com/Yukari316/ExplorerPatcher_zh-CN/actions/workflows/build.yml/badge.svg)

此为对gui进行翻译并适配字符后的汉化版本，目前只汉化了在`Windows 11`系统下运行的GUI文本，`Windows 10`环境暂无计划进行汉化，如果有时间会尽量完成所有汉化并保持更新

### 本地化进度
> 如果有遗漏可以通过issue或PR进行补充
- [x] Windows11 GUI文本(ExplorerPatcher/settings.reg)
- [ ] Windows10 GUI文本(ExplorerPatcher/settings.reg)
- [x] 更新相关动态文本及系统通知(ExplorerPatcher/update.c)
- [x] GUI自动生成的文本`swprintf_s函数相关`(ExplorerPatcher/GUI.c)
- [x] GUI自动生成的文本`MessageBoxW对话框`(ExplorerPatcher/GUI.c)
- [x] 更新服务器(ExplorerPatcher/update.h)

## 如何使用

> ⚠⚠⚠⚠
> 
> **安装过程中将会终止`Windows资源管理器(explorer.exe)`的运行，显示器上可能不会显示任何画面（包括桌面）**
> 
> ⚠⚠⚠⚠

1. 在releases中下载最新的版本（或预发布版本） [ep_setup.exe](https://github.com/Yukari316/ExplorerPatcher_zh-CN/releases/).

2. 运行安装程序。安装程序会自动进行系统组件的修改。

3. 安装完成后，程序将重新启动`Windows资源管理器(explorer.exe)`,您将看到熟悉的Windows10任务栏。

4. 需要修改设置选项，右键任务栏并选择“属性”选项进行修改。

# 以下为原repo的英文原文

# ExplorerPatcher
This project aims to enhance the working environment on Windows.

PayPal donations: [here](https://www.paypal.com/donate?business=valentingabrielradu%40gmail.com&no_recurring=0&item_name=ExplorerPatcher&currency_code=EUR) or using e-mail address valentingabrielradu@gmail.com

[Read more](https://github.com/valinet/ExplorerPatcher/wiki)