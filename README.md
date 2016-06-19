# Kunkka
本Wordpress主题以[牧风](https://mufeng.me/)大神的Kunkka 1.06为基础改进而来，可以在[我的博客](http://agatelee.cn)看到效果



# ToDo

* 回复中的表情符号没有被替换


# 版本说明

**v1.06**

牧风原版

**v1.08_local**

修改版，改动如`2016-06-17 更新日志`和`2016-06-18 更新日志`

**v1.09_local**

自定义表情支持，评论表情选择


**v1.10_local**

更正了logo分辨率、将代码中的tab替换为4个空格

**v1.11_local**

修改了显示bug，改动如`2016-06-19 更新日志`后面部分




# 更新日志

**2016-06-19**

* 自定义表情支持，评论添加表情选择
* 修改了all.js，扩展了drop-down的适用范围，解决了下列问题：
  * 手机上点击评论表情dropdown无法弹出问题
* 修改了all.js,将mobile-menu的逻辑从touchstart换为click，同时扩展适用范围，解决了下列问题：
  * ipadmini2纵向放置出现了mobile-menu但是无法触发
  * 桌面浏览器缩小窗口出现了mobile-menu但是无法出发
  这些问题都是由于桌面浏览器的判定造成的
* 增加了关于页面的fontawsome逻辑，添加了空onclick，使得IOS移动设备可以触发hover事件，如显示微信二维码


**2016-06-18**

* 关于页面增加了微信二维码，丰富了样式
* 404页面增加了倒计时，修改了样式
* 增加了分类页面


**2016-06-17**

* 本地化
  * 替换了首页logo
  * 替换了默认图片
  * 备案号
* 修改了index.php的显示逻辑，对于置顶的文章显示全文
* 修改了header.php的导航，只保留分类和标签
* 重新设计了404页面
  ![](public/images/404.png)
* 增加了表格样式，原本主题中表格全白（为了导航？），设置了格线及底色以显示内容
* 增加了代码样式，限定code的默认底色以及代码区块大小，代码高亮使用highlight.js
* 增加了友情链接页面
* 增加了关于页面
