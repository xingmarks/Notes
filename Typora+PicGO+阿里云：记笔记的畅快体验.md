---
typora-root-url: ./img
---

Typora+PicGO+阿里云：记笔记的畅快体验

最开始的笔记软件是印象笔记，个人不太喜欢印象笔记的Markdown体验。后来接触到Typora简单清爽，如果只作为本地编辑器的话，无需使用图床工具。最近想在论坛上发发文章当做自己的笔记本，这时搭配PicGo免去管理本地图片文件的烦恼。

## 1、软件安装

### 方式一：点一点直达链接📍

- [Typora]: https://www.typora.io/

- [PicGo]: https://github.com/Molunerfinn/PicGo/releases

- [阿里云]: https://www.aliyun.com

### 方式二：HomeBrew安装简单快捷

- Typora

  ![image-20210126223205889](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210127223602.png)

- PicGo

  ![image-20210126223404312](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126223404.png)

## 2、配置

- 阿里云

  1.开通阿里云对象存储OSS资源包

  ​	现在可以免费试用一个月

  ![image-20210126225627435](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126225627.png)

  ​	无活动时可以选择购买（半年继续4.98），选择对象存储

  ![image-20210126224625374](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126224625.png)

  ​	选择折扣套餐

  ​	![image-20210126224911409](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126224911.png)

  ​	选择配置购买

  ![image-20210126225105548](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126225105.png)

  2.创建Bucket

  ​	在管理后台点击创建Bucket

  ![image-20210126230425190](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126230425.png)

  ​	输入自己的名称，读写权限选择【公共读】**（这个名称在PicGo的设置中要用到）**<img src="https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126230642.png" alt="image-20210126230642774" style="zoom: 50%;" />

  ​	点击概览选项，记录下Endpoint（地域节点）中红框内的oss-cn-beijing，**（这个节点名称在PicGo的设置中要用到）**

  ​	![image-20210126234609148](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126234609.png)

  ​	新建图片存放目录**（这个目录在PicGo的设置中要用到）**

  ​	![image-20210126234944469](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126234944.png)

  

  3.创建子用户

  ​	将鼠标放在个人头像上，选择AccessKey管理

  <img src="https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126231114.png" alt="image-20210126231114698" style="zoom:67%;" />

  ​	名称随便写，选择编程访问

  ​	![image-20210126231458761](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126231458.png)

  添加权限

  ![image-20210126231646603](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126231646.png)

  ​	用户信息**（这个AccessKeyID和AccessKey Secret在PicGo的设置中要用到）**

  ![image-20210126232037729](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126232037.png)

- PicGo配置

  ![image-20210126233902213](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126233902.png)

- Typora集成PicGo

  在Typora的偏好设置中进行配置。

  ![image-20210126224156906](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126235242.png)

  点击验证图片上传选项，提示成功上传图片并获得新的URL

  ![image-20210126235408178](https://colaimg.oss-cn-beijing.aliyuncs.com/img/20210126235408.png)



大功告成，在Typora中粘贴图片时，自动上传到阿里云，生成适用于Markdown的URL

