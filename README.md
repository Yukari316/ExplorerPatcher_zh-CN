# ExplorerPatcher
该项目旨在增强 Windows 上的工作环境.

给原作者赞助PayPal: [here](https://www.paypal.com/donate?business=valentingabrielradu%40gmail.com&no_recurring=0&item_name=ExplorerPatcher&currency_code=EUR) ，邮箱 valentingabrielradu@gmail.com

![Build status](https://github.com/valinet/ExplorerPatcher/actions/workflows/build.yml/badge.svg)

此为我对gui进行翻译并适配字符后的汉化版本，目前只汉化了在`Windows 11`系统下运行的GUI文本，`Windows 10`环境暂无计划进行汉化

以下为原repo的英文原文

## 如何使用

> **⚠⚠安装过程中将会终止`Windows资源管理器(explorer.exe)`的运行，显示器上不会显示任何画面（包括桌面）⚠⚠**

1. 在releases中下载最新的版本（或预发布版本） [ep_setup.exe](https://github.com/Yukari316/ExplorerPatcher_zh-CN/releases/).

2. 运行安装程序。安装程序会自动进行系统组件的修改。

3. 安装完成后，程序将重新启动`Windows资源管理器(explorer.exe)`,您将看到熟悉的Windows10任务栏。

4. 需要修改设置选项，右键任务栏并选择“属性”选项进行修改。

That's it. It's that simple.

# ExplorerPatcher
This project aims to enhance the working environment on Windows.

PayPal donations: [here](https://www.paypal.com/donate?business=valentingabrielradu%40gmail.com&no_recurring=0&item_name=ExplorerPatcher&currency_code=EUR) or using e-mail address valentingabrielradu@gmail.com

![Build status](https://github.com/valinet/ExplorerPatcher/actions/workflows/build.yml/badge.svg)

## Feature summary

* Choose between Windows 11 or Windows 10 taskbar (with labels support, small icons and lots of customization).
* Disable Windows 11 context menu and command bar in File Explorer and more.
* Open Start to All apps by default, choose number of frequent apps to show, display on active monitor and more.
* Choose between the Windows 11, Windows 10 and Windows NT Alt-Tab window switcher with customization.
* Lots of quality of life improvements for the shell, like:
  * Skin tray menus to match Windows style, make them behave like flyouts and center them relative to the icon.
  * Choose action when left and/or right clicking the network icon.
  * Revert to the Windows 7 search box in File Explorer, or disable Windows Search altogether.
  * Disable immersive menus and use mitigations that help you run the real classic theme without glitches.
  * Learn more about all the functionality offered by this program starting with this article in the wiki, [here](https://github.com/valinet/ExplorerPatcher/wiki/All-features).

Some features may not be available on Windows 10.

## How to?

1. Download the latest version of the [setup program](https://github.com/valinet/ExplorerPatcher/releases/latest/download/ep_setup.exe).
2. Run the installer. It will automatically prompt for elevation, after which it will install the necessary files.
3. When done, you will be greeted with the familiar Windows 10 taskbar. To customize the options offered by the program, right click the taskbar and choose "Properties".

That's it. It's that simple.

## What next?

* Consult the [wiki](https://github.com/valinet/ExplorerPatcher/wiki) - this is highly recommended. There you will find information about more advanced tasks, modes of operation and features offered by this patcher.
* Get familiar with most of the features offered by this patcher [here](https://github.com/valinet/ExplorerPatcher/wiki/All-features).
* Learn how to manage updates and what to expect from new versions and new Windows builds [here](https://github.com/valinet/ExplorerPatcher/wiki/Configure-updates).
* Have a question? Consult the [Frequently Asked Questions](https://github.com/valinet/ExplorerPatcher/wiki/Frequently-asked-questions).
* Some other question? Open a thread in [Discussions](https://github.com/valinet/ExplorerPatcher/discussions).
* Found a bug, have an issue or a problem with the application? Read [here](https://github.com/valinet/ExplorerPatcher/wiki/Reporting-problems) what to do next.
* I highly encourage you to check out the [source code](https://github.com/valinet/ExplorerPatcher/tree/master) and tinker with it. I am open to merging new features, enhancements and fixes; also, I think it provides good insights on topics of interests in this area.

## Known issues

Items marked with "bug" that are still "Open" represent known issues. Active work is undergone regarding an item if it is additionally marked with "investigating". Help is especially required for items marked with "help wanted". Consult the list in [Issues](https://github.com/valinet/ExplorerPatcher/issues).

## Uninstalling

* Use "Programs and Features" in Control Panel, or "Apps and features" in the Settings app or
* Run `ep_setup.exe /uninstall` or
* Rename `ep_setup.exe` to `ep_uninstall.exe` and run that.

## Updating

* The program features built-in updates: go to "Properties" - "Updates" to configure, check for and install the latest updates. Learn more [here](https://github.com/valinet/ExplorerPatcher/wiki/Configure-updates).
* Download the latest version's setup file and simply run it.

## More information

* [How does this work?](https://github.com/valinet/ExplorerPatcher/wiki/How-does-it-work)
* [About antivirus false positives](https://github.com/valinet/ExplorerPatcher/wiki/Antivirus-false-positives)
* [Compiling](https://github.com/valinet/ExplorerPatcher/wiki/Compiling)
