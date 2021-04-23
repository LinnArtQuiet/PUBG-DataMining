# PUBG-DataMining
PUBG绝地求生策略聚类和排名预测

solo: 单排问题的数据集和代码

duo: 双排问题的数据集和代码

squad: 四排问题的数据集和代码


notebook的打开运行顺序如下：

1、PUBG preprocessing：该ipynb文件为数据预处理部分（处理后的数据另存为data）

2、PUBG Des：该ipynb文件为描述性统计部分，包括单排、双排、四排的，并分别抽取5万的样本（抽样后的数据另存sample）

3、PUBG Solo, PUBG Duo, PUBG Squad：这三个ipynb文件分别包括单排、双排、四排的特征选择和预测（特征选择后的数据另存为select）

4、PUBG clustering：包括特征选择前和特征选择后的单排、双排、四排问题的聚类（聚类后的数据附上聚类标签另存为cluster）


P.S.每一个notebook都可以单独打开运行，每一个步骤都进行了数据另存


运用到的模型（需要提前安装的包）：

pandas、matplotlib、seaborn、sklearn、 keras


运用到的方法：

1、描述性统计：plt，sns

2、聚类：Kmeans、AGG、DBSCAN

3、预测：神经网络、线性回归、决策树、KNN、GBRT、Lasso

4、特征选择：SelectKBest

