# Embedded IDE

[![](https://vsmarketplacebadge.apphb.com/version/cl.eide.svg)](https://marketplace.visualstudio.com/items?itemName=CL.eide) [![](https://vsmarketplacebadge.apphb.com/installs/cl.eide.svg)](https://marketplace.visualstudio.com/items?itemName=CL.eide) [![](https://vsmarketplacebadge.apphb.com/downloads/cl.eide.svg)](https://marketplace.visualstudio.com/items?itemName=CL.eide) [![](https://vsmarketplacebadge.apphb.com/rating/cl.eide.svg)](https://marketplace.visualstudio.com/items?itemName=CL.eide)

***

## [English](./README_EN.md)

## 简述 📑

一个 8051/STM8/Cortex-M 的开发工具。用于在 vscode 上提供对 8051, STM8, Cortex-M 项目进行 开发, 编译, 烧录 的功能。

**仅支持 Windows 平台**

![preview](./res/preview/show.png)

***

## 功能特性 🎉

* 提供丰富的项目模板方便快速开始项目
* 支持从标准的 CMSIS Package 安装芯片的外设库
* 一键编译、快速编译，支持多种主流的编译工具
* 一键烧录到芯片，支持多种主流的烧录器
* 内置的串口监视器
* 为调试器 Cortex-debug / STM8-debug 自动生成调试配置

***

## 工具链支持 🔨

#### ![8051](https://img.shields.io/badge/-8051_:-grey.svg) ![status](https://img.shields.io/badge/Keil_C51-✔-brightgreen.svg) ![status](https://img.shields.io/badge/SDCC-✔-brightgreen.svg)

#### ![STM8](https://img.shields.io/badge/-STM8_:-grey.svg) ![status](https://img.shields.io/badge/IAR_STM8-✔-brightgreen.svg) ![status](https://img.shields.io/badge/SDCC-✔-brightgreen.svg)

#### ![ARM](https://img.shields.io/badge/-ARM_:-grey.svg) ![status](https://img.shields.io/badge/ARMCC_V5-✔-brightgreen.svg) ![status](https://img.shields.io/badge/ARMCC_V6-✔-brightgreen.svg) ![status](https://img.shields.io/badge/ARM_GCC-✔-brightgreen.svg)

***

## 使用方法 📖

#### 这里有一个简要的 [使用说明](https://blog.csdn.net/qq_40833810/category_9688932.html)

***

## 版本变化 🔔 (最近3次，详见 [CHANGELOG](./CHANGELOG.md))

> #### 遇到了 BUG ? 反馈途径 [1]：[Github Issue](https://github.com/github0null/eide/issues)，[2]：QQ群: **941749328**

### [v1.18.0]
- 新增：为编译器输出增加高亮
- 更改：调整默认快捷键
- 更改：使用 jsonc 解析某些带注释的 vsocde 配置
***

### [v1.17.2]
- 更改：调整了一些图标
- 更改：调整了一些字符串提示
- 更改：调整了构建工具
***

### [v1.17.1]
- 修复：文件夹变化过快导致的刷新文件夹失败
- 更改：调整一些默认的编译配置
- 新增：支持使用 .eideignore 在打包项目时排除某些文件