### PINN文章代码合集

可能最后的研究方向就是做PINN了，虽然不是很喜欢这个方向，但是路还是要走下去的:crying_cat_face:

本博客更新一些我看到的有关PINN的文章【所有文章都有代码~】

**1.CONFIG: TOWARDS CONFLICT-FREE TRAINING OF PHYSICS INFORMED NEURAL NETWORKS**

文章地址：https://arxiv.org/pdf/2408.11104

代码地址：https://tum-pbs.github.io/ConFIG/

简介：可以用来处理损失冲突问题，我用的效果挺好的。

**2.Hidden  fluid mechanics: Learning velocity and pressure fields from flow  visualizations**

文章地址：https://www.science.org/doi/full/10.1126/science.aaw4741

代码地址：[GitHub - maziarraissi/HFM: Hidden   Fluid Mechanics](https://github.com/maziarraissi/HFM)

简介：可以读一读，少量数据驱动+控制方程。

**3.PhyCRNet:  Physics-informed Convolutional-Recurrent Network for Solving      Spatiotemporal PDEs**

文章地址：https://arxiv.org/pdf/2106.14103

代码地址：[https://github.com/isds-neu/PhyCRNet](https://github.com/maziarraissi/HFM)

简介：LSTM+PINN的合体，有研究意义，同时如何将传统的MLP转化为CNN的格式，甚至于Transformer的格式有启发意义。

**4.Finite basis physics-informed neural networks (FBPINNs)**

文章地址：[Finite   basis physics-informed neural networks (FBPINNs): a scalable domain   decomposition approach for solving differential equations | Advances in   Computational Mathematics](https://link.springer.com/article/10.1007/s10444-023-10065-9)

代码地址：[[GitHub - benmoseley/FBPINNs: Solve forward and inverse problems related to partial differential equations using finite basis physics-informed neural networks (FBPINNs)](https://github.com/benmoseley/FBPINNs?tab=readme-ov-file)](https://github.com/maziarraissi/HFM)

简介：将问题域划分成一个一个小的子域，有利于解决频谱偏差问题。

**5.GPT-PINN:  Generative Pre-Trained Physics-Informed Neural      Networks toward non-intrusive  Meta-learning of parametric PDEs**

文章地址：[https://arxiv.org/pdf/2303.14878](https://link.springer.com/article/10.1007/s10444-023-10065-9)

代码地址：https://github.com/skoohy/GPT-PINN

简介：考虑PINN的泛化能力，完成模型在新的条件之下快速的训练

**6.On the preprocessing of physics-informed neural networks: How to better utilize data in fluid mechanics**

文章地址：[https://www.sciencedirect.com/science/article/pii/S0021999125001202?via%3Dihub#ab0020](https://link.springer.com/article/10.1007/s10444-023-10065-9)

代码地址：https://github.com/Shengfeng233/PINN-Preprocess

简介：考虑数据预处理，如归一化，这篇文章中提到的一些方法可以去借鉴一下已投入大量精力改善_PINNs_的可训练性，例如领域分解、并行计算、尊重因果关系的自适应抽样、混合数值方案、复杂几何的位置信息编码等。虽然这些改进中的许多是参考传统数值方法开发的，但实际上，_PINNs_也可以通过采用主流机器学习算法的一些“技巧”来增强，例如自适应激活函数、自适应加权、迁移学习等。

**7.Meta  Learning for Improved Neural Network Wavefield Solutions**

文章地址：[https://www.sciencedirect.com/science/article/pii/S0021999125001202?via%3Dihub#ab0020](https://link.springer.com/article/10.1007/s10444-023-10065-9)

代码地址：https://github.com/Shengfeng233/PINN-Preprocess

简介：对于地震波的预测，可以借鉴里面元学习的方法

**8.An Expert's Guide to Training Physics-informed Neural Networks**

文章地址：[[2308.08468\] An Expert's Guide to Training Physics-informed Neural Networks](https://arxiv.org/abs/2308.08468)

代码地址：[GitHub - PredictiveIntelligenceLab/jaxpi](https://github.com/PredictiveIntelligenceLab/jaxpi)

简介：这里面涉及到了有关PINN预处理以及加速收敛的知识，是一个很好的用于PINN的库

**9.PINNacle: A Comprehensive Benchmark of Physics-Informed Neural Networks for Solving PDEs**

文章地址：[[2306.08827\] PINNacle: A Comprehensive Benchmark of Physics-Informed Neural Networks for Solving PDEs](https://arxiv.org/abs/2306.08827)https://arxiv.org/abs/2308.08468)

代码地址：[GitHub - i207M/PINNacle: Codebase for PINNacle: A Comprehensive Benchmark of Physics-Informed Neural Networks for Solving PDEs.](https://github.com/i207M/PINNacle?tab=readme-ov-file)

简介：这里面涉及到了有关PINN预处理以及加速收敛的知识，是一个很好的用于PINN的库

许多PINN论文是没有代码的，这里只列举了有代码的PINN，其实有些简单的PINN自己可以手动的尝试从0开始构建，还是不难的~

持续更新中,欢迎对博客内容提意见:hugs: