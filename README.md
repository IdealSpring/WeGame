1.实现了单机版随机森林，但是在建树过程中出现了递归错误，内存溢出。--2018年4月19日17:46:35
2.代码错误问题解决。--2018年4月19日17:47:14
3.使用第一阶段数据，提取出5个属性。--2018年4月19日17:47:44
4.自己实现的算法，bug过，在预测准确上难以保证，决定使用开源的项目。--2018年4月19日17:51:20
5.在机器学习算法上，使用mahout的随机森林算法。机器学习算法现在已经很成熟。--2018年4月19日17:51:27
6.第一个模型实现，Accuracy=88.8889%,F1 score=0.9412,此F1分数不准确，由于属性和数据的极端化造成的。--2018年4月19日17:53:42
7.下一步，测试属性的组合。
8.在提取第7个属性:inputTaxAndOutputTaxRatio --进项税额变动率高于销项税额变动率，分离好训练数据测试数据的时候测试数据集小，F1和准确率低，在测试集大的时候，F1明显提高。
9.今天团队完成9个属性的提取工作。
