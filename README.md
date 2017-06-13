# cordovaDemo
cordovaDemo
iOS版Cordova安装开发

Cordova：

在介绍Cordova之前，必须先提一下PhoneGap。PhoneGap 是Nitobi软件公司2008年推出的一个框架，旨在弥补web 和iOS 之间的不足，使得web 和 iPhone SDK 之间的交互更容易。后来又加入了Android SDK 和BlackBerry SDK，再然后又陆续加入了更多的平台。但是在2011年，Nitobi公司被Adobe收购，PhoneGap也被提交到Apache Incubator。由于Adobe现在拥有PhoneGap商标，PhoneGap v2.0版产品就更名为Apache Cordova。据说Cordova是Nitobi团队当时坐落的街道名称，用此名来纪念Nitobi团队的贡献。Apache Cordova是从PhoneGap中抽出的核心代码，是驱动PhoneGap的核心引擎。

提供了一组设备相关的API，通过这组API，移动应用能够以JavaScript访问原生的设备功能，如摄像头、麦克风等。Cordova还提供了一组统一的JavaScript类库，以及为这些类库所用的设备相关的原生后台代码。Cordova支持如下移动操作系统：iOS, Android,ubuntu phone os, Blackberry, Windows Phone, Palm WebOS, Bada 和 Symbian。

什么是Cordova插件?

插件就是一些附加代码用来提供原生组件的JavaScript接口，他允许你的App可以使用原生设备的能力，超越了纯粹的Web App。

Cordova的安装
安装cordova命令行工具，贴出官网的步骤：(可以去官网看看)

$ npm install -g cordova

$ cordova create MyApp

$ cd MyApp

$ cordova platform add ios

$ cordova run ios

官网就是官网的，对于小白来说还是看不懂。

下面贴出自己的实践过程：
http://www.jianshu.com/p/fb7201008fc9
更多资源欢迎进入学习交流平台：QQ群：224110749 有问题也可以联系我QQ:1107214478(一个做iOS开发的小生，但是我并不觉的我是在做iOS)
