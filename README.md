# androidx
#### AndroidX简介
[查看官网对AndroidX的介绍](https://developer.android.com/jetpack/androidx/)
AndroidX是Android团队用于在Jetpack中开发，测试，打包，发布和发布库的开源项目，AndroidX是对原始Android Support Library的重大改进。与支持库一样，AndroidX与Android操作系统分开提供，并提供跨Android版本的向后兼容性。由于在后续版本中，会逐步放弃对support 的升级和维护，所以，今后在出正式版后必须迁移到 androidX.

简单地说就是新的库可以在不同的Android版本上使用。比如之前我们如果使用support为27.1.1的相关依赖库时。可能需要所有相关的support 库都为27.1.1。如果其中有bug的话，可能需要所有的都去升级，存在一个绑定关系，而且正式版的发布周期也很长。
通过AndroidX，我们可以看到实时实现的特性和bug修复。升级个别依赖，不需要对使用的所有其他库进行更新。这就和我们使用Github上的开源库一样的，出了问题，我们可以提出bug和意见。作者修复后，发布新版本，我们就可以直接替换使用了。更加的透明便捷。

[AndroidX了解一下](https://blog.csdn.net/qq_17766199/article/details/81433706)

[Android:你好,androidX！再见,android.support](https://www.jianshu.com/p/41de8689615d)

[AndroidX 官网 maven表](https://dl.google.com/dl/android/maven2/index.html)


