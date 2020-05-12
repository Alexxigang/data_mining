### 教程系列简介

系列地址：[https://www.cnblogs.com/xiaohuiduan/category/1661541.html](https://www.cnblogs.com/xiaohuiduan/category/1661541.html)

该教程为入门教程，为博主学习数据挖掘的学习路径步骤。教程为入门教程，从最简单的开始。使用的编程语言为Python3.8.1，使用JupyterNotebook作为开发环境（使不使用JupyterNotebook都没有关系）。

在学习本教程之前，你需要：

- 有一点python编程基础
- 会用[百度](https://baidu.com) or [谷歌](https://google.com)
- 数学知识还是要一点的（但是要多少呢？我也不知道，我也是刚开始学）

我也是刚学，如有任何问题，可以邮箱联系我：xiaohuiduan@smail.hunnu.edu.cn

本项目会涉及如下：

在项目中，一般每一部分只由一篇博客构成，但是如果比较难的话会分为两个部分，前一部分为python代码实现，后面一部分为介绍。

1. [数据挖掘入门系列教程（一）之亲和性分析](https://www.cnblogs.com/xiaohuiduan/p/12419410.html) 
2. [数据挖掘入门系列教程（二）之分类问题OneR算法](https://www.cnblogs.com/xiaohuiduan/p/12446058.html) 
3. [数据挖掘入门系列教程（三）之scikit-learn框架基本使用（以K近邻算法为例）](https://www.cnblogs.com/xiaohuiduan/p/12463757.html) 
   - [数据挖掘入门系列教程（二点五）之K-近邻算法和距离度量介绍](https://www.cnblogs.com/xiaohuiduan/p/12452114.html) 
4. [数据挖掘入门系列教程（四）之基于scikit-lean实现决策树](https://www.cnblogs.com/xiaohuiduan/p/12495539.html) 
   - [数据挖掘入门系列教程（三点五）之决策树](https://www.cnblogs.com/xiaohuiduan/p/12490064.html) 
5. [数据挖掘入门系列教程（五）之Apriori算法Python实现](https://www.cnblogs.com/xiaohuiduan/p/12526837.html) 
6. [数据挖掘入门系列教程（六）之数据集特征选择](https://www.cnblogs.com/xiaohuiduan/p/12562974.html) 
7. [数据挖掘入门系列教程（七）之朴素贝叶斯进行文本分类](https://www.cnblogs.com/xiaohuiduan/p/12593256.html) 
8. [数据挖掘入门系列教程（八）之使用神经网络（基于pybrain）识别数字手写集MNIST](https://www.cnblogs.com/xiaohuiduan/p/12635624.html) 
   - [数据挖掘入门系列教程（七点五）之神经网络介绍](https://www.cnblogs.com/xiaohuiduan/p/12623925.html) 
9. [数据挖掘入门系列教程（九）之基于sklearn的SVM使用](https://www.cnblogs.com/xiaohuiduan/p/12745948.html) 
   - [数据挖掘入门系列教程（八点五）之SVM介绍以及从零开始公式推导](https://www.cnblogs.com/xiaohuiduan/p/12688812.html) 
10. [数据挖掘入门系列教程（十）之k-means算法](https://www.cnblogs.com/xiaohuiduan/p/12758121.html) 
11. [数据挖掘入门系列教程（十一）之keras入门使用以及构建DNN网络识别MNIST](https://www.cnblogs.com/xiaohuiduan/p/12806241.html) 
    - [数据挖掘入门系列教程（十点五）之DNN介绍及公式推导](https://www.cnblogs.com/xiaohuiduan/p/12790996.html) 
12. [数据挖掘入门系列教程（十二）之使用keras构建CNN网络识别CIFAR10](https://www.cnblogs.com/xiaohuiduan/p/12813368.html) 
    - [数据挖掘入门系列教程（十一点五）之CNN网络介绍](https://www.cnblogs.com/xiaohuiduan/p/12812288.html) 
13.  [数据挖掘入门系列教程（结束）](https://www.cnblogs.com/xiaohuiduan/p/12877094.html)

从无到有，陆陆续续一个**数据挖掘入门系列**的教程就写了18篇博客了，这个是我没有想到的，本来以为可能写10篇博客就结束了，但是写着写着写着写着就写了这么多。

总的来说，这个系列的博客写的不是很满意，因为不知为何自己就把侧重点放到到机器学习上面去了，使得这个系列的博客越来越像机器学习的入门博客┑(￣Д ￣)┍，对数据具体如何处理反而没有做什么介绍。但是，这个也不能怪我，实在是《Python数据挖掘入门与实践》 这本书到后面就开始介绍神经网络了，然后呢我又对其进行了补充（补充了CNN的内容以及介绍）。同时书中的**“图”和“mapreduce”的内容没有做介绍！！！**emm，我嫌麻烦就懒得弄了。

![](imgs/19e5466a55ac7ac5879c30e2aba5df15.gif)

是新手的我，刚开始以为数据挖掘和机器学习很难，但是机缘巧合的接触到了《Python数据挖掘入门与实践》这本书，在书中，刚开始以一个很简单的算法：[数据挖掘入门系列教程（一）之亲和性分析](https://www.cnblogs.com/xiaohuiduan/p/12419410.html) 让我顿时觉得，哇！怎么这么简单。尽管这本书很老了，但是却让我以一种无脑的方式开始了我的学习之旅。但是到后面就有一点坑（比如说使用SVM，但是却不告诉我SVM是什么🤮）。

尽管这个教程目前来说我不是很满意，但是同时系列也不会再进行更新（纠错除外）。想了想，尽管这个教程作为一个数据挖掘的教程明显是不合格的，但是对于入门教程来说，自我感觉还是🆗的，因为对于入门的我们来说，并不需要去**深入**去了解数据挖掘及其算法，它只需要告诉我们：

![](imgs/2683cb73a8c3a85e15d9eb20322081b2.jpg)

而只有当我们提起兴趣之后，我们才能够更好的进行学习。因此看完这教程的时候，就更应该继续看书了，更加深入的去了解数据挖掘。

长路漫漫唯键盘作伴，数据挖掘没有这么简单，但是当我们对其产生兴趣的时候，也许它也就变得简单了。我们寻找一个个数据背后所蕴含的规律，跟随前人的步伐甚至突破，最后得到满意的结果时，看着自己掉落的头发，emm好像也值得了？？

> Talk is cheap, show me the code. 

如果有任何问题，欢迎私信或mail。


