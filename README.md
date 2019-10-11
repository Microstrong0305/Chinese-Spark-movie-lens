# Chinese-Spark-movie-lens
基于Spark、Python Flask和MovieLens dataset的在线电影推荐系统

## 项目简介
- 该电影推荐系统库翻译自：https://github.com/jadianes/spark-movie-lens | [对应的blog](https://www.codementor.io/jadianes/building-a-web-service-with-apache-spark-flask-example-app-part2-du1083854)
- 适合初学者学习如何搭建一个推荐系统

---
# 基于Spark和Flask实现一个可扩展的在线电影推荐系统

这个Apache Spark教程将指导您逐步了解如何使用Spark的Alternating Least Saqures（交替最小二乘法，ALS）实现的协同过滤来基于[MovieLens数据集](https://grouplens.org/datasets/movielens/)构建电影推荐系统。这个教程分为两部分。第一部分是关于加载和解析电影和评分数据进入到Spark RDDs。第二部分是构建和使用这个推荐系统并且在线持续的使用它。

可以单独使用本教程构建基于MovieLens数据集的影片推荐模型。第一部分中关于如何将ALS与MovieLens数据集一起使用的大多数代码来自我对 CS100.1x Introduction to Big Data with Apache Spark by Anthony D. Joseph on edX 中提出的练习题之一的解决方案，该解决方案自2014年起在Spark Summit上公开发布。从那时起，我添加了一些小修改已使用更大的数据集，然后编写有关如何存储和重新加载模型以供以后使用的代码，最后使用Flask进行Web服务。

在任何情况下，此算法与此数据集的使用并不是新的，这是因为我们强调最终会在在线的环境中使用模型，以及如何在不同的情况下使用它。但我真的受到了解决该课程中提出练习的启发，我强烈建议你学习它。在那里你将学习到不仅有ALS，还有许多其它的Spark算法。

本教程的第二部分是解释如何使用Python/Flask在Spark模型之上构建Web服务的部分。 通过这样做，您将能够开发完整的在线电影推荐服务。

## Part 1：[构建推荐系统](building-recommender.ipynb)

## Part 2：[构建和运行web服务](Building_Running_web_service.ipynb)

## 快速开始

```
// 首先要进入Spark安装目录中的bin文件夹中
D:\spark\spark-2.3.3-bin-hadoop2.7\bin\spark-submit server.py
```

## 相关内容
- 【1】[Win10的Spark + Python Flask环境搭建](https://mp.weixin.qq.com/s?__biz=MzI5MzIwNDI1MQ==&mid=2650120932&idx=5&sn=fa924c8677411661a31df945b330c028&chksm=f474ba90c303338678dcd26edd5707d667c4bbe4a93b1f4e33591892cd858fd2da8db988be38&mpshare=1&scene=23&srcid=0117k0pBqKT5ucoXacbBHMfW&client=tim&ADUIN=278793087&ADSESSION=1517886579&ADTAG=CLIENT.QQ.5537_.0&ADPUBNO=26752#rd)
- 【2】 在线图书推荐系统的实现含源码（协同过滤）[知乎](https://zhuanlan.zhihu.com/p/31473161) | [GitHub](https://github.com/XuefengHuang/RecommendationSystem)
- 【3】 [Spark中ALS的实现原理](https://github.com/endymecy/spark-ml-source-analysis/blob/master/%E6%8E%A8%E8%8D%90/ALS.md)

## 关注微信公众号交流
![微信公众号]()
