# [![AppVeyor Build Status](https://github.com/yiluoe/moonlight-ios/blob/yiluoe/Limelight/Images.xcassets/AppIcon.appiconset/Other/64x64.png?raw=true)](https://ci.appveyor.com/project/cgutman/moonlight-ios/branch/master) Moonlight(IOS) by yiluoe

IOS版Moonlight可让您将全套游戏和应用程序从功能强大的台式电脑传输到 iOS 设备，例如 IPhone、IPad 和 Apple TV，甚至是 Apple Vision 和 Apple Watch。

Moonlight 也有 [PC 端](https://github.com/moonlight-stream/moonlight-qt) 和 [Android 端](https://github.com/moonlight-stream/moonlight-android)。

## 怎么构建呢？

* 从 [App Store 页面](https://apps.apple.com/us/app/xcode/id497799835) 安装 Xcode
* 运行 `git clone --recursive https://github.com/yiluoe/moonlight-ios`
  *  如果你已经克隆了仓库那么你可以直接在项目目录下运行 `git submodule update --init --recursive`
* 在 Xcode 中打开 Moonlight.xcodeproj
* 要在真实设备上运行，您需要在本地修改签名选项:
  * 点击左侧边栏顶部的 "Moonlight"
  * 点击 "Signing & Capabilities" 选项卡
  * 在 "Targets" 下如果是 iOS/iPadOS 选择 "Moonlight", 如果是 tvOS 选择 "Moonlight TV"
  * 在 "Team" 下拉菜单中, 选择你的账户. 如果没有你的账户名，您需要先使用 Apple 帐户登录 Xcode
  * 将 "Bundle Identifier" 更改为其他内容. 例如 cn.你的名字.moonlight
  * 然后你就可以将你的设备作为目标编译并运行啦～

**## 贡献者**

![Contributors](https://contrib.rocks/image?repo=yiluoe/moonlight-ios)