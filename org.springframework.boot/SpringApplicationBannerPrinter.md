这个类提供了打印应用banner的功能。
涉及到以下几个类：
* Banner
* ImageBanner
* ResourceBanner
* SpringBootBanner
* Banners
* PrintedBanner

涉及到的设计模式：
* 组合模式
  ImageBanner,ResourceBanner,SpringBootBanner为叶子类，Banners为容器类
* 装饰器模式
  PrintedBanner为装饰器类. ImageBanner,ResourceBanner,SpringBootBanner,Banners为具体被装饰类.