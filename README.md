# Awesome iOS

A curated list of awesome iOS frameworks, libraries, tutorials, plugins Xcode, components and much more. 
The list is divided into categories such as Frameworks, Components, Testing and others,  open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/CONTRIBUTING.md).

### Contents
 - [入门指南(Getting Started)](#getting-started)
 - [库和框架(Library and Frameworks)](#libraries-and-frameworks)
     - [缓存(Cache)](#cache)
     - [核心数据(Core Data)](#core-data)
     - [数据库(Database)](#database)
     - [HUD](#hud)
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
 * [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - Drop-in class for displays a translucent HUD with an indicator and/or labels while work is being done in a background thread.
 * [SVProgressHUD](https://github.com/TransitApp/SVProgressHUD) - A clean and lightweight progress HUD for your iOS app.
 * [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD is a lightweight and easy-to-use HUD.

### Images
 * [GPU Image](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing.
 * [UIImage DSP](https://github.com/gdawg/uiimage-dsp) - IOS UIImage processing functions using the vDSP/Accellerate framework for speed.
 * [QR Code Scanner](http://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation
 * [AsyncImageView](https://github.com/nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI.
 * [SDWebImage](https://github.com/rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category

### JSON
 * [JSONKit](https://github.com/johnezang/JSONKit) - Objective-C JSON
 * [TouchJSON](https://github.com/TouchCode/TouchJSON) - A humane JSON Objective-C un-framework.
 * [JSON-Framework](https://github.com/stig/json-framework) -  This framework implements a strict JSON parser and generator in Objective-C.
 * [Mantle](https://github.com/Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch.
 * [Groot](https://github.com/gonzalezreal/Groot) - Convert JSON dictionaries and arrays to and from Core Data managed objects.
 * [KZPropertyMapper](https://github.com/krzysztofzablocki/KZPropertyMapper) - Data mapping and validation with minimal amount of code.
 * [JSONModel](https://github.com/icanzilb/JSONModel) - Magical Data Modelling Framework for JSON. Create rapidly powerful, atomic and smart data model classes.
 * [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift.
 
### Logging
 * [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS
 * [NSLogger](https://github.com/fpillet/NSLogger) - a high perfomance logging utility which displays traces emitted by client applications running on Mac OS X, iOS and Android.

### Maps
 * [Route-me](https://github.com/route-me/route-me) - Open source map library for iOS.
 * [MapBox](https://github.com/mapbox/mapbox-ios-sdk) - Mapbox iOS SDK, an open source alternative to MapKit.

### Networking
 * [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and OS X networking framework.
 * [RestKit](http://restkit.org/) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun.
 * [FSNetworking](https://github.com/foursquare/FSNetworking) - Foursquare iOS networking library
 * [ASIHTTPRequest](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, Mac OS X and iPhone.
 * [Overcoat](https://github.com/gonzalezreal/Overcoat) - Overcoat is a small but powerful library that makes creating REST clients simple and fun.

### Push
 * [Orbiter](https://github.com/mattt/Orbiter) - Push Notification Registration for iOS.
 * [PEM](https://github.com/KrauseFx/PEM) - Tired of manually creating and maintaining your push certification profiles?

### Passbook
 * [passbook](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6+.
 * [Dubai](https://github.com/nomad/dubai) - Generate and Preview Passbook Passes.

### Text
 * [Twitter Text Obj](https://github.com/twitter/twitter-text-objc) - An Objective-C implementation of Twitter's text processing library.
 * [Nimbus](http://nimbuskit.info/) - Nimbus is a toolkit for experienced iOS software designers.

### UI
 * [ActionSheetPicker-3.0](https://github.com/skywinder/ActionSheetPicker-3.0/) - Quickly reproduce the dropdown UIPickerView / ActionSheet functionality on iOS.
 * [FlatUIKit](https://github.com/Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS.
 * [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) - UITextField subclass with floating labels.
 * [SSBouncyButton](https://github.com/StyleShare/SSBouncyButton) - iOS7-style bouncy button UI component.
 * [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) - An elegant messages UI library for iOS.
 * [TSMessages](https://github.com/toursprung/TSMessages) - Show notification views on top of screen such as success, error, warning or messages for iOS.
 * [NZAlertView](https://github.com/NZN/NZAlertView) - Simple and intuitive alert view. Similar to push notification effect.
 * [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell) - UITableViewCell subclass that allows to display swippable buttons with a variety of transitions.
 * [ARAutocompleteTextView](https://github.com/alexruperez/ARAutocompleteTextView) - subclass of UITextView that automatically displays text suggestions in real-time. Perfect for email Textviews
 * [TGCameraViewController](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects.
 * [BWWalkthrough](https://github.com/ariok/BWWalkthrough) - Class that helps you create Walkthroughs pages
 * [ENSwiftSideMenu] (https://github.com/evnaz/ENSwiftSideMenu) - A simple side menu for iOS 7/8 written in Swift.
 * [MDCSwipeToChoose] (https://github.com/modocache/MDCSwipeToChoose) - Swipe to "like" or "dislike" any view, just like Tinder.app. Build a flashcard app, a photo viewer, and more, in minutes, not hours!
 * [UIColor-Hex-Swift] (https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string.


### WebSocket
 * [Socket Rocket](https://github.com/square/SocketRocket) - A conforming Objective-C WebSocket client library.

### Code Quality
 * [KZBootstrap](https://github.com/krzysztofzablocki/KZBootstrap) - Set of scripts and annotations that generate extra compile time errors and warnings on bad code quality.
 * [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beatiful DSL.
 * [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
 
### Analytics
 * [Flurry Analytics](http://www.flurry.com) - Free app Analytics API
 * [Parse Analytics](https://parse.com/products/analytics) - Measure App Usage, track bugs and much more
 
### Payments
 * [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowlege on Backend.
 * [Braintree](https://www.braintreepayments.com) - Free payment processing on your first $50k. Requires Backend.

# Project setup
 * [crafter](https://github.com/krzysztofzablocki/crafter) - CLI that allows you to configure iOS project's template using custom DSL syntax, simple to use and quite powerful.
 * [liftoff](https://github.com/thoughtbot/liftoff) - Another CLI for creating iOS projects.
 * [KZBootstrap](https://github.com/krzysztofzablocki/KZBootstrap) - iOS project bootstrap aimed at high quality coding.
 * [amaro](https://github.com/crushlovely/Amaro) - iOS Boilerplate full of delights.

# Dependency Manager

 * [Cocoa Pods](http://cocoapods.org/) - CocoaPods is the dependency manager for Objective-C projects. It has thousands of libraries and can help you scale your projects elegantly.
 * [Xcode Maven](http://sap-production.github.io/xcode-maven-plugin/site/) - The Xcode Maven Plugin can be used in order to run Xcode builds embedded in a Maven lifecycle.
 * [Gradle](http://openbakery.org/gradle.php) - The gradle xcode plugin can be used to build iOS or Mac OS X Projects using gradle.
 * [Carthage](https://github.com/Carthage/Carthage) - A simple, decentralized dependency manager for Cocoa.

# Testing

### TDD / BDD
 * [Kiwi](https://github.com/kiwi-bdd/Kiwi) - A behavior-driven development library for iOS development.
 * [Specta](https://github.com/specta/specta) - A light-weight TDD / BDD framework for Objective-C & Cocoa.
 * [Quick](https://github.com/Quick/Quick) - A behavior-driven development framework for Swift and Objective-C.

### UI Testing
 * [CrashMonkey](https://github.com/mokemokechicken/CrashMonkey) - Monkey Test Tool For iOS.
 * [appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps.
 * [robotframework-appiumlibrary](https://github.com/jollychang/robotframework-appiumlibrary) - AppiumLibrary is an appium testing library for RobotFramework.
 * [Cucumber](http://cukes.info/) - Behavior driver development for iOS.
 * [Kif](https://github.com/kif-framework/KIF) - An iOS Functional Testing Framework.
 * [Subliminal](https://github.com/inkling/Subliminal) - An understated approach to iOS integration testing.
 * [UIAutomation](https://developer.apple.com/library/ios/documentation/DeveloperTools/Reference/UIAutomationRef/Introduction/Introduction.html) - JavaScript library to write test scripts that exercise your app’s user interface elements while the app runs on a connected device.
 * [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - Test any IOS native, hybrid, or mobile web application using Selenium / WebDriver.
 * [Zucchini](http://www.zucchiniframework.org/) - A visual iOS testing framework that loves your apps.

### Beta Distribution
 * [Crashlytics](https://www.crashlytics.com/) - A crash reporting and beta testing service.
 * [TestFlight Beta Testing](https://developer.apple.com/testflight/) - The beta testing service hosted on iTunes Connect (requires iOS 8 or later).
 * [HockeyApp](http://hockeyapp.net/) - With HockeyApp, you can distribute beta versions of your app, collect live crash reports, get feedback from users, and analyze test coverage.

# Toolchains
 * [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and OS X applications for iPhone, iPad and Mac, all using the Ruby language.

# Rapid Development
 * [KZPlayground](https://github.com/krzysztofzablocki/KZPlayground) - Playgrounds for Objective-C for extremely fast prototyping / learning.
 * [dyci](https://github.com/DyCI/dyci-main) - Code injection tool

# Deployment
 * [fastlane](http://fastlane.tools/) fastlane lets you define and run your deployment pipelines for different environments.
   * [deliver](https://github.com/krausefx/deliver) Deploy screenshots, app metadata and app updates to the App Store using just one command
   * [snapshot](https://github.com/krausefx/snapshot) Automatically create screenshots in all languages on all devices

# SDK
 * [Spotify](https://github.com/spotify/ios-sdk) Spotify iOS SDK
 * [Facebook](https://github.com/facebook/facebook-ios-sdk) Facebook iOS SDK
 * [Google Analytics](https://developers.google.com/analytics/devguides/collection/ios/v3/) Google Analytics SDK for iOS
 * [Paypal iOS SDK](https://github.com/paypal/PayPal-iOS-SDK) The PayPal Mobile SDKs enable native apps to easily accept PayPal and credit card payments.
 * [Pocket](https://github.com/Pocket/Pocket-ObjC-SDK) SDK for saving stuff to Pocket
 * [Tumblr](https://github.com/tumblr/TMTumblrSDK) Library for easily integrating Tumblr data into your iOS or OS X application.
 * [Evernote](https://github.com/evernote/evernote-sdk-ios) Evernote SDK for iOS
 * [Box](https://github.com/box/box-ios-sdk-v2) iOS + OS X SDK for the Box API
 * [OneDrive](https://github.com/liveservices/LiveSDK-for-iOS) Live SDK for iOS
 * [Stripe](https://github.com/stripe/stripe-ios) Stripe bindings for iOS and OS X 
 * [Venmo](https://github.com/venmo/venmo-ios-sdk) Make and accept payments in your iOS app via Venmo
 * [AWS](https://github.com/aws/aws-sdk-ios) Amazon Web Services Mobile SDK for iOS
 * [Zendesk](https://github.com/zendesk/zendesk_sdk_ios) Zendesk Mobile SDK for iOS

# Xcode

### Plugins
 * [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap) - SCXcodeMiniMap is a plugin that adds a source editor MiniMap to Xcode.
 * [Show in Github](https://github.com/larsxschneider/ShowInGitHub) - Xcode plugin to open the GitHub page of the commit of the currently selected line in the editor window.
 * [BBUFullIssueNavigator](https://github.com/neonichu/BBUFullIssueNavigator) - Xcode plugin for showing all issue content in the issue navigator.
 * [BBUDebuggerTuckAway](https://github.com/neonichu/BBUDebuggerTuckAway) - Xcode plugin for auto-hiding the debugger once you start typing in the source code editor.
 * [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander) - SCXcodeSwitchExpander is a small Xcode plugin that expands switch statements by inserting missing cases.
 * [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier.
 * [XAlign](https://github.com/qfish/XAlign) - An amazing Xcode plugin to align regular code. It can align anything by using custom alignment patterns.
 * [Cocoapods Xcode Plugin](https://github.com/kattrali/cocoapods-xcode-plugin) - Dependency management helper for your CocoaPods, right in Xcode.
 * [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.
 * [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode) - Plugin for Xcode to make working with colors more visual.
 * [Backlight-for-XCode](https://github.com/limejelly/Backlight-for-XCode) - Highlights the current editing line in Xcode

### Package Manager
 * [Alcatraz](http://alcatraz.io/) - The package manager for Xcode.

### Themes
 * [Dracula Theme](https://github.com/zenorocha/dracula-theme) - A dark theme for Xcode
 * [Xcode themes list](https://github.com/hdoria/xcode-themes) - Color themes for Xcode.
 * [Solarized-Dark-for-Xcode](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode/) - Solarized Dark Theme for Xcode 5.

# Swift

### Websites
* [Apple's Swift Blog](https://developer.apple.com/swift/blog/) - Offical Swift blog from Apple.

### Videos
* [Brian Advent youtube channel](https://www.youtube.com/channel/UCysEngjfeIYapEER9K8aikw/videos) - Swift tutorials Youtube Channel.

### UI
* [JLToast](https://github.com/devxoul/JLToast) - Toast for iOS with very simple interface. Written in Swift.
* [SweetAlert](https://github.com/codestergit/SweetAlert-iOS) - Live animated Alert View for iOS written in Swift.

# Style Guides
* [NY Times - Objective C Style Guide](https://github.com/NYTimes/objective-c-style-guide) - The Objective-C Style Guide used by The New York Times
* [raywenderlich Style Guide](https://github.com/raywenderlich/objective-c-style-guide) - A style guide that outlines the coding conventions for raywenderlich.com
* [Github Objective-C Style Guide](https://github.com/github/objective-c-style-guide) - Style guide & coding conventions for Objective-C projects
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796) - Gist with coding conventions

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

