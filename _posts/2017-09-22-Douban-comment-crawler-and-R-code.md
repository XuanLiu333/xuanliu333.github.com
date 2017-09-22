---
layout: post
title:  "Douban python crawler and R data analysis "
date:   2017-09-22
desc: "using http cookies to bypass the access block"
keywords: "python,crawler,data analysis,R studio,spider"
categories: [python]
tags: [python,crawler]
icon: icon-html
---

I've learn to use python to crawl data from douban. In the first place, I choose to use light-weigt request
lib to get http response and use beatiful soup or panda to fetch the data.

Compared with heavy-weighted crawler framework lib scrapy, beatiful soup has features to access data with a restrict structure, for example, access array should identify the array at first. 
Panda has the advantage of formating the csv output, or table stucture data.

Scrapy is the best, as it can customize `setting.py` files and also create your own middleware which is more efficient on put data into relational database(like MySQL) or non- relational database(MongoDB).

The below learnig reference would be very informative:

1. **zhanlang movie a complete python crawler with data cleanning and visualization**
	[Documentation & Description](https://isaacchanghau.github.io/2017/09/10/Python-%E6%B5%85%E6%9E%90-%E6%88%98%E7%8B%BC2-170000-%E5%BD%B1%E8%AF%84%E6%95%B0%E6%8D%AE/)
	[Github Page](https://github.com/IsaacChanghau/AmusingPythonCodes)

2. **zhanlang review data analytics another apporach**
	[Link](http://www.bijishequ.com/detail/446262?p=)

3. **!! A VERY USEFUL douban scrapy spider summary with several practice**
	[Link](http://www.jianshu.com/p/c30df581b9fc)

4. **douban book review crawler example**
	[Link](https://github.com/xiaff/dbc-downloader)

5. **explain the knowledge of spider proxy**
	[Link](http://kaito-kidd.com/2015/11/02/proxies-service/)

6. **scrapy douban book**
	[Link](http://izualzhy.cn/python/2015/08/27/scrapy-doubanbook)

7. **!! deep-understanding of scrapy how middleware works**
	[Link](http://www.jianshu.com/p/be856bc15afb)

8. **higher level scrapy aiohttp proxy usage**
	[Link](http://www.jianshu.com/p/1cd6d34407e2)



