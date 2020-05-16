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
(2) 按照距离（一般欧氏距离）递增次序排序；  
(3) 选取与当前点距离最小的k个点；  
(4) 确定前k个点所在类别的出现频率；  
(5) 返回前k个点出现频率最高的类别作为当前点的预测分类。
- **决策树：**
决策树的一般流程：  
(1) 收集数据：可以使用任何方法。  
(2) 准备数据：树构造算法只适用于标称型数据，因此数值型数据必须离散化。  
(3) 分析数据：可以使用任何方法，构造树完成之后，我们应该检查图形是否符合预期。  
(4) 训练算法：构造树的数据结构。  
(5) 测试算法：使用经验树计算错误率。  
(6) 使用算法：此步骤可以适用于任何监督学习算法，而使用决策树可以更好地理解数据的内在含义。
- **朴素贝叶斯**
朴素贝叶斯的一般过程：  
(1) 收集数据：可以使用任何方法。本章使用RSS源。  
(2) 准备数据：需要数值型或者布尔型数据。  
(3) 分析数据：有大量特征时，绘制特征作用不大，此时使用直方图效果更好。  
(4) 训练算法：计算不同的独立特征的条件概率。  
(5) 测试算法：计算错误率。  
(6) 使用算法：一个常见的朴素贝叶斯应用是文档分类。可以在任意的分类场景中使用朴素贝叶斯分类器，不一定非要是文本。  
- **Logistic回归**
一般过程  
(1) 收集数据：采用任意方法收集数据。  
(2) 准备数据：由于需要进行距离计算，因此要求数据类型为数值型。另外，结构化数据
格式则最佳。  
(3) 分析数据：采用任意方法对数据进行分析。  
(4) 训练算法：大部分时间将用于训练，训练的目的是为了找到最佳的分类回归系数。  
(5) 测试算法：一旦训练步骤完成，分类将会很快。  
(6) 使用算法：首先，我们需要输入一些数据，并将其转换成对应的结构化数值；接着，基于训练好的回归系数就可以对这些数值进行简单的回归计算，判定它们属于哪个类别；在这之后，我们就可以在输出的类别上做一些其他分析工作。
- **支持向量机**

