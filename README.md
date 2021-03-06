# BP神经网络

## 数据集：
基于MNIST数据集

## 改进细节：
1.将激活函数从常用的sigmoid函数改为了Relu函数<br>
2.其次考虑到该问题实际为多分类问题，引入softmax作为输出层以及交叉熵作为损失函数<br>
3.最后引入批处理，将训练集分为训练批进行训练，提升了神经网络的运行效率<br>

## 模型对比结论：
本实验中详细探讨了参数调整对模型效果以及训练时间的影响<br>
有如下发现：<br>
1.发现该模型的训练时间对迭代次数以及隐藏层神经元个数较为敏感<br>
2.隐藏层层数、学习率以及迭代次数对训练效果影响较大<br>
3.将改进BP模型与常见的机器学习以及深度学习模型，如随机森林和卷积神经网络等，<br>
  进行模型效果和训练时间的综合对比，改进后的BP神经网络在两方面都表现突出。<br>

## 运行结果：

| 模型名称 | 测试集效果 | 训练时间（秒）|
| ------ | ------ | ------ |
| BP | 0.97540 | 35.71 |
| Logistics | 0.92030 | 105.76 |
| SVM | 0.94460 | 935.98 |
| RF | 0.94910 | 5.30 |
| CNN | 0.99200 | 245.98 |
