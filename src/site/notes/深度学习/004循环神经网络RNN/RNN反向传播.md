---
{"dg-publish":true,"permalink":"/深度学习/004循环神经网络RNN/RNN反向传播/","dg-note-properties":{}}
---

RNN中的反向传播叫做BPTT(本质还是链式法则)
由于时间维度，它是沿着时间轴往回传

###### 步骤
1、计算总损失Loss
2、梯度累加：把每个时间步的梯度都加起来
3、沿时间轴链式求导

