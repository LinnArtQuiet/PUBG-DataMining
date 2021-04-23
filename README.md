# PUBG-DataMining
PUBG绝地求生策略聚类和排名预测\n

solo: 单排问题的数据集和代码\n
duo: 双排问题的数据集和代码\n
squad: 四排问题的数据集和代码\n

notebook的打开运行顺序如下：\n
1、PUBG preprocessing：该ipynb文件为数据预处理部分（处理后的数据另存为data）\n
2、PUBG Des：该ipynb文件为描述性统计部分，包括单排、双排、四排的，并分别抽取5万的样本（抽样后的数据另存sample）\n
3、PUBG Solo, PUBG Duo, PUBG Squad：这三个ipynb文件分别包括单排、双排、四排的特征选择和预测（特征选择后的数据另存为select）\n
4、PUBG clustering：包括特征选择前和特征选择后的单排、双排、四排问题的聚类（聚类后的数据附上聚类标签另存为cluster）\n

P.S.每一个notebook都可以单独打开运行，每一个步骤都进行了数据另存\n

运用到的模型（需要提前安装的包）：\n
pandas、matplotlib、seaborn、sklearn、 keras\n

运用到的方法：\n
1、描述性统计：plt，sns\n
2、聚类：Kmeans、AGG、DBSCAN\n
3、预测：神经网络、线性回归、决策树、KNN、GBRT、Lasso\n
4、特征选择：SelectKBest\n
