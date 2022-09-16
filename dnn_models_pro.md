### 

先来看一下未优化的效果，2000次普通网络cost 打印:

<img src="./image_dnn_pro测试/2000次普通网络cost 打印.png" alt="2000次普通网络cost 打印" style="zoom:67%;" />

2000次普通网络cost 学习图：

<img src="./image_dnn_pro测试/2000次普通网络cost 学习图.png" alt="2000次普通网络cost 学习图" style="zoom: 33%;" />

2000次普通网络训练样本准确率 1.0 ：

<img src="./image_dnn_pro测试/2000次普通网络训练样本准确率 1.0.png" alt="2000次普通网络训练样本准确率 1.0" style="zoom: 67%;" />

2000次普通网络测试样本准确率 0.58，这里准确率很低，是过拟合：

<img src="./image_dnn_pro测试/2000次普通网络测试样本准确率 0.58，这里准确率很低，是过拟合.png" alt="2000次普通网络测试样本准确率 0.58，这里准确率很低，是过拟合" style="zoom: 80%;" />

### 采用L2正则化+Adam优化

2000次 L2 + adam优化cost 打印：

<img src="./image_dnn_pro测试/2000次adam优化cost 打印.png" alt="2000次adam优化cost 打印" style="zoom: 50%;" />

2000次 L2 + adam优化cost 学习图：

<img src="./image_dnn_pro测试/2000次adam优化cost 学习图.png" alt="2000次adam优化cost 学习图" style="zoom: 40%;" />

2000次 L2 + adam优化训练样本准确率 :

<img src="./image_dnn_pro测试/2000次adam优化训练样本准确率.png" alt="2000次adam优化训练样本准确率" style="zoom:60%;" />

2000次 L2 + adam优化测试样本准确率：

<img src="./image_dnn_pro测试/2000次adam优化测试样本准确率.png" alt="2000次adam优化测试样本准确率" style="zoom:60%;" />

### 采用Dropout+Adam优化

3000 dropout+adam优化:

<img src="./image_dnn_pro测试/3000 dropout+adam优化.png" alt="3000 dropout+adam优化" style="zoom: 40%;" />

3000 dropout+adam优化cost学习图 :

<img src="./image_dnn_pro测试/3000 dropout+adam优化cost学习图.png" alt="3000 dropout+adam优化cost学习图" style="zoom: 33%;" />

3000 dropout+adam优化训练样本正确率 :

<img src="./image_dnn_pro测试/3000 dropout+adam优化训练样本正确率.png" alt="3000 dropout+adam优化训练样本正确率" style="zoom: 67%;" />

3000 dropout+adam优化 测试样本准确率:

<img src="./image_dnn_pro测试/3000 dropout+adam优化 测试样本准确率.png" alt="3000 dropout+adam优化 测试样本准确率" style="zoom: 67%;" />



优化效果不是很明显...
