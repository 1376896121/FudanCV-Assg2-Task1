## 复旦大学大数据学院计算机视觉期中作业Task1.
### Best Result
Alexnet（base_lr = 0.01, finetune_rate =1）准确率为52.4\%

Resnet18（base_lr = 0.001, finetune_rate =1）准确率为74.4\%
### 如何训练：
运行Alexnet.ipynb或Resnet18.ipynb。修改必要参数，如：

base_lr = 0.001      （输出层学习率）

finetune_rate = 0.01 （其他参数的学习率 / 输出层学习率）

###### 如果你想尝试Alexnet和Resnet18之外的其他CNN网络，需要注意不同网络输出层的替换方式有所不同。
### tensorboard可视化训练过程
文档存储在Alexnet和Resnet18文件夹中，可以下载下来通过tensorboard命令查看它们。
