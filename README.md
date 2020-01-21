# ResUnet-a
### 针对遥感影像的语义分割
## [English introduction here](https://github.com/mohuazheliu/ResUnet-a/edit/master/introduction/README.md)
### 论文地址[https://arxiv.org/abs/1904.00592]
### 原作者使用MXNet的实现[https://github.com/feevos/resuneta]
## 依赖
#### keras==2.2.2
#### tensorflow==1.9.0
#### cv2
#### numpy
## 训练
#### 修改train.py中unet.train的第一个参数为数据集地址，第二个参数为模型存放地址
#### 数据集文件格式见[https://github.com/mohuazheliu/ResUnet-a/blob/master/dataset-postdam/train/README.md]
## Predict
#### 参照test.py 使用model.predict对一张图片进行预测，使用model.visual可视化预测
### 细微差别
#### 关于PSPPooling的实现方法略有不同，这里参照了PSPNet的做法
## 训练损失，测试结果及预训练模型后续更新
