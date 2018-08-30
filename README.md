# Swift4 二维码扫描 支持横竖屏切换

> 网上二维码扫描的轮子实在是太多了，为啥还要自己写呢？实在是因为没有找到合适的，找了十几二十个轮子， swift 、oc的都找了，全都不支持横竖屏切换，所以只能自己造了。
>
> 这是一款使用Swift4编写的二维码扫描器，支持二维码/条形码的扫描，支持横竖屏切换，支持连续扫描，使用超简单，可扩展性强



## 使用


[代码地址：https://github.com/sunflowerseat/SwiftQRCode](https://github.com/sunflowerseat/SwiftQRCode)

先贴一下使用方法，实在太简单，就一个ViewController，根本懒得弄什么pod，直接把SwiftQRCodeVC拷贝过来用就ok了， 记得要给权限 `Privacy - Camera Usage Description`


### 自定义


里面有些属性方便自定义

- scanAnimationDuration  	扫描时长 
	 needSound 			        扫描结束是否需要播放声音 
- scanWidth                                  扫描框宽度 
- scanHeight                                扫描框高度 



扫描线替换：QRCode_ScanLine.png 把这个图片换掉就可以了

扫描框替换：QRCode_ScanBox.png  把这个图片换掉就可以了


## 总结

界面是有点粗制滥造哈~ 不过没关系啊，在initView里面稍微改改就可以变成你想要的了。

播放声音有点问题，不过也不是很重要，所以没花时间去研究了

对代码有什么疑问，可以随时来问 ，秋秋邮箱：970201861@qq.com

