# Agora Android Signaling Tutorial

*Read this in other languages: [English](README.en.md)*

这个开源示例项目演示了如何快速集成 Agora 信令 SDK 实现发消息功能。

在这个示例项目中包含了以下功能：

- 登录信服务器
- 查询点对点聊天对象是否在线
- 发送点对点消息，离线接收点对点消息
- 加入频道
- 发送频道消息，接收频道消息
- 离开频道
- 注销信令登录

Agora 信令 SDK 支持 iOS / Android / Web 等多个平台，你可以查看对应各平台的示例项目：
Android: https://github.com/AgoraIO/Agora-Signaling-Tutorial-Android
IOS      : https://github.com/AgoraIO/Agora-Signaling-Tutorial-iOS-Swift
Web    : https://github.com/AgoraIO/Agora-Signaling-Tutorial-Web
MacOS: https://github.com/AgoraIO/Agora-Signaling-Tutorial-macOS-Swift


## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。
然后选择测试项目里的编辑，App Certificate 点击启用，根据操作拿到App Certificate。
将 AppID 和App Certificate 填写进 "app/src/main/res/values/strings_config.xml"

```
<string name="agora_app_id"><#YOUR APP ID#></string>
<string name="agora_app_certificate"><#YOUR APP Certificate#></string>
```



最后用 Android Studio 打开该项目，连上设备，编译并运行。

也可以使用 `Gradle` 直接编译运行。

## 运行环境
- Android Studio 2.0 +
- 真实 Android 设备 (Nexus 5X 或者其它设备)
- 部分模拟器会存在功能缺失或者性能问题，所以推荐使用真机

## 联系我们
- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的 bug, 欢迎提交 [issue](https://github.com/AgoraIO/Agora-Android-Tutorial-1to1/issues)

## 代码许可
The MIT License (MIT).
