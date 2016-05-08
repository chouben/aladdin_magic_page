# aladdin_magic_page

可自定义网站页面模板，目前提供图片，商品，魔法页面以及链接（首页，分类页，购物车，个人中心，我的订单）页面元素的自定义编辑，后续可扩展到商家自定义编辑商品页，店铺页以及CMS内容管理。

## 部署方式

###java tomcat 直接拉取源码至webroot目录下

###php Nginx 直接拉取源码至www可执行目录下

##接口说明

###http restful数据接口
数据接口由aladdin_magic_service微服务提供 http restful接口（便于编程，不需要同时启动微服务和gateway），或者也可以根据情况由gateway网关发布http restful接口

###图片接口
使用七牛图片js上传接口，有cdn加速，图片裁剪，图片压缩等特性
