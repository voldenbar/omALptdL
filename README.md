# 前言

随着移动互联网的普及，校园内的二手交易需求日益增长。为了方便大学生进行二手物品的买卖，我们基于微信小程序开发了一套校园二手交易平台。本项目使用Java语言，结合Spring、Spring MVC、MyBatis等主流框架，前端采用JS、Vue、CSS3和Uniapp技术，数据库采用MySQL。以下是对本项目的详细介绍。

# 内容介绍

本项目主要包括以下功能模块：用户模块、商品模块、订单模块、消息模块和搜索模块。用户模块负责实现用户的注册、登录、修改资料等功能；商品模块负责实现商品的上架、下架、编辑、删除等功能；订单模块负责实现订单的创建、支付、取消、评价等功能；消息模块负责实现用户之间的互动沟通；搜索模块为用户提供商品检索功能。

通过本项目，用户可以方便地在微信小程序上浏览、搜索、购买二手商品，同时支持发布商品、管理订单等操作。此外，我们还关注用户体验，优化界面设计，使平台更加易用。

# 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis，微信小程序
- 前端技术：JS、Vue、CSS3，Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是商品模块中的一个核心代码片段，用于查询商品列表：

```java
// ProductMapper.xml
<select id="selectProductList" resultType="Product">
    SELECT
        id,
        user_id AS userId,
        title,
        price,
        status,
        create_time AS createTime
    FROM
        product
    WHERE
        status = #{status}
    ORDER BY
        create_time DESC
    LIMIT #{pageNo}, #{pageSize}
</select>
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/326158/31/19748/80048/68c57b23F1b1067e3/8018f9e9c75d882b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/350207/13/2999/12985/68c57afaFa02b10d8/63ba0092ace3a7d7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345310/20/3115/25724/68c57afbF771beb87/d14e935bf3cae848.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/337397/3/10468/19543/68c57afbF7ce41685/8f431dc07b5dd3c3.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328772/21/19469/14460/68c57afbF16fe0f9b/05b18100890756b4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/331687/26/12926/12791/68c57afcFf78af36d/8b009b5d8318c086.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327628/19/19553/24294/68c57afcF52749ddc/5819d8e6a199942c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/328051/11/19582/18143/68c57afcFab9a9638/ce89433db939aed5.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/333051/30/12857/11346/68c57afdF9d50dd91/9baf9a1b7b5528cd.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/347050/17/2861/25671/68c57afdF843e0269/d548b04344c0b8cf.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
