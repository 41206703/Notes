# django

## 基础

### 请求

- **django中的Httprequest的属性**：
- ![image-20211029160022708](https://i.loli.net/2021/10/29/rVR8jy5PvOHUqGh.png)

- ![image-20211029160613819](https://i.loli.net/2021/10/29/PYilzFT2ZA48s5y.png)

### 响应

![image-20211029161125138](https://i.loli.net/2021/10/29/pCPELS2UkxhQ8oA.png)

- ![image-20211029161431048](https://i.loli.net/2021/10/29/irGHS8241RdDsmn.png)





## MTC模型

### 概念

- ![image-20211029162257658](https://i.loli.net/2021/10/29/OnCWDl7EQ1tILqB.png)

### 模板

- ![image-20211029162843030](https://i.loli.net/2021/10/29/su8SK5bypTr61lH.png)
- ==使用方案二更常见==：
- ![image-20211029163056045](https://i.loli.net/2021/10/29/Jd3RYXgi2MQUNh9.png)
- locals（）方法会自动封装字典
- ![image-20211029164119975](https://i.loli.net/2021/10/29/43MmDlec2Cpgs5G.png)

#### 过滤器

![image-20211029164904457](https://i.loli.net/2021/10/29/BiDqhcsSb5gr1jn.png)

### url反向解析

- 



## 静态文件

- static





# 应用

## 分布式路由

- ![image-20211030093117209](https://i.loli.net/2021/10/30/KRSprhIeEAliQMy.png)



## 模型层以及ORM框架

- 创建：
- ![image-20211030124827973](https://i.loli.net/2021/10/30/2Wnrj5ypH8sqR7c.png)

## ORM查询

- ![image-20211122104004830](https://i.loli.net/2021/11/22/puj1rTIhzAaNMon.png)
- ![image-20211122105750988](https://i.loli.net/2021/11/22/IDngZRixJVeUBCh.png)

### 重要的练习：

![image-20211122111055455](https://i.loli.net/2021/11/22/YoJVhPEzSLq3Ge6.png)

- filter（）包含所选信息的筛选
- exclude（）除了条件内所写的都列出（排除法）
- ==**get**（）==返回单条数据，如果多余一条，则报错了
- 
