# Sklearn
## 数据格式
在Sklearn里，模型能即用的数据有两种形式：

*  Numpy二维数组（ndarray）的稠密数据（dense data），通常都是这种格式
*  SciPy矩阵（scipy.sparse.matrix）的稀疏数据（sparse data）

上述数据在机器学习中通常用符号 X 表示，是模型自变量。它的大小 = [样本数, 特征数]，图下图所示。该房屋数据有 21000 条包括平方英尺，卧室数，楼层，日期，翻新年份等等 21 栏。该数据形状为 [21000, 21]
![avatar](/AboutML/Data.png)
