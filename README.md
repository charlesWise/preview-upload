前端实现：图片压缩，图片旋转矫正方向，图片预览，图片二进制数据流上传

# 项目中主要插件是：exif.js 和 processImg.js这两个插件是用来实现图片压缩和图片方向纠正的。
 
 processImg.js依赖于exif.js，所以在使用的时候，必须先引入exif.js，然后再引入processImg.js
 
 插件processImg.js和exif.js都是原生js编写的。所以不依赖第三方库，可以直接在任何前端项目中使用。
 
 只需要先将exif.js引入，然后再将processImg.js引入即可。

 exif.js 提供了 JavaScript 读取图像的原始数据的功能扩展，例如：拍照方向、相机设备型号、拍摄时间、ISO 感光度、GPS 地理位置等数据。

 Exif.js 的 github 仓库地址：[https://github.com/exif-js/exif-js/](https://github.com/exif-js/exif-js/)

# 兼容性：
 插件的浏览器兼容性：IE10+，IE10以下的浏览器可能不兼容