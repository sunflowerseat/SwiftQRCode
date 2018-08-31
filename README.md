# Swift4 二维码扫描 支持横竖屏切换

> 网上二维码扫描的轮子实在是太多了，为啥还要自己写呢？实在是因为没有找到合适的，找了十几二十个轮子， swift 、oc的都找了，全都不支持横竖屏切换，所以只能自己造了。
>
> 这是一款使用Swift4编写的二维码扫描器，支持二维码/条形码的扫描，支持横竖屏切换，支持连续扫描，可识别框内，使用超简单，可扩展性强，很适合需要高度自定义小伙小姑凉们。

因为不太喜欢storyBoard、xib那一套，所以界面是纯手写的，所以很方便移植哈~

## 使用

[代码地址：https://github.com/sunflowerseat/SwiftQRCode](https://github.com/sunflowerseat/SwiftQRCode)

先贴一下使用方法，实在太简单，就一个ViewController，根本懒得弄什么pod，直接把SwiftQRCodeVC拷贝过来用就ok了， 记得要给权限 `Privacy - Camera Usage Description`

备注：声音文件需要右键点击项目名称，add Files to "项目名称"，acc文件是无效的

扫描完成后，在`func qrCodeCallBack(_ codeString : String?)`方法中写回调 ，默认是连续扫描的

### 自定义

里面有些属性方便自定义

| 属性名称              | 属性含义                 |
| --------------------- | ------------------------ |
| scanAnimationDuration | 扫描时长                 |
| needSound             | 扫描结束是否需要播放声音 |
| scanWidth             | 扫描框宽度               |
| scanHeight            | 扫描框高度               |
| isRecoScanSize        | 是否仅识别框内           |
| scanBoxImagePath      | 扫描框图片               |
| scanLineImagePath     | 扫描线图片               |
| soundFilePath         | 声音文件                 |


## 总结

界面是有点粗制滥造哈~ 不过没关系啊，在initView里面稍微改改就可以变成你想要的了。

对代码有什么疑问，可以随时来问 ，秋秋邮箱：970201861@qq.com
