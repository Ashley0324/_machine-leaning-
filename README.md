# 😀前言

相信很多同学认识吴恩达大佬都来自这门机器学习课程。也是目前公认最好的机器学习课程，最近重新整理了一下之前的学习笔记，包括文字笔记和相关代码，希望能对大家有所帮助。这门课非常适合小白入门，完成后就可以独立构建一个简单的监督模型，使用TensorFlow 构建和训练神经网络。NLP小菜鸟们，一起冲鸭！

Coursera课程链接：https://www.coursera.org/specializations/machine-learning-introduction#courses

# 📔 目录

### 1.引言(Introduction)
1.1 欢迎
1.2 机器学习是什么？
1.3 监督学习
1.4 无监督学习

### 2.单变量线性回归(Linear Regression with One Variable)
2.1 模型表示
2.2 代价函数
2.3 代价函数的直观理解I
2.4 代价函数的直观理解II
2.5 梯度下降
2.6 梯度下降的直观理解
2.7 梯度下降的线性回归
2.8 接下来的内容

### 3.线性代数回顾(Linear Algebra Review)
3.1 矩阵和向量
3.2 加法和标量乘法
3.3 矩阵向量乘法
3.4 矩阵乘法
3.5 矩阵乘法的性质
3.6 逆、转置

### 4.多变量线性回归(Linear Regression with Multiple Variables)
4.1 多维特征
4.2 多变量梯度下降
4.3 梯度下降法实践1-特征缩放
4.4 梯度下降法实践2-学习率
4.5 特征和多项式回归
4.6 正规方程
4.7 正规方程及不可逆性（选修）

### 5.Octave教程(Octave Tutorial)
5.1 基本操作
5.2 移动数据
5.3 计算数据
5.4 绘图数据
5.5 控制语句：for，while，if语句
5.6 向量化 88
5.7 工作和提交的编程练习

### 6.逻辑回归(Logistic Regression)
6.1 分类问题
6.2 假说表示
6.3 判定边界
6.4 代价函数
6.5 简化的成本函数和梯度下降
6.6 高级优化
6.7 多类别分类：一对多

### 7.正则化(Regularization)
7.1 过拟合的问题
7.2 代价函数
7.3 正则化线性回归
7.4 正则化的逻辑回归模型

### 8.神经网络：表述(Neural Networks: Representation)
8.1 非线性假设
8.2 神经元和大脑
8.3 模型表示1
8.4 模型表示2
8.5 样本和直观理解1
8.6 样本和直观理解II
8.7 多类分类

### 9.神经网络的学习(Neural Networks: Learning)
9.1 代价函数
9.2 反向传播算法
9.3 反向传播算法的直观理解
9.4 实现注意：展开参数
9.5 梯度检验
9.6 随机初始化
9.7 综合起来
9.8 自主驾驶

### 10.应用机器学习的建议(Advice for Applying Machine Learning)
10.1 决定下一步做什么
10.2 评估一个假设
10.3 模型选择和交叉验证集
10.4 诊断偏差和方差
10.5 正则化和偏差/方差
10.6 学习曲线
10.7 决定下一步做什么

### 11.机器学习系统的设计(Machine Learning System Design)
11.1 首先要做什么
11.2 误差分析
11.3 类偏斜的误差度量
11.4 查准率和查全率之间的权衡
11.5 机器学习的数据

### 12.支持向量机(Support Vector Machines)
12.1 优化目标
12.2 大边界的直观理解
12.3 数学背后的大边界分类（选修）
12.4 核函数1
12.5 核函数2
12.6 使用支持向量机

### 13.聚类(Clustering)
13.1 无监督学习：简介
13.2 K-均值算法
13.3 优化目标
13.4 随机初始化
13.5 选择聚类数

### 14.降维(Dimensionality Reduction)
14.1 动机一：数据压缩
14.2 动机二：数据可视化
14.3 主成分分析问题
14.4 主成分分析算法
14.5 选择主成分的数量
14.6 重建的压缩表示
14.7 主成分分析法的应用建议

### 15.异常检测(Anomaly Detection)
15.1 问题的动机
15.2 高斯分布
15.3 算法
15.4 开发和评价一个异常检测系统
15.5 异常检测与监督学习对比
15.6 选择特征
15.7 多元高斯分布（选修）
15.8 使用多元高斯分布进行异常检测（选修）

### 16.推荐系统(Recommender Systems)
16.1 问题形式化
16.2 基于内容的推荐系统
16.3 协同过滤
16.4 协同过滤算法
16.5 向量化：低秩矩阵分解
16.6 推行工作上的细节：均值归一化

### 17.大规模机器学习(Large Scale Machine Learning)
17.1 大型数据集的学习
17.2 随机梯度下降法
17.3 小批量梯度下降
17.4 随机梯度下降收敛
17.5 在线学习
17.6 映射化简和数据并行

### 18.应用实例：图片文字识别(Application Example: Photo OCR)
18.1 问题描述和流程图
18.2 滑动窗口
18.3 获取大量数据和人工数据
18.4 上限分析：哪部分管道的接下去做

### 19.总结(Conclusion)
总结和致谢

# 🍗 支持一下
拜托各位老爷们喜欢的话给新人点个🌟🌟，欢迎加入QQ群（839938357），一起学习互助。另外我的个人公众号也会分享一些关于AI，区块链的思考。
<img width="643" alt="截屏2023-09-01 16 56 23" src="https://github.com/Ashley0324/-/assets/99146042/65fabfa0-95cb-4663-8b9e-4e1c8f28a084">







