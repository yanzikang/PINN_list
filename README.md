## PINN总汇

**搜索关键词：Physics，Physics-informed, PINN, PDE, Operator**

### Papers on PINN Models

- **PINNsFormer: A Transformer-Based Framework For Physics-Informed Neural Networks**,Zhiyuan Zhao,Xueying Ding,B. Aditya Prakash,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/19142)] [[code](https://github.com/AdityaLab/pinnsformer)]
- **Scaling physics-informed hard constraints with mixture-of-experts**,Nithin Chalapathi,Yiheng Du,Aditi Krishnapriyan,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/17590)] [[code](https://github.com/ASK-Berkeley/physics-NNs-hard-constraints)]
- **Space and time continuous physics simulation from partial observations**,Steeven Janny,Madiha Nadri,Julie Digne,Christian Wolf,ICLR,2024.[[paper](https://iclr.cc/virtual/2024/poster/19444)] [[code](https://github.com/continuous-pde/continuous-pde)]
- **PIG: Physics-Informed Gaussians as Adaptive Parametric Mesh Representations**,Zeyu Li,Hongkun Dou,Shen Fang,Wang Han,Yue Deng,Lijun Yang,ICLR,2025.[[paper](https://arxiv.org/abs/2412.05994)] [[code](https://github.com/NamGyuKang/Physics-Informed-Gaussians)]
- **MeshMask: Physics-Based Simulations with Masked Graph Neural Networks**,Paul Garnier,Vincent Lannelongue, Jonathan Viquerat,Elie Hachem,ICLR,2025. [[paper](https://arxiv.org/pdf/2501.08738)] [[code]()]
- **PARCv2: Physics-aware Recurrent Convolutional Neural Networks for Spatiotemporal Dynamics Modeling**, Phong C.H. Nguyen, Xinlun Cheng, Shahab Azarfar, Pradeep Seshadri, Yen T. Nguyen, Munho Kim, Sanghun Choi, H.S. Udaykumar, Stephen Baek.ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/33980)] [[code](https://github.com/hphong1990/PARCv2)]
- **Transolver: A Fast Transformer Solver for PDEs on General Geometries**,Haixu Wu, Huakun Luo, Haowen Wang, Jianmin Wang, Mingsheng Long,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/33751)] [[code](https://github.com/thuml/Transolver)]

### Papers on Parallel PINN

- **Physics and Lie symmetry informed Gaussian processes**,David Dalton, Dirk Husmeier, Hao Gao,ICML,2024.  [[paper](https://icml.cc/virtual/2024/poster/35147)] [[code](https://github.com/dodaltuin/jax-pigp/tree/main/examples/PSGPs)]

### Papers on PINN Accerleration

- **PINNACLE: PINN Adaptive ColLocation and Experimental points selection**,Gregory Kang Ruey Lau,Apivich Hemachandra,See-Kiong Ng,Bryan Kian Hsiang Low,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/19012)] [[code](https://github.com/apivich-h/pinnacle)]
- **Adversarial Adaptive Sampling: Unify PINN and Optimal Transport for the Approximation of PDEs**,Kejun Tang,Jiayu Zhai,Xiaoliang Wan,Chao Yang,ICRL,2024. [[paper](https://iclr.cc/virtual/2024/poster/19361)]
- **Learning a Neural Solver for Parametric PDEs to Enhance Physics-Informed Methods**，Lise Le Boudec, Emmanuel de Bézenac, Louis Serrano,Ramon Daniel Regueiro-Espino,Yuan Yin,patrick Gallinari,ICLR,2025. [[paper](https://arxiv.org/abs/2410.06820)] [[code]([https://github.com/2ailesB/neural-solver)] //没有发布代码
- **Metamizer: A Versatile Neural Optimizer for Fast and Accurate Physics Simulations**，Nils Wandel,Stefan Schulz,Reinhard Klein,ICLR,2025. [[paper](https://arxiv.org/pdf/2410.19746)] [[code](https://github.com/wandeln/metamizer)]
- **Physics-aligned field reconstruction with diffusion bridge**,Zeyu Li,Hongkun Dou,Shen Fang,Wang Han,Yue Deng,Lijun Yang,ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/30484)] [[code](https://github.com/lzy12301/PalSB)]
- **PINP: Physics-Informed Neural Predictor with latent estimation of fluid flows**,Huaguan Chen,Yang Liu,Hao Sun,ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/27928)]
- **ConFIG: Towards Conflict-free Training of Physics Informed Neural Networks**,Qiang Liu,Mengyu Chu,Nils Thuerey,ICLR,2025. [[paper](https://arxiv.org/abs/2408.11104)] [[code](https://tum-pbs.github.io/ConFIG/)]

- **ANaGRAM: A Natural Gradient Relative to Adapted Model for efficient PINNs learning**,Nilo Schwencke,Cyril Furtlehner,ICLR,2025. [[paper](https://arxiv.org/abs/2412.10782)] [[code](https://github.com/IloneM/ANaGRAM/)] // 代码打不开
- **Predicting the Energy Landscape of Stochastic Dynamical System via Physics-informed Self-supervised Learning**, Wenhan Gao,Ruichen Xu,Yuefan Deng,Yi Liu,ICLR,2025.[[paper](https://arxiv.org/pdf/2502.16828)] [[code](https://github.com/tsinghua-fib-lab/PESLA)]
- **TENG: Time-Evolving Natural Gradient for Solving PDEs With Deep Neural Nets Toward Machine Precision**, Zhuo Chen, Jacob Mccarran, Esteban Vizcaino, Marin Soljacic, Di Luo ,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/32799)] [[code](https://github.com/pde-sim/teng)]
- **Dual Cone Gradient Descent for Training Physics-Informed Neural Networks**，*Youngsik Hwang, Dong-Young Lim*，NeurIPS,2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b2b781badeeb49896c4b324c466ec442-Abstract-Conference.html)] [[code](https://github.com/youngsikhwang/Dual-Cone-Gradient-Descent)]
- **Physics-informed Neural Networks for Functional Differential Equations: Cylindrical Approximation and Its Convergence Guarantees**，*Taiki Miyagawa, Takeru Yokota*,NeurIPS,2024.[[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/84c6c76526783f4afd82687829d3aa97-Abstract-Conference.html)] [[code](https://github.com/TaikiMiyagawa/FunctionalPINN)]
- **Kronecker-Factored Approximate Curvature for Physics-Informed Neural Networks**，*Felix Dangel, Johannes Müller, Marius Zeinhofer*，NeurIPS,2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/3d27d607586984908900eaa8ce19c96c-Abstract-Conference.html)] 

### Papers on Model Transfer & Meta-Learning

- **MetaPhysiCa: Improving OOD Robustness in Physics-informed Machine Learning**,S Chandra Mouli , Muhammad Alam,Bruno Ribeiro,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/18883)] [[code](https://github.com/PurdueMINDS/MetaPhysiCa)]
- **DATS: Difficulty-Aware Task Sampler for Meta-Learning Physics-Informed Neural Networks**,Maryam Toloubidokhti,Yubo Ye,Ryan Missel,Xiajun Jiang,Nilesh Kumar,Ruby Shrestha,Linwei Wang,ICLR,2024.[[paper](https://iclr.cc/virtual/2024/poster/19085)] [[code](https://github.com/maryamTolou/DATS_ICLR2024)]
- **PIED: Physics-Informed Experimental Design for Inverse Problems**,Apivich Hemachandra,Gregory Kang Ruey Lau,See-Kiong Ng,Bryan Kian Hsiang Low,ICLR,2025. [[paper](https://arxiv.org/pdf/2503.07070)] [[code](https://github.com/apivich-h/pied)]

### Papers on Probabilistic PINNs and Uncertainty Quantification

- **RoPINN: Region Optimized Physics-Informed Neural Networks**,*Haixu Wu, Huakun Luo, Yuezhou Ma, Jianmin Wang, Mingsheng Long*,NeurIPS,2024.  [[paper](https://neurips.cc/virtual/2024/poster/93144)] [[code](https://github.com/thuml/RoPINN)]

### Papers on Applications

- **AirPhyNet: Harnessing Physics-Guided Neural Networks for Air Quality Prediction**,Kethmi Hirushini Hettige, Jiahao Ji,Shili Xiang,Cheng Long,Gao Cong,Jingyuan Wang,ICLR,2024.[[paper](https://iclr.cc/virtual/2024/poster/18940)] [[code](https://github.com/kethmih/AirPhyNet)]

- **PIORF: Physics-Informed Ollivier-Ricci Flow for Long–Range Interactions in Mesh Graph Neural Networks**,Youn-Yeol Yu,Jeongwhan Choi,Jaehyeon Park,Kookjin Lee,Noseong Park,ICLR,2025 [[paper](https://iclr.cc/virtual/2025/poster/28238)]

- **Physics-Informed Diffusion Models**,Jan-Hendrik Bastek,WaiChing Sun,Dennis Kochmann,ICLR,2025.[[paper](https://arxiv.org/abs/2403.14404)] [[code](https://github.com/jhbastek/PhysicsInformedDiffusionModels?tab=readme-ov-file)]

- **Air Quality Prediction with Physics-Guided Dual Neural ODEs in Open Systems**,jindong tian,Yuxuan Liang, Ronghui Xu,Peng Chen,Chenjuan Guo,Aoying Zhou,Lujia Pan,Zhongwen Rao,Bin Yang,ICLR,2025.[[paper](https://openreview.net/pdf?id=kOJf7Dklyv)] [[code](https://github.com/decisionintelligence/Air-DualODE)]

- **Generating Physical Dynamics under Priors**,Zihan Zhou,Xiaoxue Wang,Tianshu Yu,ICLR,2025.[[paper](https://arxiv.org/pdf/2409.00730)] [[code]()]

- **PAPM: A Physics-aware Proxy Model for Process Systems**,Pengwei Liu, Zhongkai Hao, Xingyu Ren, Hangjie Yuan, Jiayang Ren, Dong Ni,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/34037)] [[code](https://github.com/pengwei07/PAPM)]

- **Med-Real2Sim: Non-Invasive Medical Digital Twins using Physics-Informed Self-Supervised Learning**, *Keying Kuang, Frances Dean, Jack B. Jedlicki, David Ouyang, Anthony Philippakis, David Sontag, Ahmed Alaa*,NeurIPS,2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0b081a44ed0b8c0c4aa6bd886a60bea4-Abstract-Conference.html)] [[code](https://github.com/AlaaLab/med-real2sim)]

  

### Papers on PINN Analysis

- **On the Benefits of Memory for Modeling Time-Dependent PDEs**,Ricardo Buitrago Ruiz,Tanya Marwah,Albert Gu,Andrej Risteski,ICLR,2025. [[paper](https://arxiv.org/pdf/2409.02313)]
- **PhysPDE: Rethinking PDE Discovery and a Physical HYpothesis Selection Benchmark**,Mingquan Feng,Yixin Huang,Yizhou Liu,Bofang Jiang,Junchi Yan,ICLR.2025.[[paper](https://openreview.net/forum?id=G3CpBCQwNh)] 
- **Challenges in Training PINNs: A Loss Landscape Perspective**，Pratik Rathore, Weimu Lei, Zachary Frangella, Lu Lu, Madeleine Udell,ICML,2024 [[paper](https://icml.cc/virtual/2024/poster/33180)] [[code](https://github.com/pratikrathore8/opt_for_pinns)]
- **Physics-Informed Neural Network Policy Iteration: Algorithms, Convergence, and Verification**,Yiming Meng, Ruikun Zhou, Amartya Mukherjee, Maxwell Fitzsimmons, Christopher Song, Jun Liu,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/32906)] [[code](https://git.uwaterloo.ca/hybrid-systems-lab/lyznet/)]
- **Efficient Error Certification for Physics-Informed Neural Networks**,Francisco Eiras, Adel Bibi, Rudy R Bunel, Krishnamurthy Dj Dvijotham, Philip Torr, M. Pawan Kumar ,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/34959)]
- **Parameterized Physics-informed Neural Networks for Parameterized PDEs**,Woojin Cho, Minju Jo, Haksoo Lim, Kookjin Lee, Dongeun Lee, Sanghyun Hong, Noseong Park*,ICML,2024. [[paper](https://proceedings.mlr.press/v235/cho24b.html)] [[code](https://github.com/search?q=Parameterized+Physics-informed+Neural+Networks&type=code)]
- **Learning from Integral Losses in Physics Informed Neural Networks**,Ehsan Saleh, Saba Ghaffari, Tim Bretl, Luke Olson, Matthew West,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/33334)] [[code](https://github.com/ehsansaleh/btspinn)]
- **UGrid: An Efficient-And-Rigorous Neural Multigrid Solver for Linear PDEs**,Xi Han, Fei Hou, Hong Qin,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/32790)] [[code](https://github.com/AXIHIXA/UGrid)]  // 这里面涉及到U-Net
- **How does PDE order affect the convergence of PINNs?** *Changhoon Song, Yesom Park, Myungjoo Kang*, NeurIPS, 2024. [[paper](https://neurips.cc/virtual/2024/poster/96377)]
- **PINNacle: A Comprehensive Benchmark of Physics-Informed Neural Networks for Solving PDEs**,*Zhongkai Hao, Jiachen Yao, Chang Su, Hang Su, Ziao Wang, Fanzhi Lu, Zeyu Xia, Yichi Zhang, Songming Liu, Lu Lu, Jun Zhu*, NeurIPS,2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/8c63299fb2820ef41cb05e2ff11836f5-Abstract-Datasets_and_Benchmarks_Track.html)] [[code](https://github.com/i207M/PINNacle)]
- **The Challenges of the Nonlinear Regime for Physics-Informed Neural Networks**,*Andrea Bonfanti, Giuseppe Bruno, Cristina Cipriani*,NeurIPS,2024. [[paper]([The Challenges of the Nonlinear Regime for Physics-Informed Neural Networks](https://proceedings.neurips.cc/paper_files/paper/2024/hash/49f07f600ca532a89ef4fa0618bb78c1-Abstract-Conference.html))]

### **Neural Operator神经算子法**

- **An operator preconditioning perspective on training in physics-informed machine learning**,Tim De Ryck, Florent Bonnet,Siddhartha Mishra,Emmanuel de Bézenac,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/18473)]

- **ClimODE: Climate and Weather Forecasting with Physics-informed Neural ODEs**,Yogesh Verma,Markus Heinonen,Vikas Garg,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/17438)] [[code](https://github.com/Aalto-QuML/ClimODE)]

- **Solving High Frequency and Multi-Scale PDEs with Gaussian Processes**,Shikai Fang,Madison Cooley,Da Long, Shibo Li,Mike Kirby,Shandian Zhe,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/17752)] [[code](https://github.com/xuangu-fang/Gaussian-Process-Slover-for-High-Freq-PDE)]

- **BENO: Boundary-embedded Neural Operators for Elliptic PDEs**,Haixin Wang,Jiaxin Li,Anubhav Dwivedi, Kentaro Hara, Tailin Wu.ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/18389)] [[code](https://github.com/AI4Science-WestlakeU/beno)]

- **Better Neural PDE Solvers Through Data-Free Mesh Movers**,Peiyan Hu,Yue Wang,Zhi-Ming Ma,ICLR,2024. [[paper]([https://iclr.cc/virtual/2024/poster/18088)] [[code](https://github.com/Peiyannn/MM-PDE)]
- **Guaranteed Approximation Bounds for Mixed-Precision Neural Operators**,Renbo Tu,Colin White,Jean Kossaifi,Boris Bonev,Gennady Pekhimenko,Kamyar Azizzadenesheli,anima anandkumar,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/18680)] [[code](https://github.com/neuraloperator/neuraloperator)]

- **Learning semilinear neural operators: A unified recursive framework for prediction and data assimilation**, Ashutosh Singh,Ricardo Borsoi,Deniz Erdogmus,Tales Imbiriba,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/18401)] [[code](https://github. com/singh17ashu/NODA-Neural-Operator-with-Data-Assimilation)] // GitHub有给但是打不开

- **MgNO: Efficient Parameterization of Linear Operators via Multigrid**,Juncai He,Xinliang Liu,Jinchao Xu, ICLR, 2024. [[paper](https://iclr.cc/virtual/2024/poster/19328)] [[code](https://github.com/xlliu2017/MgNO)]

- **Accelerating Data Generation for Neural Operators via Krylov Subspace Recycling**,Hong Wang,Zhongkai Hao,Jie Wang,Zijie Geng,Zhen Wang,Bin Li,Feng Wu,ICLR,2024. [[paper](https://iclr.cc/virtual/2024/poster/18516)] [[code](https://github.com/wanghong1700/NO-DataGen-SKR)]

- **PhyMPGN: Physics-encoded Message Passing Graph Network for spatiotemporal PDE systems**,Bocheng Zeng,Qi Wang,Mengtao Yan,Yang Liu,Ruizhi Chengze,Yi Zhang,Hongsheng Liu,Zidong Wang,Hao Sun,ICLR,2025. [[paper](https://arxiv.org/pdf/2410.01337)] [[code](https://github.com/intell-sci-comput/PhyMPGN)] // 代码没有放出来

- **Text2PDE: Latent Diffusion Models for Accessible Physics Simulation**,Anthony Zhou,Zijie Li,Michael Schneier, John Buchanan,Amir Barati Farimani,ICLR,2025.[[paper](https://arxiv.org/pdf/2410.01153)] [[code](https://github.com/anthonyzhou-1/ldm_pdes)]

- **Boundary constrained Gaussian processes for robust physics-informed machine learning of linear partial differential equations**,David Dalton,Alan Lazarus,Hao Gao,Dirk Husmeier,ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/31382)] [[code](https://github.com/dodaltuin/jax-pigp)]

- **PRDP: Progressively Refined Differentiable Physics**,Kanishk Bhatia,Felix Koehler,Nils Thuerey,ICLR,2025. [[paper](https://arxiv.org/pdf/2502.19611)] [[code](https://github.com/tum-pbs/PRDP)]

- **Physics-Informed Deep Inverse Operator Networks for Solving PDE Inverse Problems**,Sung Woong Cho, Hwijae Son,ICLR,2025. [[paper](https://arxiv.org/pdf/2412.03161)]
- **Fengbo: a Clifford Neural Operator pipeline for 3D PDEs in Computational Fluid Dynamics**,Alberto Pepe, Mattia Montanari,Joan Lasenby,ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/29396)]

- **Active Learning for Neural PDE Solvers**,Daniel Musekamp,Marimuthu Kalimuthu,David Holzmüller,Makoto Takamoto,Mathias Niepert,ICLR,2025.[[paper](https://arxiv.org/pdf/2408.01536)] [[code](https://github.com/dmusekamp/al4pde)]

- **GridMix: Exploring Spatial Modulation for Neural Fields in PDE Modeling**,Honghui Wang,Shiji Song,Gao Huang.ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/30317)]

- **SINGER: Stochastic Network Graph Evolving Operator for High Dimensional PDEs**,Mingquan Feng,Yixin Huang,Weixin Liao,Yuhong Liu,Yizhou Liu,Junchi Yan,ICLR,2025. [[paper](https://openreview.net/forum?id=wVADj7yKee)] [[code](https://github.com/FengMingquan-sjtu/SINGER?tab=readme-ov-file)]

- **Wavelet Diffusion Neural Operator**,Peiyan Hu,Rui Wang,Xiang Zheng,Tao Zhang,Haodong Feng,Ruiqi Feng,Long Wei,Yue Wang,Zhi-Ming Ma,Tailin Wu,ICLR,2025.[[paper](https://arxiv.org/pdf/2412.04833)] [[code](https://github.com/AI4Science-WestlakeU/wdno)]

- **Sensitivity-Constrained Fourier Neural Operators for Forward and Inverse Problems in Parametric Differential Equations**,Abdolmehdi Behroozi,Chaopeng Shen,Daniel Kifer,ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/30461)]

- **Lie Algebra Canonicalization: Equivariant Neural Operators under arbitrary Lie Groups**,Zakhar Shumaylov, Peter Zaika,James Rowbottom,Ferdia Sherry,Melanie Weber,Carola-Bibiane Schönlieb,ICLR,2025.[[paper](https://arxiv.org/pdf/2410.02698)]

- **Spectral-Refiner: Accurate Fine-Tuning of Spatiotemporal Fourier Neural Operator for Turbulent Flows**,Shuhao Cao,Francesco Brarda,Ruipeng Li,Yuanzhe Xi,LCLR,2025. [[paper](https://arxiv.org/pdf/2405.17211)] [[code](https://github.com/scaomath/torch-cfd)]

- **Learning vector fields of differential equations on manifolds with geometrically constrained operator-valued kernels**,Daning Huang,Hanyang He,John Harlim,Yan Li,ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/29790)]

- **Discretization-invariance? On the Discretization Mismatch Errors in Neural Operators**,Wenhan Gao, Ruichen Xu,Yuefan Deng,Yi Liu,ICLR,2025. [[paper](https://iclr.cc/virtual/2025/poster/30126)]

- **Generalizable Motion Planning via Operator Learning**,Sharath Matada,Luke Bhan,Yuanyuan Shi,Nikolay Atanasov,ICLR,2025. [[paper](https://arxiv.org/pdf/2410.17547)] [[code](https://github.com/ExistentialRobotics/PNO)] //打不开代码

- **Quantitative Approximation for Neural Operators in Nonlinear Parabolic Equations**,Takashi Furuya,Koichi Taniguchi,Satoshi Okuda,ICLR,2025 [[paper](https://arxiv.org/pdf/2410.02151)]

- **Neural operators meet conjugate gradients: The FCG-NO method for efficient PDE solving**,Alexander Rudikov, Vladimir Fanaskov, Ekaterina Muravleva, Yuri M. Laevsky, Ivan Oseledets,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/34406)] [[code](https://github.com/arudikov/FCG-NO)]

- **Reference Neural Operators: Learning the Smooth Dependence of Solutions of PDEs on Geometric Deformations**,Ze Cheng, Zhongkai Hao, Xiaoqiang Wang, Jianing Huang, Youjia Wu, Xudan Liu, Yiru Zhao, Songming Liu, Hang Su,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/34670)] 

- **DPOT: Auto-Regressive Denoising Operator Transformer for Large-Scale PDE Pre-Training**,Zhongkai Hao, Chang Su, Songming Liu, Julius Berner, Chengyang Ying, Hang Su, Anima Anandkumar, Jian Song, Jun Zhu,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/33838)] [[code](https://github.com/thu-ml/DPOT)]

- **Using Uncertainty Quantification to Characterize and Improve Out-of-Domain Learning for PDEs**,S Chandra Mouli, Danielle C. Maddix, Shima Alizadeh, Gaurav Gupta, Andrew Stuart, Michael W. Mahoney, Bernie Wang,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/33787)] [[code](https://github.com/amazon-science/operator-probconserv)]

- **Accelerating PDE Data Generation via Differential Operator Action in Solution Space**,Huanshuo Dong, Hong Wang, Haoyang Liu, Jian Luo, Jie Wang,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/34521)] [[code](https://github.com/hs-dong/DiffOAS)]

- **Graph Neural PDE Solvers with Conservation and Similarity-Equivariance**,Masanobu Horie, Naoto Mitsume,ICML,2024.  [[paper](https://icml.cc/virtual/2024/poster/33858)] [[code](https://github.com/yellowshippo/fluxgnn-icml2024)]
- **Harnessing the Power of Neural Operators with Automatically Encoded Conservation Laws**,Ning Liu, Yiming Fan, Xianyi Zeng, Milan Klöwer, Lu Zhang, Yue Yu ,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/33964)] [[code](https://github.com/ningliu-iga/clawNO)]
- **Operator SVD with Neural Networks via Nested Low-Rank Approximation**,Jongha Jon Ryu, Xiangxiang Xu, Hasan Sabri Melihcan Erol, Yuheng Bu, Lizhong Zheng, Gregory W. Wornell,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/33002)] [[code](https://github.com/jongharyu/neural-svd)]

- **Hierarchical Neural Operator Transformer with Learnable Frequency-aware Loss Prior for Arbitrary-scale Super-resolution**，Xihaier Luo, Xiaoning Qian, Byung-Jun Yoon,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/34275)]

- **Equivariant Graph Neural Operator for Modeling 3D Dynamics**,Minkai Xu, Jiaqi Han, Aaron Lou, Jean Kossaifi, Arvind Ramanathan, Kamyar Azizzadenesheli, Jure Leskovec, Stefano Ermon, Anima Anandkumar,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/33544)] [[code](https://github.com/MinkaiXu/egno)]
- **Neural Operators with Localized Integral and Differential Kernels**,Neural Operators with Localized Integral and Differential Kernels,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/32773)] [[code](https://github.com/neuraloperator/neuraloperator)]

- **Positional Knowledge is All You Need: Position-induced Transformer (PiT) for Operator Learning**,Junfeng Chen, Kailiang Wu,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/33916)] [[code](https://github.com/junfeng-chen/position_induced_transformer)]

- **Improved Operator Learning by Orthogonal Attention**,Zipeng Xiao, Zhongkai Hao, Bokai Lin, Zhijie Deng, Hang Su,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/34901)] 

- **Implicit Representations via Operator Learning**,Sourav Pal, Harshavardhan Adepu, Clinton Wang, Polina Golland, Vikas Singh,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/35103)] [[code](https://github.com/vsingh-group/oinr)]

- **Beyond Regular Grids: Fourier-Based Neural Operators on Arbitrary Domains**,Beyond Regular Grids: Fourier-Based Neural Operators on Arbitrary Domains,ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/33684)] [[code](https://github.com/camlab-ethz/DSE-for-NeuralOperators)]

- **HAMLET: Graph Transformer Neural Operator for Partial Differential Equations**,Andrey Bryutkin, Jiahao Huang, Zhongying Deng, Guang Yang, Carola-Bibiane Schönlieb, Angelica I Aviles-Rivero,ICML,2024.[[paper](https://icml.cc/virtual/2024/poster/33118)] 

- **Gaussian Plane-Wave Neural Operator for Electron Density Estimation**,Seongsu Kim, Sungsoo Ahn, ICML,2024. [[paper](https://icml.cc/virtual/2024/poster/33959)] [[code]([https://github.com/seongsukim-ml/GPWNO)]

- **Stochastic Taylor Derivative Estimator: Efficient amortization for arbitrary differential operators**，Zekun Shi,Zheyuan Hu,Min Lin,Kenji Kawaguchi,NeurIPS,2024. [[paper](https://nips.cc/virtual/2024/oral/97986)] [[code](https://github.com/sail-sg/stde)]

- **Optimal deep learning of holomorphic operators between Banach spaces**,*Ben Adcock, Nick Dexter, Sebastian Moraga*, NeurIPS,2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/3100d29d662360bb1a40a5ded8e100ae-Abstract-Conference.html)] 
- **Nonlocal Attention Operator: Materializing Hidden Knowledge Towards Interpretable Physics Discovery**, *Yue Yu, Ning Liu, Fei Lu, Tian Gao, Siavash Jafarzadeh, Stewart Silling*, NeurIPS, 2024.  [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ce5b4f79f4752b7f8e983a80ebcd9c7a-Abstract-Conference.html)] [[code](https://github.com/fishmoon1234/NAO)]

- **Learning to Predict Structural Vibrations**,*Jan van Delden, Julius Schultz, Christopher Blech, Sabine C. Langer, Timo Lüddecke*, NeurIPS,2024. [[paper](https://nips.cc/virtual/2024/poster/94031)] [[code](https://github.com/ecker-lab/Learning_Vibrating_Plates)]
- **PACE: Pacing Operator Learning to Accurate Optical Field Simulation for Complicated Photonic Devices**, *Hanqing Zhu, Wenyan Cong, Guojin Chen, Shupeng Ning, Ray T. Chen, Jiaqi Gu, David Z. Pan*,NeurIPS,2024. [[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/7cc16e8635e6f27c295355bd214ef8d8-Abstract-Conference.html)] [[code](https://github.com/zhuhanqing/PACE-Light)]
- **Latent Neural Operator for Solving Forward and Inverse PDE Problems**,*Tian Wang, Chuang Wang*, NeurIPS, 2024. [[paper](https://nips.cc/virtual/2024/poster/94908)] [[code](https://github.com/L-I-M-I-T/LatentNeuralOperator)]

- **Can neural operators always be continuously discretized?** ,*Takashi Furuya, Michael Puthawala, Maarten V. de Hoop, Matti Lassas*,NeurIPS,2024.[[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b31f6d65f2584b3c4347148db36fe07f-Abstract-Conference.html)] 
- **Amortized Fourier Neural Operators**,*Zipeng Xiao, Siqi Kou, Zhongkai Hao, Bokai Lin, Zhijie Deng*,NeurIPS,2024.[[paper](https://neurips.cc/virtual/2024/poster/94587)]
- **Pretraining Codomain Attention Neural Operators for Solving Multiphysics PDEs**,Md Ashiqur Rahman, Robert Joseph George, Mogab Elleithy, Daniel Leibovici, Zongyi Li, Boris Bonev, Colin White, Julius Berner, Raymond A. Yeh, Jean Kossaifi, Kamyar Azizzadenesheli, Anima Anandkumar,NeurIPS,2024. [[paper](https://neurips.cc/virtual/2024/poster/93155)] [[code](https://github.com/neuraloperator/CoDA-NO)]
- **Universal Physics Transformers: A Framework For Efficiently Scaling Neural Operators**, *Benedikt Alkin, Andreas Fürst, Simon Schmid, Lukas Gruber, Markus Holzleitner, Johannes Brandstetter*, NeurIPS,2024[[paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/2cd36d327f33d47b372d4711edd08de0-Abstract-Conference.html)] [[code](https://ml-jku.github.io/UPT/)]
