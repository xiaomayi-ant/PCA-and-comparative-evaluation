# PCA
PCA算法常用于对存在相关性的高维数据进行降维处理，本文按照方差贡献率>0.85选择主成分
对广告数据进行分析，试图测定其间关系和建立评分或指数评估体系
项目选取CPM,CPC,CTR,CPA,CVR等5个指标，进行建模，根据一次建模选择第一，第二主成分
我们可以得到系数以及相应变量的线性表达式
其中:第一主成分中所有系数都为正,则y1表达广告的强度，同，y2表达广告的难度
