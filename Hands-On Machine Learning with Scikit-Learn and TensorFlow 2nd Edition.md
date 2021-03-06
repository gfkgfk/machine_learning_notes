# Hands-On Machine Learning with Scikit-Learn and TensorFlow 2nd Edition

<https://github.com/ageron/handson-ml2>

### 第一章

<font color=blue >什么是机器学习，神经网络等等前言(略)</font>

#### 1.1、一些重要的监督学习算法

* K-邻近算法

* 线性回归算法

* 逻辑回归算法

* 支持向量机(SVMs)

* 决策树和随机森林

* 神经网络

#### 1.2、一些无监督学习算法

* 聚类
  * K-Means
  * DBSCAN
  * 分层聚类分析(HCA)

* 异常检测和新颖性检测

  * One-Class SVM

  * 分离森林

* 可视化和降维

  * 主要成分分析(PCA)
  * 内核 PCA
  * 本地线性嵌入 (LLE)
  * t 分布随机邻居嵌入 (t-SNE)

* 关联规则学习

  * 先验
  * Eclat

#### 1.3、部分学习方法的举例
当前该部分并不太理解。这是一部分举例的内容，有个大概的了解

#### 1.4  机器学习主要的两点
* 算法
* 数据
### 第二章 End-to-End



平均值:

方差:标准差的平方就是方差。由于在统计带有负号的数据的时候，如果不用平方最后求出来的标准差可能为0,因此才产生了方差

标准差:
![标准差公式](./images\标准差公式.jpg)

x表示一组数据集内的每一个数据，$\mu$表示这组数据集的均值， n表示数据集内的个数。

**标准差是描述数据或概率分布的集中程度。标准差小，数据/概率都离这个期望值不远；反之，如果标准差大则表示数据/概率离期望值很远，什么都有可能发生**。



RMSE:

RMSE与标准差对比：**标准差**是用来衡量**一组数**自身的**离散程度**，而**均方根误差**是用来衡量**观测值**同真值之间的偏差，它们的研究对象和研究目的不同，但是计算过程类似。



RMSE:Root Mean Square Error,均方根误差

对于线性回归问题，RMSE是一个典型的衡量指标。



MAE:平均绝对误差



范数：

L1-范数:曼哈顿范数,向量中所有元素的绝对值之和。可用于优化中去除没有取值的信息，又称稀疏规则算子。

L2-范数:欧几里得范数,典型应用——欧式距离。可用于优化正则化项，避免过拟合。

L无穷范数:切比雪夫范数,计算向量中的最大值。

标准指数越高，它越关注大值而忽略小值。这就是为什么 RMSE 对异常值比 MAE 更敏感的原因。但是，当异常值呈指数级罕见（如钟形曲线），RMSE 性能非常好，通常更受欢迎。







