JMessage-SDK-iOS
=============

这是一个 [极光IM](https://www.jpush.cn/common/im) iOS 版本 SDK 的一个非官方镜像。 

官方开发指南在这里：[http://docs.jpush.io/client/im_sdk_ios/](http://docs.jpush.io/client/im_sdk_ios/).

极光IM 为 App 开发者提供易用可靠的即时通信云服务，搭建应用用户间自由的交流通道，增强产品社会化属性。

### 使用 CocoaPods 安装
[CocoaPods](http://cocoapods.org) 是开发 OS X 和 iOS 应用程序的一个第三方库的依赖管理工具。

推荐这样配置 Podfile:

```ruby
# The front repo is prior if conflicted
# CocoaPods private repo
source 'https://github.com/jcccn/PodSpecs.git'
# CocoaPods master repo
source 'https://github.com/CocoaPods/Specs.git'

platform :ios,'7.0'

# ignore all warnings from all pods
inhibit_all_warnings!

pod 'JMessage'

```

也可以这样配置Podfile:

```ruby
# CocoaPods master repo
source 'https://github.com/CocoaPods/Specs.git'

platform :ios,'7.0'

# ignore all warnings from all pods
inhibit_all_warnings!

pod 'JMessage', :git => 'https://github.com/jcccn/JMessage-SDK-iOS.git'

```

### 产品特点
##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-im-feature-chat.png"> 聊天功能
- 极光 IM 提供单聊，群聊的方式。聊天内容支持文本，图片，语音以及自定义消息等多种格式。终端平台覆盖 Android，iOS 以及 Web 客户端。
	
##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-im-feature-upgrade.png"> 平滑升级
- 极光 IM 完美兼容极光推送的全部功能，JPush 服务使用者可以直接集成 JMessage SDK 平滑升级到极光 IM 让应用具备聊天的能力。

##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-im-feature-integration.png"> 集成模式
- 无好友模式极光最小化保留用户数据，最大限度保护用户隐私。有好友模式开发者无需搭建基础即可快速搭建全功能的 IM 业务。

##### <img src="https://www.jpush.cn/res/v3/images/common/v4/product-im-feature-technology.png"> 技术基础
- 以极光推送的大规模、高并发、稳定的推送服务为技术基础；共享极光推送的多区域分布接入资源，采用一条连接同时维护 JMessage 与 JPush 两个服务。