<h1 align = "center">:rocket: RandomForest :facepunch:</h1>

---
在随机森林中，每个决策树都是通过反复抽取数据集中的数据生成的训练集所拟合。此外，在生产决策树的过程中，节点的选择不再是属性中的最佳属性；节点为子集的最佳拆分节点。由于该随机性，森林的偏差通常略有增加；由于平均的原因，其方差会减少；会补偿偏差，因此该模型的整体收益较好。与原始版本相反，sklearn通过平均概率的方式集成，而不是通过投票的方式。
