---
description: ExDirectUI 4.1 Manual
---

## ExDirectUI
![Ver](https://img.shields.io/badge/version-4.1-orange "Ver") ![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen "PRs") ![QQ](https://img.shields.io/badge/chat-on%20qq-blue "QQ")

一款基于 GDI/GDI+ & Direct2D 的轻量级用户界面引擎<br>
它相对其他轻量级UI引擎具有 `高效` `安全` `绚丽` `扩展性强` `跨语言` 等特点。<br>
使用本引擎提供的布局文件和主题文件机制, 可以快速高效的设计和实现界面的布局, 大大提高软件开发的效率。

[开始阅读](https://docs.exdui.org)

#### 概要
- 不依赖于大量底层API, 使得可以更灵活的使用更优秀的底层接口, 如绘制引擎可以采用 `GDI/GDI+` 也可采用 `Direct2D` 等新技术
- 使用界面布局文件, 使得界面的布局可与业务逻辑分离, 在某些情况下, 界面布局的修改甚至可以不用重新编译或更新整个程序
- 使用主题文件, 使界面的外观可以轻松更换, 并且可以将该部分交由UI设计师设计, 减轻了程序开发人员的工作负担
- 采用高效的界面逻辑, 使界面绘制的效率很高, 支持父子关系、相对坐标、坐标锁定、光标穿透等控件特性
- 使用了大量优美高效的动画缓动效果, 方便开发人员轻松地制作出各种优秀的用户交互效果
- 所有接口采用 `Unicode` 编码, 只要满足Windows标准, 任何国家任何语言的计算机都可以正常运行
- 采用句柄作为界面元素标识, 界面库文件提供接口用于操作界面元素, 所有界面元素均采用句柄作为标识, 这样做可以方便开发人员的二次封装和跨语言使用

## Github

本文档源码托管在 [https://github.com/ikoude/exdui-doc](https://github.com/ikoude/exdui-doc)
> 本文档持续更新中, 欢迎PR

## License
*Licensed under the WTFPL License*
