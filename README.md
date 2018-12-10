# uni-template-picture
基于uni-app框架的看图模板，包含单列图、双列图，图片分类，图片轮播、预览、下载，图片分享、收藏，设置桌面背景图等功能。
 
<p align="center">
    <img src="http://img-cdn-qiniu.dcloud.net.cn/uniapp/template/new.png" width="200"/>
    <img src="http://img-cdn-qiniu.dcloud.net.cn/uniapp/template/hot.png" width="200"/>
</p>


## 运行方式

将项目拖入[HBuilderX](http://www.dcloud.io/hbuilderx.html),直接运行即可<br>
在windows选择项目的目录名称，然后拖到项目管理器中，项目管理器就会新增目录名称的项目
### 运行到浏览器
1.  manifest.json中appid为空
<p >
自己的appid，怎么获得？可能通过云端获得，点击后面的按钮
</p>


### 小程序运行

## 发行
### 网站-H5手机版
 1. 发行碰到的问题，static/js/chunk-vendors.2ad41823.js文件不存在
### 
## 使用须知

1. 页面样式主要在common/common.css
2. 数据在页面的methods->getData里获取，替换里面的链接及参数即可
3. 接口返回的字段根据已固定，若替换接口也要替换相应的字段名，页面才能正常渲染
3. 页面的分享需配置自己的appid等信息

