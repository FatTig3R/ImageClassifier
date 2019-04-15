# 前言

> 起源于一个不成熟的想法

最近在学习机器学习方面的一些知识，难免的就要学习卷积神经网络，在网上找了一些关于Keras、TensorFlow的文章或课程，发现有很多大佬使用Keras做一个图片分类器，比如猫狗识别。

然而我这个人就是看到什么新鲜的东西，感兴趣的东西就要去尝试一下。

从网上找了一些数据集，我就想能不能自己弄一个爬虫，当我需要什么数据就爬取什么数据，然后喂给神经网络，训练模型，再利用flask搭建一个web网站调用训练好的模型进行识别。

因为是一个菜鸟，估计做起来还是需要花费一些精力，再就是时间不是很充裕，所以这个项目从零到基本完成应该要花挺多时间。

反正也不急，慢慢做。

# 功能

- 1, Web Crawler  这个 GitHSub 有很多批量爬取图片的，就不自己造轮子的，有时间找一个好的直接开始用(偷懒)
- 2, Classifier   这个是重点(慢慢写)
- 3, Flask App    训练好模型之后再着手写(其实已经写好了)

# 更新日志

## 2019年4月10日   

创建项目, 命名为 "ImagesClassifier"

### TODO LIST

- [x] 将RESIZE RENAME的数据放一些到 Test_Images_Folder/ 目录下

## 2019年4月11日

- 完成 Training 相关代码，可以开始训练模型

不过昨天的任务还没完成，今晚去图书馆努力一下，加油

2019年4月11日22:51:19

终于弄好move file的任务了
接下来应该就弄爬虫了，有时间再找，溜了溜了

## 2019年4月15日
- [x] 完成图片的爬取

有个迷之bug, 只能爬取一个关键字的图片，不能用循环对多个关键字进行爬取(挠头)，等我打两把LOL再回来写。