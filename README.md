# Machine_Learning
机器学习
1. **什么是机器学习？**  
- 定义有所不同：1）根据经验不断优化。2）把无序的数据转换成有用的信息。  
- 主要任务：分类（监督）、回归（监督）、聚类（无监督）
- 涉及神经网络的机器学习叫深度学习
2. **学习的种类**  
监督与无监督：监督学习指的是“利用经验获取技能”，然后利用“技能”来“监督”测试集。无监督学习的训练集和测试集没有区别，聚类是典型的例子。还有一种中间情况，监督并不明确（如俄罗斯方块），称为强化学习。
3. **算法**
- **k邻近算法（KNN）：**  
对未知类别属性的数据集中的每个点依次执行以下操作：  
(1) 计算已知类别数据集中的点与当前点之间的距离；  
(2) 按照距离递增次序排序；  
(3) 选取与当前点距离最小的k个点；  
(4) 确定前k个点所在类别的出现频率；  
(5) 返回前k个点出现频率最高的类别作为当前点的预测分类。
