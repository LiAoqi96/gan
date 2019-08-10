主要研究了基于生成式对抗网络的交通数据填充与预测问题。通过分析交通流数据存在时空相关性的特点，针对现有的算法进行交通流数据填充和预测方面无法充分利用时空相关性特征的缺点，提出了两种新的算法。

首先，提出了一种基于3D_DCGAN的生成式对抗网络模型，在完整的训练数据下，能充分的使用交通流数据的时空特性，提高了预测精度。其次，还针对交通流数据收集中经常遇到的缺失情况，提出了一种基于AmbientGAN及三维卷积网络的网络模型以实现缺失情况下的交通流数据填充模型。利用北京出租车交通数据进行仿真实验，并与DeepST，ST-ResNet，Bayesian CP等算法进行比较，所提出的网络模
型在数据缺失情况下具有更好的恢复精度。
