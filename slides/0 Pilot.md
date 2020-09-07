---
theme: gaia
_class: lead
paginate: false
backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.jpg')
marp: true
---


<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![bg right:50% 90%](https://docs-assets.developer.apple.com/published/0c6f70c9aa2bc6bc3af552ecdfe73700/110/overview-hero@2x.png)
# iOS智能应用开发

---

# iPhone：2007 - 

![bg](https://www.bankmycell.com/blog/wp-content/uploads/2019/06/post-iphone-evolution.png)

---

![bg left:50% 100%](https://training.apple.com/content/dam/appletraining/us/en/2020/section-image/IOS%2013_V2.png)

# iOS


iOS（iPadOS）是一个苹果公司开发的运行于iPhone、iPad和iPod Touch等移动设备上的操作系统

当前最新版本 iOS 13 

![w:100px](https://km.support.apple.com/kb/image.jsp?productid=PP144&size=240x240)

---

# iOS App

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/appstore.png)


---

# 基于Swift语言的iOS应用开发
<br>
<br>

##  Swift语言
## 基于Swift的iOS应用开发
## iOS高级应用开发技术

---

# 基于Swift语言的iOS应用开发
<br>
<br>

## -> Swift语言
## 基于Swift的iOS应用开发
## iOS高级应用开发技术


---

# 一切从 Swift 开始

![bg right:45% 50%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/swift.png)
- Swift是Apple公司2014年推出一个用以应用开发的全新语言
- 其目标是成为Apple各个平台上应用的主要开发语言
- 简洁是其主要设计目标之一，开发人员可以用更简短更清晰的代码完成同样的功能

---

# Swift优势


- Swift 是由 Chris Lattner 在苹果工作时创建的。目前，Chris Lattner 在 Google Brain 工作（全球最先进的人工智能研究团队之一）。
- Swift 非常靠近硬件，Swift 与硬件之间没有其他用 C 写的附加层。Swift 的数值计算速度与 C 一样快，还没有内存安全的问题，而且更容易学习。Swift 背后的 LLVM 编译器功能非常强大，并且拥有非常高效的优化功能，可以确保代码快速地运行。
- 因为 Swift 可以很好地与 Python 语言结合。你只需在 Swift 中导入 Python 库，就可以放心使用了。与此同时，你还可以将 C 和 C++ 库导入到 Swift 中。

---

# Swift for TensorFlow

![bg right:45% 90%](https://www.tensorflow.org/site-assets/images/marketing/learn/learn-swift-hero.svg)

- Swift for TensorFlow 是深度学习和可微分计算的新一代系统。
- 通过直接与通用编程语言集成，Swift for TensorFlow 能够以前所未有的方式表达更强大的算法。


---

# Swift.org



![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/swiftorg.png)



---

# Swift Playgrounds



![width:800px](https://www.apple.com.cn/swift/playgrounds/images/overview/real_swift_large_2x.png)

---

# 官方教材

- 《人人能编程：解谜闯关》
  -  [学生指南](https://www.apple.com.cn/105/media/cn/education/everyone-can-code/2019/1d77a2fe_0701_4683_a84b_2a0a86ae5950/puzzles/everyone-can-code-puzzles.ibooks) [教师指南](https://www.apple.com.cn/105/media/cn/education/everyone-can-code/2019/1d77a2fe_0701_4683_a84b_2a0a86ae5950/puzzles-teacher/everyone-can-code-puzzles-teacher-guide.ibooks)

- 《人人能编程：探险闯关》
  - 即将推出


![bg right 80%](https://www.apple.com.cn/education/k12/teaching-code/images/ecc_puzzles__ctl9jhsdcvsm_large_2x.png)

![bg right 80%](https://www.apple.com.cn/education/k12/teaching-code/images/ecc_adventures__bpf9yy7pe1yu_large_2x.png)

---

# Playground (Xcode)

![width:800px](https://developer.apple.com/swift/blog/images/NewtonsCradle_2x.png)


---


![bg right:50% 100%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/GuidedTour.png)
# A Swift Tour

官方指南
https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html

Playground
https://docs.swift.org/swift-book/GuidedTour/GuidedTour.playground.zip

---

# 基于Swift语言的iOS应用开发
<br>
<br>

## Swift语言
## -> 基于Swift的iOS应用开发
## iOS高级应用开发技术


---

# 基于Swift的iOS应用开发

![bg 50%](https://docs-assets.developer.apple.com/published/0c6f70c9aa2bc6bc3af552ecdfe73700/110/overview-hero@2x.png)

---


# 开发工具包

![bg right:40% 80%](https://images2015.cnblogs.com/blog/800567/201510/800567-20151028110802966-1641019918.png)


- 应用开发使用iOS开发工具包
- 开发工具包（SDK）包含开发、安装、运行和测试iOS操作系统之上的应用软件所需的工具和接口

  - 工具: Xcode集成开发环境、 模拟器和开发文档等
  - 接口:  供App调用的程序库和资源，称之为框架（Frameworks）

---


# 框架概览


![bg right:82% ](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/Cocoa_iOS_3.0_cheatsheet.png)

---

# Frameworks

![bg right:50% 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/frameworks.jpg)


整个iOS系统的上百个Frameworks被划分为多层。

下层包含基本服务和技术。高层次的层建立在较低的层，并提供更复杂的服务和技术。

---

## Cocoa Touch层框架

- 构造iOS应用的核心框架
  - Address Book UI Framework
  - Event Kit UI Framework
  - Game Kit Framework
  - Map Kit Framework
  - Message UI Framework
  - Twitter Framework
  - **UIKit Framework**
……

---

## UIKit 框架

- 其中UIKit 框架(UIKit.framework) 提供了开发图形化事件驱动iOS App的基础设施，包括

  - 基本应用管理/用户界面管理
  - 视图控制器和视图
  - 触摸和运动事件
  - 多任务、打印、通知等机制
  - 动画效果、内容分享等
  ……

---

## Media 层框架

- 包含了绘图、音频、视频处理技术的实现，用以实现iOS应用中的多媒体体验
  - Assets Library Framework/AV Foundation Framework
  - Core Audio/Core Graphics/Core Image/Core Text/Core Video Framework
  - Image I/O Framework
  - Media Player Framework
  - OpenGL ES Framework
  - Quartz Core Framework
……

---

## Core Services 层框架

- 所有App都使用的基础系统服务
  - Address Book Framework
  - Core Data Framework
  - Core Foundation Framework
  - Core Location Framework
  - Core Media Framework
  - Core Telephony Framework
  - **Foundation Framework**
……

---

## Foundation 框架

- Foundation framework (Foundation.framework) 提供了 Core Foundation框架中大部分功能特性的（Swift）封装
  - Collection data types (arrays, sets, and so on)
  - Bundles/String management
  - Date and time management
  - Preferences management
  - URL and stream manipulation
  - Threads and run loops
  - Regular expression matching
……

---

## Core OS 层框架

- 以上其他各项技术（框架）的实现基础
  - Accelerate Framework
  - Core Bluetooth
  - External Accessory Framework
  - Security Framework
  - System
    - Threading/Networking/File-system access/Standard I/O/Bonjour and DNS services/Locale information/Memory allocation/Math computations

---

# 核心框架

初级阶段的开发所涉及iOS系统功能基本全部集中与**UIKit**和**Foundation**两个框架之上。

![bg right:60% 60%](https://cdn.tutsplus.com/mobile/uploads/legacy/Exploring-the-iOS-SDK/figure-01.png) 

---

![bg right:50% 60% ](https://help.apple.com/xcode/mac/11.4/en.lproj/GlobalArt/AppLanding.png)


# Xcode

- 安装
  
  - App Store[免费下载](https://apps.apple.com/cn/app/xcode/id497799835?mt=12)

- 文档

  - [Xcode Overview](https://developer.apple.com/library/archive/documentation/ToolsLanguages/Conceptual/Xcode_Overview/index.html)

  - [Xcode Help](https://help.apple.com/xcode/mac/11.4/)



---

# 官方教材


![bg right 80%](https://www.apple.com.cn/education/k12/teaching-code/images/intro_app_dev_swift__c26eyz1rl526_large_2x.png)

![bg right 80%](https://www.apple.com.cn/education/k12/teaching-code/images/app_dev_with_swift__cxb2d60ibje6_large_2x.png)



- 《使用 Swift 开发 App 入门课程》
  - [学生指南](https://www.apple.com.cn/105/media/cn/education/everyone-can-code/2017/bb05cf6f_6591_4502_ba4a_e84e14c35c01/download-swift/intro-to-app-development-with-swift.ibooks) [教师指南](https://www.apple.com.cn/105/media/cn/education/everyone-can-code/2017/bb05cf6f_6591_4502_ba4a_e84e14c35c01/download-swift-teacher-guide/intro-to-app-development-with-swift-teacher-guide.ibooks)
- 《使用 Swift 开发 App》
  - [学生指南](https://www.apple.com.cn/105/media/cn/education/teaching-code/2019/8cd5ecd1_53c8_4e57_b4ea_bd16a261de90/app-dev-with-swift/app-development-with-swift.ibooks) [教师指南](https://www.apple.com.cn/105/media/cn/education/teaching-code/2018/a9d3dcdc_780a_4f43_98bc_5d255cc7BB3E/app-dev-with-swift-teacher/app-development-with-swift-teacher-guide.ibooks)

---


# Apple 官方认证

<br>

![width:400px](https://certiport.pearsonvue.com/Certifications/Apple/App-Dev-With-Swift/Exam-Logos/Badge-3x.png)


---

# Stanford开放课程

https://www.youtube.com/playlist?list=PLpGHT1n4-mAtTj9oywMWoBx0dCGd51_yG

![bg right:50%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/stanford.png)

---

# 基于Swift语言的iOS应用开发
<br>
<br>

## Swift语言
## 基于Swift的iOS应用开发
## -> iOS高级应用开发技术

---


# iOS高级应用开发技术


![bg 80%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/iostech.png)

---


# iOS 游戏开发

###  SpriteKit
###  SceneKit
  

![bg right:50%](http://www.veprof.com/images/scenekit.jpg)

---


![bg](https://www.technologizer.com/wp-content/uploads/2014/06/flappybird.gif)

![bg](https://koenig-media.raywenderlich.com/uploads/2016/03/Thumb.gif)

<!-- ![bg 100%](https://img-blog.csdn.net/20160808172021035) -->

---

# iOS 机器学习 Core ML

![bg  50%](https://developer.apple.com/assets/elements/icons/core-ml/core-ml-128x128_2x.png)

![bg  100%](https://docs-assets.developer.apple.com/published/65b8e13531/e3663268-5db4-42c9-a7f0-2114920a9f1f.png)


---

# 模型训练（迁移学习）

![bg 80%](https://docs-assets.developer.apple.com/published/e6ad1efd6a/d926fc62-3dea-4447-86fc-920d4d6c4781.png)
![bg 80% fit](https://docs-assets.developer.apple.com/published/efbf968cc0/0edb3e43-a85c-41d0-9156-b0ee0b7b1d37.png)


---

# 智能应用开发

![width:900px](https://www.appcoda.com/wp-content/uploads/2017/06/coreml-failed-case.jpg)


---

![bg fit](https://github.com/tucan9389/TextDetection-CoreML/raw/master/resource/TextDetection-CoreML_DEMO001.gif)
![bg fit](https://github.com/yulingtianxia/Core-ML-Sample/raw/master/coreml.gif)
![bg fit](https://user-images.githubusercontent.com/37643248/69563016-acdf3400-0ff3-11ea-8cd0-12df4a86e104.gif)

---

# 增强现实 ARKit



![bg 50%](https://upload.wikimedia.org/wikipedia/commons/2/21/ARKit.png)

![bg fit](https://mrmad.com.tw/wp-content/uploads/2017/11/apple-park-3-2.jpeg)


---


![bg fit](https://camo.githubusercontent.com/8a706d86c3ec995c60111dddb09344c3c94f107f/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f77656261707030312d3134393630302e61707073706f742e636f6d2f6769746875622f776f6c662e676966)
![bg fit](https://github.com/NovatecConsulting/FaceRecognition-in-ARKit/raw/master/demo.gif)
![bg fit](https://github.com/ProjectDent/ARKit-CoreLocation/raw/master/giphy-2.gif)

---


![bg 40%](https://dealercenterportal.blob.core.windows.net/websitemedia/2017/07/dc-pthankyou-59705aa1ab032.png)