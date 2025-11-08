# ![Banner](./Assets/Banner.png)
<div align="center">
    <img width="100px" src="./Assets/Icon.png" align="center" alt="RStatus" />
    <h2 align="center">火苗调试器</h2>
    <p align="center">适用于某软件的窗口置顶解除工具。</p>
</div>
<div align="center">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/virelyx258/Flame-Debugger?style=for-the-badge"> 
    <img alt="GitHub" src="https://img.shields.io/github/license/virelyx258/Flame-Debugger?style=for-the-badge"> 
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/virelyx258/Flame-Debugger?style=for-the-badge"> 
</div>


## 简介

> [!IMPORTANT]
> 以下内容于2025年11月8日撰写，本软件的实际功能可能会因新版本推送而与简介有所差异。

**火苗调试器**是一个窗口置顶解除工具，使用`易语言`编写。其主要功能是将某软件的`强制置顶窗口`解除置顶，以达到提高用户使用效率的目的。

- 技术栈：`易语言`
- 支持的操作系统：WindowsNT 4.0 以上

## 声明
> [!NOTE]
> 以下简称 `火苗调试器` 为 **本软件** 。
- 本软件使用**易语言**编写，部分反病毒软件可能会向用户报告本软件可能危害此电脑，请**忽略这一类提示并信任本软件**。
- 应用程序内提供的部分功能可能需要向用户申请 `管理员权限`。
- 本软件会在运行目录生成一个 `Config.ini` 用于保存配置项。

## Todo List
- [x] 支持窗口取消置顶
- [x] 支持自动匹配窗口
- [ ] 高DPI适配

## 下载
前往[Release](https://github.com/virelyx258/Flame-Debugger/releases)页面进行下载。

## 编译

该软件采用易语言编写，如果你想要编译该软件，请准备以下环境：

- Windows 7 和以上版本的电脑
- 易语言 v5.93 或更高版本

同时，该软件引用了 [精易模块](https://ec.125.la/)，请在编辑 / 引用代码时遵守相关协议。

## 使用教程

> [!NOTE]
> 使用前，请确保 `AntiFlame.dll` 与主程序在同一目录下。否则程序将无法正常运行。

1. 在 PC 上启动`某软件`和`火苗调试器`。

2. 在`火苗调试器`主窗口中，点击`延时10秒自动解除窗口置顶`按钮。（推荐）
3. 立刻进入`某软件`的强制置顶窗口，并持续用鼠标点击该窗口，确保其处于焦点状态。
4. 等待约 10 秒钟。
5. `火苗调试器`会自动将`某软件`的强制置顶窗口包裹到一个容器中，达到`窗口化`的效果。

此时，您就可以高效地进行您的工作了。

**注意：`火苗调试器`主窗口下方的`手动操作`模块，其作用是方便进行原理学习，到了真正的使用场景上，`手动操作`模块也许不能帮到您。所以，`手动操作`使用方法不再介绍。**

## 协议

本软件采用 **Apache License 2.0** 协议，在分发、修改软件时 **必须要标注** 源码来源和原作者，并且在相关的文件或页面中保留原许可证的版权声明和免责声明。此外，你可以选择修改并分发该软件的修改版本，但无需开源你的修改，只需在分发时附上适用的 **Apache License 2.0** 协议副本。

## 其它
 - [易语言官网](https://dywt.com.cn/)
 - [Apache License v2](https://www.apache.org/licenses/LICENSE-2.0)