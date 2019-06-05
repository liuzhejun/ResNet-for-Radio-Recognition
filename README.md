# ResNet-for-Radio-Recognition
### 论文"Over the Air Deep Learning Based Radio Signal Classification"的实现与改进。
### Implementation and improvement of "Over the Air Deep Learning Based Radio Signal Classification"

* 论文地址：[Over the Air Deep Learning Based Radio Signal Classification](https://arxiv.org/pdf/1712.04578.pdf)
* 数据集下载：[2018.01.OSC.0001_1024x2M.h5.tar.gz](http://opendata.deepsig.io/datasets/2018.01/2018.01.OSC.0001_1024x2M.h5.tar.gz)

## 文件描述

文件名 | 描述
-|-
ResNet_Model.ipynb | 原始的论文复现代码
ResNet_incomplete_dataset.ipynb | 改进的代码
sample_new_data2018.py | 分割数据集的代码
Models | 存放模型的文件夹

## 注意
* ResNet_Model.ipynb中代码仅用于与改进的代码作参数和训练时间上的对比，在细节处理上很粗糙，主要还是参考ResNet_incomplete_dataset.ipynb文件
* 分割数据集是因为硬件限制，有条件的可以直接使用完整数据集。
* 更多内容和解释请看博客：[使用ResNet模型进行无线电调制识别](https://blog.csdn.net/qq_34467412/article/details/90738232)
