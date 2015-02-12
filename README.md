# Awesome iOS

A curated list of awesome iOS frameworks, libraries, tutorials, plugins Xcode, components and much more. 
The list is divided into categories such as Frameworks, Components, Testing and others,  open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/CONTRIBUTING.md).

### Contents
 - [入门指南(Getting Started)](#getting-started)
 - [库和框架(Library and Frameworks)](#libraries-and-frameworks)
     - [缓存(Cache)](#cache)
     - [核心数据(Core Data)](#core-data)
     - [数据库(Database)](#database)
     - [透明指示器(HUD)](#hud)
     - [图像(Images)](#images)
     - [JSON](#json)
     - [日志(Logging)](#logging)
     - [地图(Maps)](#maps)
     - [网络(Networking)](#networking)
     - [Push](#push)
     - [Passbook](#passbook)
     - [Text](#text)
     - [UI](#ui)
     - [Websocket](#websocket)
     - [代码质量(Code Quality)](#code-quality)
     - [分析(Analytics)](#analytics)
     - [支付(Payments)](#payments)

- [项目搭建(Project setup)](#project-setup)
- [依赖管理(Dependency Manager)](#dependency-manager)
- [测试(Testing)](#testing)
    - [测试驱动开发(TDD) / 行为驱动开发(BDD)](#tdd--bdd)
    - [界面测试(UI Testing)](#ui-testing)
    - [beta版本发布(Beta Distribution)](#beta-distribution)
- [工具链(Toolchains)](#toolchains)
- [快速开发(Rapid Development)](#rapid-development)
- [部署(Deployment)](#deployment)
- [SDK](#sdk)
- [Xcode开发环境](#xcode)
    - [插件(Plugins)](#plugins)
    - [开发包管理(Package Manager)](#package-manager)
    - [主题(Themes)](#themes)

- [Swift语言](#swift)
    - [网站(Websites)](#websites)
    - [视频(Videos)](#videos)
    - [界面(UI)](#ui-1)

- [编码风格指南(Style Guides)](#style-guides)
- [不错的网站(Good Websites)](#good-websites)
    - [新闻博客和推送(News, Blogs and Feeds)](#news-blogs-and-feeds)
    - [UIKIt references](#uikit-references)
    - [组件和开发包(Components and Packages)](#components-and-packages)
    - [论坛和讨论列表(Forums and discuss lists)](#forums-and-discuss-lists)
    - [教程和主题讨论(Tutorials and Keynotes)](#tutorials-and-keynotes)
    - [原型开发(Prototyping)](#prototyping)

- [Twitter](#twitter)
- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)
- [投稿(Contributing)](#contributing)

# Getting Started
 * [Road Map iOS](https://developer.apple.com/library/ios/referencelibrary/GettingStarted/RoadMapiOS/) - Apple出品的《开启iOS应用开发》
 * [Lifehacker](http://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175) - 想写iOS应用，该从哪里着手?
 * [Codeproject](http://www.codeproject.com/Articles/88929/Getting-Started-with-iPhone-and-iOS-Development) - iPhone/iOS开发指南.
 * [Ray Wenderlich](http://www.raywenderlich.com/38557/learn-to-code-ios-apps-1-welcome-to-programming) - 学习开发iOS应用.
 * [Stanford - Developing Apps to iOS](https://itunes.apple.com/us/itunes-u/developing-apps-for-ios-hd/id395605774?mt=10) - 斯坦福iOS应用开发课程(视频和音频)
 * [Stanford - Developing iOS 8 Apps with Swift](https://itunes.apple.com/us/course/developing-ios-8-apps-swift/id961180099) - 斯坦福2015使用Swift开发iOS8应用课程.

# Libraries And Frameworks

### Cache
 * [SDURLCache](https://github.com/steipete/SDURLCache) - iPhone/iPad上URLCache盘上(on-disk)缓存机制的分支(Star 518).

### Core Data
 * [CWCoreData](https://github.com/jayway/CWCoreData) - 工具附件集合，用来简化核心数据(CoreData)框架的并发处理(Star 70).
 * [Objective-Record](https://github.com/mneorr/Objective-Record) - 以轻量级活动记录(ActiveRecord)方式管理核心数据对象(Star 1011).
 * [Magical Record](https://github.com/magicalpanda/MagicalRecord) -  获取CoreData超级棒的项目库(Star 6224).
 * [SSDataKit](https://github.com/soffes/SSDataKit) - 帮助消除CoreData例行代码(boilerplate code)的项目库(Star 424).
 * [ios-queryable](https://github.com/martydill/ios-queryable) - 提供CoreData的IQueryable/IEnumerable接口实现(Star 219)
 * [ReactiveCoreData](https://github.com/apparentsoft/ReactiveCoreData) - 尝试将CoreData带入ReactiveCocoa领域的项目库(Star 225).
 * [Ensembles](https://github.com/drewmccormack/ensembles) - CoreData同步框架(Star 1117).
 * [Mogenerator](https://github.com/rentzsch/mogenerator) - 自动化CoreData代码产生器项目库(Star 2289).

### Database
 * [Realm](https://github.com/realm/realm-cocoa) - CoreData和SQLite的替代品，简单，新颖快速(Star 2955).

### HUD
 * [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - 一个嵌入式指示器，用于背景线程完成某项工作的时候，显示一个带有标签的透明提示(Star 6526).
 * [SVProgressHUD](https://github.com/TransitApp/SVProgressHUD) - 为你的iOS应用打造的简洁轻量级进度指示器(Star 4653).
 * [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - 一个轻量级易用的指示器(Star 462).

### Images
 * [GPU Image](https://github.com/BradLarson/GPUImage) - iOS开源的，基于GPU的图像和视频处理框架(Star 7937).
 * [UIImage DSP](https://github.com/gdawg/uiimage-dsp) - 采用vDSP/Accellerate框架加速的iOS UIImge处理函数库(Star 344).
 * [QR Code Scanner](http://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR码工具库
 * [AsyncImageView](https://github.com/nicklockwood/AsyncImageView) - 实现非锁定用户界面情况下，异步载入和显示图像的UIImageView扩展(Star 671).
 * [SDWebImage](https://github.com/rs/SDWebImage) - 带缓存支持的异步图像下载器(Star 7702).

### JSON
 * [JSONKit](https://github.com/johnezang/JSONKit) - Objective-C JSON(Star 4682).
 * [TouchJSON](https://github.com/TouchCode/TouchJSON) - 基于Objective-c的JSON编码数据的解析和产生器(Star 797).
 * [JSON-Framework](https://github.com/stig/json-framework) -  实现基于Objective-C的严格的JSON解析器和产生器(Star 3496).
 * [Mantle](https://github.com/Mantle/Mantle) - Cocoa and Cocoa Touch的建模框架(Star 5571).
 * [Groot](https://github.com/gonzalezreal/Groot) - 支持JSON自动数组和CoreData管理对象之间的相互转换的项目库(Star 246).
 * [KZPropertyMapper](https://github.com/krzysztofzablocki/KZPropertyMapper) - 以最小代码量实现数据映射和校验的项目库(Star 910).
 * [JSONModel](https://github.com/icanzilb/JSONModel) - 基于JSON的数据建模神奇框架，快速高效创建原子，智能数据模型类(Star 2798).
 * [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - 提供更好的方式来在Swift中处理JSON数据(Star 3296).
 
### Logging
 * [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - 针对Mac和iOS提供一套简单快速，灵活有效的日志框架(Star 4420).
 * [NSLogger](https://github.com/fpillet/NSLogger) - 提供一套高效率日志工具，能够显示运行在多种平台(Mac OS X, iOS和Android)上客户端应用产生的日志信息(Star 2528).

### Maps
 * [Route-me](https://github.com/route-me/route-me) - iOS开源地图库(Star 1142).
 * [MapBox](https://github.com/mapbox/mapbox-ios-sdk) - Mapbox iOS SDK, 一个MapKit的开源替代库(Star 772).

### Networking
 * [AFNetworking](https://github.com/AFNetworking/AFNetworking) - 优雅的iOS/OS X网络框架(Star 15759).
 * [RestKit](http://restkit.org/) - 为iOS编写的Objective-c框架，用于实现同REST风格web服务之间快速，简洁高效交互.
 * [FSNetworking](https://github.com/foursquare/FSNetworking) - Foursquare iOS网络项目库(Star 377).
 * [ASIHTTPRequest](https://github.com/pokeb/asi-http-request) - 基于objective-c，为HTTP请求提供的CFNetwork包装器(Star 5300).
 * [Overcoat](https://github.com/gonzalezreal/Overcoat) - 一个小而强大的库，使创建REST客户简单而有趣(Star 524).

### Push
 * [Orbiter](https://github.com/mattt/Orbiter) - iOS推送通知注册器(Star 600).
 * [PEM](https://github.com/KrauseFx/PEM) - 自动生成和更新推送通知配置(Star 339).

### Passbook
 * [passbook](https://github.com/frozon/passbook) - 用于为iOS 6+的Passbook生成pkpass(Star 149).
 * [Dubai](https://github.com/nomad/dubai) - 产生和预览PassBook内容(Star 245).

### Text
 * [Twitter Text Obj](https://github.com/twitter/twitter-text-objc) - Twitter文本处理库的objective-c实现(Star 633).
 * [Nimbus](http://nimbuskit.info/) - iOS软件设计老兵的工具库.

### UI
 * [ActionSheetPicker-3.0](https://github.com/skywinder/ActionSheetPicker-3.0/) - 在iOS中快速创建下拉式UIPickerView/ActionSheet功能(Star 703).
 * [FlatUIKit](https://github.com/Grouper/FlatUIKit) - 一组很棒的iOS平面UI组件集合(Star 5126).
 * [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) - 浮动标签扩展(Star 3619).
 * [SSBouncyButton](https://github.com/StyleShare/SSBouncyButton) - iOS7风格的弹性按钮UI组件（Star 64).
 * [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) - 一个优雅的iOS消息UI组件(Star 2605).
 * [TSMessages](https://github.com/toursprung/TSMessages) - 在屏幕顶部显示提示信息视图，比如成功，失败，错误等(Star 2871).
 * [NZAlertView](https://github.com/NZN/NZAlertView) - 简单而直观的警报视图。类似于推送通知的效果(Star 425).
 * [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell) - 一个易于使用的UITableViewCell子类，允许显示带有多种变化的拖拽按钮(Star 1068).
 * [ARAutocompleteTextView](https://github.com/alexruperez/ARAutocompleteTextView) - UITextView子类，运行时自动显示文字提示信息，特别适用于邮件TextViews(Star 159）
 * [TGCameraViewController](https://github.com/tdginternet/TGCameraViewController) - 基于AVFoundation的定制相机，美观，易于与iOS整合项目(Star 701).
 * [BWWalkthrough](https://github.com/ariok/BWWalkthrough) - 用来帮助你的App制作使用Demo的项目库(Star 858).
 * [ENSwiftSideMenu] (https://github.com/evnaz/ENSwiftSideMenu) - 一个Swift为iOS7/8编写简单的滑动菜单(Star 656).
 * [MDCSwipeToChoose] (https://github.com/modocache/MDCSwipeToChoose) - 使用Swipe手势来表示喜欢或不喜欢任何视图(Star 1036)
 * [UIColor-Hex-Swift] (https://github.com/yeahdongcn/UIColor-Hex-Swift) - 提供一种创建基于RGBA十六进制字符串的自动释放颜色的方便方法(Star 89).


### WebSocket
 * [Socket Rocket](https://github.com/square/SocketRocket) - 一个兼容Objective-C WebSocket的客户端项目库(Star 3382).

### Code Quality
 * [KZBootstrap](https://github.com/krzysztofzablocki/KZBootstrap) - iOS项目bootstrap，旨在引导高品质的编码(Star 1190).
 * [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - 自定义断言(Assertion)集, 能够自动产生NSError,支持debug模式的断言和Release编译下的错误处理(Star 66).
 * [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - 当UIKit在后台线程使用的时候产生断言(Assertion)的简单参考代码片段(Star 66).
 
### Analytics
 * [Flurry Analytics](http://www.flurry.com) - 免费APP分析API.
 * [Parse Analytics](https://parse.com/products/analytics) - 测量应用程序使用，跟踪bug等.
 
### Payments
 * [Stripe](https://stripe.com) - 在应用程序中集成支付功能，适合于对后端了解有限的用户群.
 * [Braintree](https://www.braintreepayments.com) - 对前$50K的支付处理免费，需要后端支持.

# Project setup
 * [crafter](https://github.com/krzysztofzablocki/crafter) - 采用定制的DSL语法，帮助你来配置iOS项目模板的命令行工具(CLI)，快速简单高效(Star 291).
 * [liftoff](https://github.com/thoughtbot/liftoff) - 又一个创建iOS项目的命令行工具(CLI)(Star 878).
 * [KZBootstrap](https://github.com/krzysztofzablocki/KZBootstrap) - iOS项目bootstrap，用于引导高质量编码(Star 291).
 * [amaro](https://github.com/crushlovely/Amaro) - 功能丰富的iOS样板代码(boilerplate cdoe)(Star 179).

# Dependency Manager

 * [Cocoa Pods](http://cocoapods.org/) - 提供一个Objective-C项目的依赖管理器，包含了工具库，能够帮助你优雅的扩展自己的项目.
 * [Xcode Maven](http://sap-production.github.io/xcode-maven-plugin/site/) - 一个Xcode Maven插件，用于帮助运行嵌套在Maven中的Xcode编译.
 * [Gradle](http://openbakery.org/gradle.php) - 一个Gradle Xcode插件， 帮助使用Gradle来编译iOS或者Mac OS X项目.
 * [Carthage](https://github.com/Carthage/Carthage) - 一个简单，分散化的Cocoa依赖管理器(Star 1890).

# Testing

### TDD / BDD
 * [Kiwi](https://github.com/kiwi-bdd/Kiwi) - 为iOS开发行为驱动开发库(Star 2491).
 * [Specta](https://github.com/specta/specta) - 面向Objective-c和Cocoa的一个轻量级测试驱动开发(TDD)/行为驱动开发(BDD)框架(Star 1049).
 * [Quick](https://github.com/Quick/Quick) - 面向Swift和Objective-C的行为驱动开发(BDD)框架(Star 1974).

### UI Testing
 * [CrashMonkey](https://github.com/mokemokechicken/CrashMonkey) - iOS Monkey Test工具(Star 40).
 * [appium](http://appium.io/) - 一个开源的自动化测试框架，用于本机和混合移动应用程序.
 * [robotframework-appiumlibrary](https://github.com/jollychang/robotframework-appiumlibrary) - 基于appium的RobotFramework测试库(Star 24).
 * [Cucumber](http://cukes.info/) - iOS行为驱动开发库.
 * [Kif](https://github.com/kif-framework/KIF) - 一个iOS功能测试框架(Star 3008).
 * [Subliminal](https://github.com/inkling/Subliminal) - iOS集成测试方案(Star 732).
 * [UIAutomation](https://developer.apple.com/library/ios/documentation/DeveloperTools/Reference/UIAutomationRef/Introduction/Introduction.html) - 提供一个JavaScript库，当App运行于链接设备上的时候，可以用它来编写测试脚本去测试App用户接口元素.
 * [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - 基于Selenium/WebDriver， 用于测试任何iOS原生,混合或者移动Web应用的框架.
 * [Zucchini](http://www.zucchiniframework.org/) - 可视化iOS测试框架.

### Beta Distribution
 * [Crashlytics](https://www.crashlytics.com/) - Crash报告和beta测试服务.
 * [TestFlight Beta Testing](https://developer.apple.com/testflight/) - 托管在iTunes Connect中的beta测试服务(iOS 8或更新版本).
 * [HockeyApp](http://hockeyapp.net/) - 使用HockeyApp, 可以帮助你分发beta版本应用程序，收集Crash报告，获取用户反馈，分析测试覆盖率.

# Toolchains
 * [RubyMotion](http://www.rubymotion.com/) - RubyMotion是一个革命性的工具链，采用Ruby语言，帮助你为iPhone，iPad和Mac快速开发和测试原生iOS和OS X应用程序.

# Rapid Development
 * [KZPlayground](https://github.com/krzysztofzablocki/KZPlayground) - 基于Objective-c的快速原型开发和学习的试验田(Star 1411).
 * [dyci](https://github.com/DyCI/dyci-main) - 代码注入工具(Star 644).

# Deployment
 * [fastlane](http://fastlane.tools/) 帮助你为不同环境定义和运作部署流水线(deployment pipelines).
 * [deliver](https://github.com/krausefx/deliver) 一键支持部署截屏, 应用元数据(metadata)和应用更新到App Store(Star 1612).
 * [snapshot](https://github.com/krausefx/snapshot) 自动创建所有语言，所有设备的应用截屏(Star 812).

# SDK
 * [Spotify](https://github.com/spotify/ios-sdk) Spotify iOS开发包(Star 328)
 * [Facebook](https://github.com/facebook/facebook-ios-sdk) Facebook iOS开发包(Star 4670)
 * [Google Analytics](https://developers.google.com/analytics/devguides/collection/ios/v3/) 谷歌分析IOS开发包
 * [Paypal iOS SDK](https://github.com/paypal/PayPal-iOS-SDK) 贝宝移动开发包，帮助原生应用轻松支持贝宝和信用卡支付功能(Star 365).
 * [Pocket](https://github.com/Pocket/Pocket-ObjC-SDK) 保存信息到Pocket的开发包(Star 153)
 * [Tumblr](https://github.com/tumblr/TMTumblrSDK) 方便集成Tumblr数据到iOS或者OS X应用的开发包(Star 246).
 * [Evernote](https://github.com/evernote/evernote-sdk-ios) Evernote IOS开发包(Star 381)
 * [Box](https://github.com/box/box-ios-sdk-v2) 支持Box API的iOS和OS X开发包(Star 123)
 * [OneDrive](https://github.com/liveservices/LiveSDK-for-iOS) Live iOS开发包(Star 129)
 * [Stripe](https://github.com/stripe/stripe-ios) Stripe iOS和OS X绑定库(Star 331) 
 * [Venmo](https://github.com/venmo/venmo-ios-sdk) 通过Venmo,为iOS应用提供建立和接受支付的能力(Star 54)
 * [AWS](https://github.com/aws/aws-sdk-ios) 亚马逊Web服务iOS开发包(Star 182)
 * [Zendesk](https://github.com/zendesk/zendesk_sdk_ios) Zendesk移动iOS开发包(Star 8)

# Xcode

### Plugins
 * [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap) - 为Xcode代码编辑器添加迷你映射图(MiniMap)的插件(Star 680).
 * [Show in Github](https://github.com/larsxschneider/ShowInGitHub) - 支持为当前在编辑器窗口中选中代码行，打开Github提交页面的Xcode插件(Star 181).
 * [BBUFullIssueNavigator](https://github.com/neonichu/BBUFullIssueNavigator) - 支持在Issue浏览器中现实所有issue的Xcode插件(Star 187).
 * [BBUDebuggerTuckAway](https://github.com/neonichu/BBUDebuggerTuckAway) - 一旦在代码编辑器中进行编码操作，该插件就能帮助自动隐藏调试器X(Star 484).
 * [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander) - 该插件提供switch case语句自动补全功能(Star 304)S.
 * [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - 帮助简化Javadoc风格文档编写的xcode插件(Star. 3338)
 * [XAlign](https://github.com/qfish/XAlign) - 一个很棒的常规代码对齐Xcode插件，通过使用自定义对齐模版，可以对齐任何东东(Star 1324).
 * [Cocoapods Xcode Plugin](https://github.com/kattrali/cocoapods-xcode-plugin) - CocoaPods的依赖管理器插件(Star 1391).
 * [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) - 提供imageNamed调用自动补全的Xcode插件(Star 2471).
 * [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode) - 增强色彩开发可视化的Xcode插件(Star 2031).
 * [Backlight-for-XCode](https://github.com/limejelly/Backlight-for-XCode) - 高亮显示当前编辑行的Xcode插件(Star 128)

### Package Manager
 * [Alcatraz](http://alcatraz.io/) - Xcode包管理器.

### Themes
 * [Dracula Theme](https://github.com/zenorocha/dracula-theme) - Xcode深色主题(Star 641)
 * [Xcode themes list](https://github.com/hdoria/xcode-themes) - Xcode颜色主题(Star 566)
 * [Solarized-Dark-for-Xcode](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode/) - Xcode5 Solarized Dark主题(Star 109).

# Swift

### Websites
* [Apple's Swift Blog](https://developer.apple.com/swift/blog/) - Apple官方Swift博客.

### Videos
* [Brian Advent youtube channel](https://www.youtube.com/channel/UCysEngjfeIYapEER9K8aikw/videos) - Swift教程Youtube频道.

### UI
* [JLToast](https://github.com/devxoul/JLToast) - Swift编写的, iOS上Android风格Toast提示器实现(Star 159).
* [SweetAlert](https://github.com/codestergit/SweetAlert-iOS) - Swift编写的iOS动画报警视图控件(Star 382).

# Style Guides
* [NY Times - Objective C Style Guide](https://github.com/NYTimes/objective-c-style-guide) - The New York Times使用的objective-C编码风格指南(Star 3001) 
* [raywenderlich Style Guide](https://github.com/raywenderlich/objective-c-style-guide) - 概述了raywenderlich.com约定的编码风格指南(Star 1270)
* [Github Objective-C Style Guide](https://github.com/github/objective-c-style-guide) - Objective-C项目的风格指南和编码约定(Star 1147)
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796) - objective-c编码规范和最佳实践

# Good Websites

### News, Blogs and Feeds
 * [BGR](http://bgr.com/ios-7/)
 * [iMore](http://www.imore.com/)
 * [Lifehacker](http://lifehacker.com/tag/ios)
 * [iCode Blog](http://www.icodeblog.com/)
 * [NSHipster](http://nshipster.com)
 * [Objc.io](http://www.objc.io)
 * [AsciiWWDC](http://asciiwwdc.com)
 * [Natasha The Robot](http://natashatherobot.com)

### UIKit references
 * [iOS Fonts](http://iosfonts.com/)
 * [UIAppearance list](https://gist.github.com/mattt/5135521)

### Components and Packages
 * [Cocoa Controls](http://www.cocoacontrols.com)
 * [Cocoa Pods](http://cocoapods.org/)

### Forums and discuss lists
 * [iPhone Dev SDK Forum](http://iphonedevsdk.com/)
 * ["iOS" on Stackoverflow](http://stackoverflow.com/questions/tagged/ios)

### Tutorials and Keynotes
 * [AppCoda](http://www.appcoda.com)
 * [Ray Wenderlich](http://www.raywenderlich.com)
 * [Tutorials Point](http://www.tutorialspoint.com/ios/)
 * [Code with Cris](http://codewithchris.com/)
 * [Cocoa with Love](http://www.cocoawithlove.com/)
 * [Cocoa is my Girlfriend](http://www.cimgf.com/)
 * [Code School - Try Objective-C](http://tryobjectivec.codeschool.com/)

### iOS UI Template
 * [App Icon Template](http://appicontemplate.com/ios8)
 * [iOS 8 GUI PSD Template](http://www.teehanlax.com/tools/iphone)
 * [iOS UI Design Kit](http://www.invisionapp.com/tethr)
 * [iOS Design Guidelines](http://iosdesign.ivomynttinen.com/)

### Prototyping
 * [FluidUI](https://www.fluidui.com)
 * [Proto.io](http://proto.io)
 * [Framer](http://framerjs.com/)
 * [Pixate](http://www.pixate.com/)

# Twitter
 * [@objcio](https://twitter.com/objcio)
 * [@nshipster](https://twitter.com/NSHipster)
 * [@CocoaPods](https://twitter.com/CocoaPods)
 * [@CocoaPodsFeed](https://twitter.com/CocoaPodsFeed)
 * [@RubyMotion](https://twitter.com/RubyMotion)

# Books
 * [Programming with Objective-C by Apple](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/ProgrammingWithObjectiveC.pdf)
 * [Object-Oriented Programming with Objective-C by Apple](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/OOP_ObjC/OOP_ObjC.pdf)
 * [The Swift Programming Language by Apple](https://itunes.apple.com/us/book/swift-programming-language/id881256329?mt=11)
 * [Using Swift with Cocoa and Objective C by Apple](https://itunes.apple.com/us/book/using-swift-cocoa-objective/id888894773?mt=11)
 * [iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass, Joe Conway](http://www.bignerdranch.com/we-write/ios-programming.html)
 * [Programming in Objective-C by Stephen G. Kochan](http://www.amazon.com/Programming-Objective-C-6th-Developers-Library/dp/0321967607)
 * [Your First iOS App by Ash Furrow](https://leanpub.com/your-first-ios-app)

# Other Awesome Lists
Other amazingly awesome lists can be found in the     
 * [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.
 * [Open Source apps](https://github.com/dkhamsing/open-source-ios-apps) list of open source ios apps
 * Awesome-swift
   * [@matteocrippa](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources. 
   * [@Wolg](https://github.com/Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software.

# Contributing
[See the guide](https://github.com/vsouza/awesome-ios/blob/master/CONTRIBUTING.md)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/vsouza/awesome-ios/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

