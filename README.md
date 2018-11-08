# <div align=center>日常积累所看到的面试题集锦</div>
### <div align=center>各种精选面试题</div>

#####  <div align=center> 小编会不定时更新哦，麻烦给一个赞哈。</div>
#####  <div align=center> 编辑积累学习都不容易，希望大家相互鼓励。</div>
<br>
<br>

| 目录名称 | 面试题内容 | 编辑时间 | 地址 |
| --- | --- | --- | --- |
| iOS面试准备之思维导图 | 1.UI视图相关面试问题<br><br>2.Objective-C语言特性相关面试问题<br><br>3.Runtime相关面试问题<br><br>4.内存管理相关面试问题<br><br>5.Block相关面试问题<br><br>6.多线程相关面试问题<br><br>7.RunLoop相关面试问题<br><br>8.网络相关面试问题<br><br>9.设计模式相关面试问题<br><br>10.架构/框架相关面试问题<br><br>1.算法相关面试问题<br><br>12.第三方库相关面试问题 | 2018.05.05 | [前往查看详情](https://www.jianshu.com/p/a2c85b9f6a25)|
|有感而写（面试题总结一）| 1.为什么说Objective-C是一门动态的语言？<br><br>2.讲一下MVC和MVVM，MVP？<br><br>3.@property 后面可以有哪些修饰符？<br><br>4.copy和mutableCopy,深复制和浅复制？<br><br>5.什么情况使用 weak 关键字，相比 assign 有什么不同？<br><br>6.block为什么要用copy修饰？<br><br>7.这个写法会出什么问题： @property (copy) NSMutableArray *array;<br><br>8.如何让自己的类用 copy 修饰符？如何重写带 copy 关键字的 setter？<br><br>9.@property 的本质是什么？ivar、getter、setter 是如何生成并添加到这个类中的。<br><br>10.@protocol 和 category 中如何使用 @property？<br><br>11.Runtime 如何实现 weak 属性？<br><br>12.@synthesize和@dynamic分别有什么作用？<br><br>13.用@property声明的NSString（或NSArray，NSDictionary）经常使用copy关键字，为什么？如果改用strong关键字，可能造成什么问题？<br><br>14.@synthesize合成实例变量的规则是什么？假如property名为foo，存在一个名为_foo的实例变量，那么还会自动合成新变量么？ | 2018.03.15 |[前往查看答案](https://juejin.im/post/5a961b146fb9a0635c04a788)|
|iOS面试题 Published by iOS收藏家|1.设计模式是什么？ 你知道哪些设计模式，并简要叙述？<br><br>2.MVC 和 MVVM 的区别 <br><br>3.#import跟 #include 有什么区别，@class呢，#import<> 跟 #import””有什么区别？<br><br>4.frame 和 bounds 有什么不同？<br><br>5.Objective-C的类可以多重继承么？可以实现多个接口么？Category是什么？重写一个类的方式用继承好还是分类好？为什么？<br><br>6.@property 的本质是什么？ivar、getter、setter 是如何生成并添加到这个类中的<br><br>7.@property中有哪些属性关键字？/ @property 后面可以有哪些修饰符？<br><br>8.属性关键字 readwrite，readonly，assign，retain，copy，nonatomic 各是什么作用，在那种情况下用？<br><br>9.什么情况使用 weak 关键字，相比 assign 有什么不同？<br><br>10.怎么用 copy 关键字？<br><br>11.用@property声明的 NSString / NSArray / NSDictionary 经常使用 copy 关键字，为什么？如果改用strong关键字，可能造成什么问题？<br><br>12.浅拷贝和深拷贝的区别？<br><br>13.系统对象的 copy 与 mutableCopy 方法<br><br>14.这个写法会出什么问题：@property (nonatomic, copy) NSMutableArray *arr;<br><br>15.如何让自己的类用 copy 修饰符？如何重写带 copy 关键字的 setter？<br><br>16.写一个 setter 方法用于完成 @property (nonatomic, retain) NSString *name，写一个 setter 方法用于完成 @property (nonatomic, copy) NSString *name<br><br>17.@synthesize 和 @dynamic 分别有什么作用？<br><br>18.常见的 Objective-C 的数据类型有那些，和C的基本数据类型有什么区别？如：NSInteger和int<br><br>19.id 声明的对象有什么特性？<br><br>20.Objective-C 如何对内存管理的，说说你的看法和解决方法？<br><br>21.Objective-C 中创建线程的方法是什么？如果在主线程中执行代码，方法是什么？如果想延时执行代码、方法又是什么？<br><br>22.Category（类别）、 Extension（扩展）和继承的区别<br><br>23.我们说的OC是动态运行时语言是什么意思？<br><br>24.为什么我们常见的delegate属性都用是week而不是retain/strong？<br><br>25.什么时候用delete，什么时候用Notification？<br><br>26.什么是 KVO 和 KVC？<br><br>27.KVC的底层实现？<br><br>28.KVO的底层实现？<br><br>29.ViewController生命周期<br><br>30.方法和选择器有何不同？<br><br>31.你是否接触过OC中的反射机制？简单聊一下概念和使用<br><br>32.调用方法有两种方式：<br><br>33.如何对iOS设备进行性能测试？<br><br>34.开发项目时你是怎么检查内存泄露？<br><br>35.什么是懒加载？<br><br>36.类变量的 @public，@protected，@private，@package 声明各有什么含义？<br><br>37.什么是谓词？<br><br>38.isa指针问题<br><br>39.如何访问并修改一个类的私有属性？<br><br>40.一个objc对象的isa的指针指向什么？有什么作用？<br><br>41.下面的代码输出什么？<br><br>42.写一个完整的代理，包括声明、实现 <br><br>43.isKindOfClass、isMemberOfClass、selector作用分别是什么<br><br>44.delegate 和 notification 的区别<br><br>45.什么是block？<br><br>46.block反向传值<br><br>47.block的注意点<br><br>48.BAD_ACCESS在什么情况下出现？<br><br>49.lldb（gdb）常用的控制台调试命令？<br><br>50.你一般是怎么用Instruments的？<br><br>51.iOS中常用的数据存储方式有哪些？<br><br>52.iOS的沙盒目录结构是怎样的？<br><br>53.iOS多线程技术有哪几种方式？<br><br>54.GCD 与 NSOperation 的区别<br><br>55.写出使用GCD方式从子线程回到主线程的方法代码<br><br>56.如何用GCD同步若干个异步调用？（如根据若干个url异步加载多张图片，然后在都下载完成后合成一张整图）<br><br>57.dispatch_barrier_async（栅栏函数）的作用是什么？<br><br>58.以下代码运行结果如何？<br><br>59.什么是 RunLoop<br><br>60.什么是 Runtime<br><br>61.Runtime实现的机制是什么，怎么用，一般用于干嘛？<br><br>62.什么是 Method Swizzle（黑魔法），什么情况下会使用？<br><br>63._objc_msgForward 函数是做什么的，直接调用它将会发生什么？<br><br>64.什么是 TCP / UDP ?<br><br>65.通信底层原理（OSI七层模型）<br><br>66.介绍一下XMPP？<br><br>67.OC中创建线程的方法是什么？如果在主线程中执行代码，方法是什么？<br><br>68.tableView的重用机制？<br><br>69.用伪代码写一个线程安全的单例模式<br><br>70.如何实现视图的变形?<br><br>71.在手势对象基础类UIGestureRecognizer的常用子类手势类型中哪两个手势发生后，响应只会执行一次？<br><br>72.字符串常用方法<br><br>73.如何高性能的给 UIImageView 加个圆角?<br><br>74.你是怎么封装一个view的<br><br>75.HTTP协议中 POST 方法和 GET 方法有那些区别?<br><br>76.请简单的介绍下APNS发送系统消息的机制<br><br>未完待续... |2018.8.27|[前往查看答案](http://yipingmi.top/ios面试题/)|
| iOS 阿里三面 面试题整理 | 1.dSYM你是如何分析的？<br><br>2.多线程有哪几种？你更倾向于哪一种？<br><br>3.单例弊端？ <br><br>4.如何把异步线程转换成同步任务进行单元测试？<br><br>5.介绍下App启动的完成过程？<br><br>6.比如App启动过慢，你可能想到的因素有哪些？<br><br>7.0x8badf00d表示是什么？<br><br>8.怎么防止反编译？<br><br>9.说说你遇到到的技术难点？<br><br>10.说说你了解的第三方原理或底层知识？| 2018.1.2 | [前往查看详情](https://juejin.im/post/5a31e6846fb9a044fd11c6c5)|
| iOS面试题，面试答这么多就可以了 | 1.面向对象设计原则<br><br>2.iOS应用导航模式有哪些<br><br>3.iOS持久化方式有哪些<br><br>4.NSClassFromString加载静态库中的类什么情况是nil<br><br>5.id和NSObject的区别<br><br>6.简单描述一下Runtime<br><br>7.Runtime给类添加属性、成员变量<br><br>8.KVO原理<br><br>9.Property修饰符<br><br>10.程序内存分区<br><br>11.extern的作用<br><br>12.指针函数/函数指针/Block<br><br>13.__weak、__strong、__block理解<br><br>14.事件传递链/事件响应链<br><br>15.简述RunLoop<br><br>16.NSTimer原理<br><br>17.简述GCD<br><br>18.自动释放池<br><br>19.iOS中的定时器<br><br>20.UIView/UILayer关系<br><br>21.简述你了解的锁<br><br>22.ISO七层、TCP/IP四层协议<br><br>23.什么是ARC<br><br>24.iOS类和结构体有什么区别<br><br>25.iOS通知和协议的区别<br><br>26.iOS内存使用注意事项和优化<br><br>27.ViewController完整生命周期<br><br>28.frame和bounds区别，origin和anchorPoint的区别<br><br>29.@synthesize和@dynamic的作用<br><br>30.SDWebImage作用<br><br>未完待续... | 2018.4.11 | [前往查看详情](https://www.jianshu.com/p/f8c7eb0c2778)|
