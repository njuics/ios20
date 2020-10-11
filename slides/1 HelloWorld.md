---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.jpg')
marp: true
---


# iOS智能应用开发

![bg right:60% 95%](https://docs-assets.developer.apple.com/published/0c6f70c9aa2bc6bc3af552ecdfe73700/110/overview-hero@2x.png)

Hello World


---


# Hello World


Hello, World是指在电脑屏幕显示“Hello, World!”（你好，世界！）字符串的计算机程序。相关的程序通常都是每种电脑编程语言最基本、最简单的程序，也会用作示范一个编程语言如何运作。同时它亦可以用来确认一个编程语言的编译器、程序开发环境及运行环境是否已经安装妥当。


![bg left](https://upload.wikimedia.org/wikipedia/commons/2/21/Hello_World_Brian_Kernighan_1978.jpg)



---

# Xcode

- 安装
  
  - App Store[免费下载](https://apps.apple.com/cn/app/xcode/id497799835?mt=12)


---

# Hello World

年轻人的第一个iOS App

![bg right 60%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld/9.4.1/helloworld.png)


---
##### 1. 启动Xcode

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![width:800px](./images/start-up.png)




---

##### 2. 选择项目模板

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:800px](./images/template.png)




---

##### 3. 填写项目信息

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![width:800px](./images/info.png)



---

##### 4. 选择保存地址

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:800px](./images/save.png)



---

##### 5. 选择模拟器并启动

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![width:800px](./images/simulator.png)




---

##### 6. 添加文字标签

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![width:800px](./images/addlabel.png)




---

##### 7. 选择模拟器并启动

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![width:800px](./images/project.png)




---

##### 8. 修改文字内容

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:800px](./images/changetext.png)




---

##### 9. 再次运行

![bg 30%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld/9.4.1/helloworld.png)


---


# 为Hello World添加互动

![bg 35%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/run.png)

![bg 35%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/alert.png)


---

##### 1. 在界面上添加能引起互动的元素

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:800px](./images/addbutton.png)

---

##### 2. 添加几行代码

在`ViewController.swift`文件中添加一个方法`func`

```swift
@IBAction func showAlert(){
    let alert = UIAlertController(title: "警告", message: "⚠️皇上，您的按钮被点啦！", preferredStyle: .alert)
    alert.addAction(UIAlertAction(title: "朕知道了", style: .default, handler: nil))
    self.present(alert, animated: true, completion: nil)
}
```

---
##### 3. 打开两个编辑器

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/assistanteditor-annotated.png)


---

###### 4. 选择编辑内容


![bg 70%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/selection1-annotated.png)

![bg 70%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/selection2-annotated.png)


---

###### 5. 建立关联
<style>
img {
  display: block;
  margin: 0 auto;
}
</style>

![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/connect-annotated.png)


---

#####  5. 建立关联-再看一遍


<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/ctrldrag.gif)


---

##### 6. 运行

![bg 50%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/run.png)

![bg 50%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/alert.png)







---

#### 看看代码

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:600px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/codeexplain.png)

```swift
@IBAction func showAlert(){
    let alert = UIAlertController(title: "警告", message: "⚠️皇上，您的按钮被点啦！", preferredStyle: .alert)
    alert.addAction(UIAlertAction(title: "朕知道了", style: .default, handler: nil))
    self.present(alert, animated: true, completion: nil)
}
```

---


# Swift.org

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/swiftorg.png)</div>



---

# 命令行工具

```bash
> swift
Welcome to Apple Swift version 5.2.4 (swiftlang-1103.0.32.9 clang-1103.0.32.53).
Type :help for assistance.
  1> print("hello world")
hello world
  2>
```

---


# Playground (Xcode)

<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:800px](https://developer.apple.com/swift/blog/images/NewtonsCradle_2x.png)

---

# 在Xcode中新建Playground

#### 1. 选择新建Playground
<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:700px](./images/createplayground.png)



---

# 在Xcode中新建Playground

#### 2. 选择Playground的类型
<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:650px](./images/template-playground.png)



---

# 在Xcode中新建Playground

#### 3. 选择Playground的储存位置
<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:650px](./images/save-playground.png)



---

# 在Xcode中新建Playground

#### 4. 写一些代码
<style>
img {
  display: block;
  margin: 0 auto;
}
</style>
![width:580px](./images/code-playground.png)



---



![bg right:50% 100%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/GuidedTour.png)
# A Swift Tour

官方指南
https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html

Playground
https://docs.swift.org/swift-book/GuidedTour/GuidedTour.playground.zip

---

# 回顾小结


![bg 70%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/helloworld2.0/9.4.1/explain.png)


---

# 建立关联 Connection

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:600px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/ctrldrag.gif)

这个操作实际上是建立了一个关联关系

---

#### 查看关联


![bg 60%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/connectioninspector-annotated.png)


---

#### 两个部件间的关联关系

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:700px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/connection1.png)


---

#### 调整关联

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:700px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/connection-change.png)

```swift
@IBAction func changeLabel(){}
```


---

#### 操作

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/newconnection.gif)


---

#### 删除多余关联

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/deleteconnection-annotated.png)


---

#### 动画演示一下

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/deleteconnection.gif)


---

#### 新的代码

```swift
@IBAction func changeLabel(){
    print("changeLabel被执行")
}
```

![bg right:50%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/output-annotated.png)


---

#### 第二类关联

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/connection-II.png)


---

#### 再操作


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![width:800px](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/outletconnection.gif)


---

#### 填上名字


```swift
@IBOutlet weak var myLabel: UILabel!
```

```swift
@IBAction func changeLabel(){
    print("changeLabel被执行")
    myLabel.text = "你好！"
}
```

![bg right:50%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/outletdialog.png)


---

# 运行

![bg 40%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/run-hello.gif)

---

# 理解两类关联

- 把Button拖到changeLabel()函数上，让Button上发生的事件跟函数执行关联（一号关联）
- 把Label拖动到代码中生成了一个变量myLabel，这个变量关联（二号关联）到这个Label

![bg right:50% 99%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/IBActionOutlet.png)


---

#### 再改一下

```swift
@IBAction func changeLabel(){
    print("changeLabel被执行")
    myLabel.text = "你好！" + String(arc4random_uniform(10))
}
```



![bg right:50%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/connections/9.4.1/run-random.gif)


---

#### 小结

- App运行，用户看到屏幕上出现一个界面；
- 界面上某些地方用户是可以操作的，比如这个Button;
- 用户触碰这个Button，系统产生事件；
- 这个事件根据你开发App时定义的 一号关联 ，驱动一段代码运行；
- 代码运行中，将一些计算结果或者获得到的内容通过 二号关联 显示到界面上；
- 用户看到界面上发生变化，进行下一次操作，产生下一个事件；
- 新的事件可能又驱动另一段代码执行。如此往复。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;事件驱动的图形化应用程序 ✌️✌️✌️

---

# 真机运行

![bg 30%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/rerun.jpg)


---

##### 1. 注册Apple开发者账号

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/developer.apple-annotated.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/login.png)


---

##### 2. 登陆账号

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/team-annotated.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/addaccount.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/accounts-annotated.png)

---

##### 3. 选择Team

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/team-selection.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/fixagain-annotated.png)

---

##### 4. 选择真机运行

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/realdevice-annotated.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/fixed.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/keychain.png)


---

##### 5. 排除错误

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/cannotlaunch-annotated.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/devicemgr-annotated.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/devapp-annotated.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/trust-annotated.png)

![bg 90%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/confirm.png)

---

##### 6. 再再次运行

![bg 30%](https://cdn.nemoworks.info/swiftplaygrounds.fun/images/makeitreal/9.4.1/rerun.jpg)


---

# 作业

Hello 你的 World