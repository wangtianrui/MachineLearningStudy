###### KNN

已有：标记好的数据集

然后输入没有标记的样本，将新样本的每个特征与样本集中每一数据特征进行比较，然后算法提取样本集中特征最相似数据的分类标签，一般来说只选择样本数据中前k个最相似的数据，这就是KNN中的K的出处，通常K不大于20，最后在这K个数据中找出现次数最多的类别，作为新分类。

##### 归一化操作：

* 可以保证所有newV都在0-1之间

> newV = (oldV - min) / (max - min) 

