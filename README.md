# uni-app-moments
uni-app朋友圈模版
uniapp初期写的模版, 时间比较久远, 目前不再维护

#### 历次更新说明

##### 1.2.1.20190519
* 修复 H5下上传图片时的`plus is not defined`错误
* 优化 App下编译模式由`template模板模式`改为新的`自定义组件模式`

##### 1.2.0.20190425
* 优化 取消选择图片按钮
* 修复 发布时内容为空时未正确拦截

##### 1.1.0.20190417
* 优化 发送按钮触发位置,现在只有刚好点击到**发送**才触发
* 新增 发布评论和发布'朋友圈'内容为空的验证
* 新增 发布moment图片上传服务端示例

##### 1.0.2.20190322
* 修复 H5下使用本地数据测试时,预览图片总是第一张的bug,将index.post.data.js中的图片路径均改为绝对路径,线上环境中使用网路路径,故不存在此问题

##### 1.0.1.20190305
* 新增 下拉刷新和加载更多
* 修改目录结构,dcloud插件市场下载解压后直接为项目目录,可直接运行;github下载后需将根目录下的uni-app-moments目录拖到HbuilderX中才可直接运行

#### 功能简介

* 点赞
* 评论 + 回复评论
* 图片预览
* 发布页
* 图片上传
* 图片压缩(app端)
* 发布页侧滑返回(app端体验效果更佳)
* 评论和回复时输入框自动定位到当前内容下(导致输入框闪烁,体验不好,待完善,可直接删除adjust函数第一行的return测试)
* 下拉刷新 + 加载更多

#### 使用方法

##### dcloud插件市场
1. 解压下载文件
2. 将项目目录,直接拖到HbuilderX中运行

##### github
1. 下载后需要将根目录下的uni-app-moments目录拖到HbuilderX中才能直接运行

![dir.jpg](https://upload-images.jianshu.io/upload_images/14618365-1b54255c3ec7b157.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 运行截图

![index.jpg](https://upload-images.jianshu.io/upload_images/14618365-379e1915cae8ec46.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/290) 
![comment+like.jpg](https://upload-images.jianshu.io/upload_images/14618365-cdc9299f7697c836.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/290)
![upload.png](https://upload-images.jianshu.io/upload_images/14618365-fef776173d49f68d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/290) 
![showimg.jpg](https://upload-images.jianshu.io/upload_images/14618365-ce9298ae26e24851.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/290)
![showimg02.jpg](https://upload-images.jianshu.io/upload_images/14618365-dd57f7f53446164a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/290)



>如果觉得对您有用,烦请给个好评或者star