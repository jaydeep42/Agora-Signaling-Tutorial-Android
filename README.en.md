# Agora Android Signaling Tutorial

*其他语言版本： [简体中文](README.md)*

The Agora Android OpenDuo Sample App is an open-source demo that will help you get message chat integrated directly into your Android applications using the Agora Signal SDK.

With this sample app, you can:

- Login signal server
- Inquire whether the calling object is online
- Send point to point message and receive point to point message off line
- Join channel
- Send channel message, receive channel message
- Leave channel
- Logout signal server

Agora Signal SDK supports iOS / Android / Web. You can find demos of these platform here:

Android: https://github.com/AgoraIO/Agora-Signaling-Tutorial-Android
IOS      : https://github.com/AgoraIO/Agora-Signaling-Tutorial-iOS-Swift
Web    : https://github.com/AgoraIO/Agora-Signaling-Tutorial-Web
MacOS: https://github.com/AgoraIO/Agora-Signaling-Tutorial-macOS-Swift


## Running the App
First, create a developer account at [Agora.io](https://dashboard.agora.io/signin/), and obtain an App ID.
Then select the editor in the test project, click App Certificate, and get the App Certificate according to the operation.
Update "app/src/main/res/values/strings_config.xml" with your App ID and App Certificate.

```
<string name="agora_app_id"><#YOUR APP ID#></string>
<string name="agora_app_certificate"><#YOUR APP Certificate#></string>
```



Finally, open project with Android Studio, connect your Android device, build and run.

Or use `Gradle` to build and run.

## Developer Environment Requirements
- Android Studio 2.0 or above
- Real devices (Nexus 5X or other devices)
- Some simulators are function missing or have performance issue, so real device is the best choice

## Connect Us
- You can find full API document at [Document Center](https://docs.agora.io/en/)
- You can file bugs about this demo at [issue](https://github.com/AgoraIO/Agora-Android-Tutorial-1to1/issues)

## License
The MIT License (MIT).
