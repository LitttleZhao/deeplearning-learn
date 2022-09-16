dnn_model 在第一次进行训练时 采用2层模型训练1500次

<img src="./image_dnn测试/1500次迭代数据打印.png" style="zoom: 67%;" />

<img src="./image_dnn测试/1500次迭代cost下降图.png" style="zoom: 33%;" />

可以见到损失函数还是很大

dnn_model 进行第二次训练时，采用3000次、6000次迭代

<img src="./image_dnn测试/3000次迭代数据打印.png" style="zoom: 33%;" />

<img src="./image_dnn测试/6000次迭代数据打印.png" style="zoom:50%;" />

损失已经足够低了，检测下预测值准确率： 6000次迭代，训练样本准确率由0.7变成1.0

<img src="./image_dnn测试/6000次迭代，训练样本准确率由0.7变成1.0.png" style="zoom: 67%;" />

检测下真实值准确率： 很低

<img src="./image_dnn测试/6000次迭代后，测试样本准确率第一次检测 0.585，很低.png" style="zoom:60%;" />

dnn_model 第四次训练，这次采用5层模型结构 12288，100，50，10，4，1的神经元数

<img src="./image_dnn测试/5层3000次迭代cost下降图.png" style="zoom:33%;" />

<img src="./image_dnn测试/5层3000次迭代数据打印，效果很好.png" alt="5层3000次迭代数据打印，效果很好" style="zoom:50%;" />

真实值预测已经能有0.605正确率，个人猜测：

1、需要更多的图片进行训练提升准确率

2、5层模型还是不够成熟，可能需要使用30层、100层、或者循环神经网络模型会更好。

<img src="./image_dnn测试/5层3000次迭代测试样本测试，效果仍然只有0.605.png" alt="5层3000次迭代测试样本测试，效果仍然只有0.605" style="zoom: 67%;" />

