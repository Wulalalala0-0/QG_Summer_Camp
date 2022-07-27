# MAS Note(2)

> Written By: 思思不羡仙
> Date: 2022.07.26-2022.07.27

**论文：Hybrid-Order Network Consensus for Distributed Multi-agent Systems**

> 此笔记部分Motif翻译为基元，类比生物学名词

此笔记包含论文4部分的复现（很简单），主要完成了：

1. 论文数据集构建
2. 基元函数构建
3. 绘制参考图片

本文采用的是无向图且智能体状态信息采用相邻距离代替，因此复现图片部分内容可以遵循以下步骤：

1. 按照论文要求创建数据点集
2. 按照$r_c$构建邻接矩阵
3. 按照临接矩阵与数据点位置绘图

基元函数部分可以按此方法构建：

先找到两个相邻点，若相邻，再寻找与这两个点相邻的第三个点，若存在，则可将基元矩阵对应位置+1

以下是实验结果：

![output1](MAS Note(2).assets/output1.png)

![output2](MAS Note(2).assets/output2.png)

![output3](MAS Note(2).assets/output3.png)

![output4](MAS Note(2).assets/output4.png)

![output5](MAS Note(2).assets/output5.png)

![output6](MAS Note(2).assets/output6.png)

![output7](MAS Note(2).assets/output7.png)

![output8](MAS Note(2).assets/output8.png)

![output9](MAS Note(2).assets/output9.png)

![output10](MAS Note(2).assets/output10.png)