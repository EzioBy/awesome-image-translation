# Image Restoration and Enhancement

## Table of Contents
- [Team](#team)
- [Exemplar-Guided](#with-exemplar)
- [Unpaired or Misaligned Data](#with-unpaired-or-misaligned-data)
- [Replacing ISP](#replacing-isp)
- [NAS and AutoML](#nas-and-automl)
- [Misc](#misc)
- [Challenge and Survey](#challenge-and-survey)

## Team

[GenForce](https://genforce.github.io): Research Initiative on Generative Modeling at CUHK.

## Replacing ISP

**Rendering Natural Camera Bokeh Effect with Deep Learning.**<br>
*Andrey Ignatov, Jagruti Patel, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.05698)] [[Project](http://people.ee.ethz.ch/~ihnatova/pynet-bokeh.html)] [[Everything is Better with Bokeh!  Dataset](https://competitions.codalab.org/competitions/24716)]

**PyNET: Replacing Mobile Camera ISP with a Single Deep Learning Model.**<br>
*Andrey Ignatov, Luc Van Gool, Radu Timofte.*<br>
CVPRW 2020. [[PDF](https://arxiv.org/abs/2002.05509)] [[Project](http://people.ee.ethz.ch/~ihnatova/pynet.html)] [[Official PyTorch](https://github.com/aiff22/PyNET-PyTorch)] [[Official TensorFlow](https://github.com/aiff22/PyNET)]

**DSLR-Quality Photos on Mobile Devices with Deep Convolutional Networks.**<br>
*Andrey Ignatov, Nikolay Kobyshev, Radu Timofte, Kenneth Vanhoey, Luc Van Gool.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1704.02470)] [[Github](https://github.com/aiff22/DPED)] [[Project](http://people.ee.ethz.ch/~ihnatova/index.html)]

**WESPE: Weakly Supervised Photo Enhancer for Digital Cameras.**<br>
*Andrey Ignatov, Nikolay Kobyshev, Radu Timofte, Kenneth Vanhoey, Luc Van Gool.*<br>
CVPRW 2018. [[PDF](https://arxiv.org/abs/1709.01118)][[Project](http://people.ee.ethz.ch/~ihnatova/wespe.html)]

**Single-Image HDR Reconstruction by Learning to Reverse the Camera Pipeline.**<br>
*[Yu-Lun Liu](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/), Wei-Sheng Lai, Yu-Sheng Chen, Yi-Lung Kao, Ming-Hsuan Yang, Yung-Yu Chuang, Jia-Bin Huang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01179)] [[Github](https://github.com/alex04072000/SingleHDR)] [[Project](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/SingleHDR)]

**Deep White-Balance Editing.**<br>
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), Michael S. Brown.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01354)] [[Github](https://github.com/mahmoudnafifi/Deep_White_Balance)]

## Exemplar-Guided

**Learning Texture Transformer Network for Image Super-Resolution.**<br>
*Fuzhi Yang, Huan Yang, Jianlong Fu, Hongtao Lu, Baining Guo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.04139)] [[Github](https://github.com/FuzhiYang/TTSR)]

**Instance-aware Image Colorization.**<br>
*Jheng-Wei Su, Hung-Kuo Chu, Jia-Bin Huang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.10825)] [[Github](https://ericsujw.github.io/InstColorization/)] [[Project](https://ericsujw.github.io/InstColorization/)]

**Unsupervised Real Image Super-Resolution via Generative Variational AutoEncoder.**<br>
*Zhi-Song Liu, Wan-Chi Siu, Li-Wen Wang, Chu-Tak Li, Marie-Paule Cani, Yui-Lam Chan.*<br>
CVPR 2020 Workshop NTIRE. [[PDF](https://arxiv.org/abs/2004.12811)] [[Github](https://github.com/Holmes-Alan/dSRVAE)] [[NTIRE2020 Real Image Super-Resolution Challenge](https://data.vision.ee.ethz.ch/cvl/ntire20/)]

**SRTNN: Image Super-Resolution by Neural Texture Transfer.**<br>
*[Zhifei Zhang](https://zzutk.github.io/), Zhaowen Wang, Zhe Lin, Hairong Qi.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.00834)] [[Project](http://web.eecs.utk.edu/~zzhang61/project_page/SRNTT/SRNTT.html)] [[Github](https://github.com/ZZUTK/SRNTT)]

**CrossNet: An End-to-end Reference-based Super Resolution Network using Cross-scale Warping.**<br>
*Haitian Zheng, Mengqi Ji, Haoqian Wang, Yebin Liu, Lu Fang.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.10547)]

**Deep Exemplar-Based Video Colorization.**<br>
*Bo Zhang, Mingming He, Jing Liao, Pedro V. Sander, Lu Yuan, Amine Bermak, Dong Chen.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deep_Exemplar-Based_Video_Colorization_CVPR_2019_paper)]

**Deep Exemplar-based Colorization.**<br>
*Mingming He, [Dongdong Chen](http://www.dongdongchen.bid/), [Jing Liao](https://liaojing.github.io/html/index.html), Pedro V. Sander, Lu Yuan.*<br>
Siggraph 2018. [[PDF](https://arxiv.org/abs/1807.06587)] [[Github](https://github.com/msracver/Deep-Exemplar-based-Colorization)]

**Progressive Color Transfer with Dense Semantic Correspondences.**<br>
*Mingming He, Jing Liao, Dongdong Chen, Lu Yuan, Pedro V Sander.*<br>
ACM TOG 2018.[[PDF](https://arxiv.org/pdf/1710.00756.pdf)]

**Recovering Realistic Texture in Image Super-resolution by Deep Spatial Feature Transform.**<br>
*[Xintao Wang](https://xinntao.github.io/), [Ke Yu](https://yuke93.github.io/), [Chao Dong](https://scholar.google.com.hk/citations?user=OSDCB0UAAAAJ&hl=en), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/).*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1804.02815)] [[Project](http://mmlab.ie.cuhk.edu.hk/projects/SFTGAN/)] [[Github](https://github.com/xinntao/SFTGAN)] [[BasicSR](https://github.com/xinntao/BasicSR)] [[HandyViewer](https://github.com/xinntao/HandyViewer)]

**The Unreasonable Effectiveness of Texture Transfer for Single Image Super-resolution.**<br>
*Muhammad Waleed Gondal, Bernhard Schölkopf, Michael Hirsch.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1808.00043)] [[Github](https://github.com/waleedgondal/Texture-based-Super-Resolution-Network)]

**Learned Multi-View Texture Super-Resolution.**<br>
*Audrey Richard, Ian Cherabier, Martin R. Oswald, Vagia Tsiminaki, Marc Pollefeys, Konrad Schindler.*<br>
3DV 2019. [[PDF](https://arxiv.org/abs/2001.04775)]

## Unpaired or Misaligned Data

**Unfolding the Alternating Optimization for Blind Super Resolution.**<br>
*Zhengxiong Luo, Yan Huang, Shang Li, Liang Wang, Tieniu Tan.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.02631)] [[Github](https://github.com/greatlog/DAN.git)]

**Learning Image-adaptive 3D Lookup Tables for High Performance Photo Enhancement in Real-time.**<br>
*Hui Zeng, Jianrui Cai, Lida Li, Zisheng Cao, Lei Zhang.*<br>
TPAMI 2020. [[PDF](https://www4.comp.polyu.edu.hk/~cslzhang/paper/PAMI_LUT.pdf)] [[Github](https://github.com/HuiZeng/Image-Adaptive-3DLUT)] [[Dataset](https://connectpolyu-my.sharepoint.com/:f:/g/personal/16901447r_connect_polyu_hk/EqNGuQUKZe9Cv3fPG08OmGEBbHMUXey2aU03E21dFZwJyg?e=QNCMMZ)]

**Blind Image Restoration with Flow Based Priors.**<br> 
*Leonhard Helminger, Michael Bernasconi, Abdelaziz Djelouah, Markus Gross, Christopher Schroers.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.04583)]

**NTGAN: Learning Blind Image Denoising without Clean Reference.**<br> 
*Rui Zhao, Daniel P.K. Lun, Kin-Man Lam.*<br> 
BMVC 2020. [[PDF](https://arxiv.org/abs/2009.04286)]

**Blind Face Restoration via Deep Multi-scale Component Dictionaries.**<br> 
*Xiaoming Li, Chaofeng Chen, Shangchen Zhou, Xianhui Lin, Wangmeng Zuo, Lei Zhang.*<br> 
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540375.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540375-supp.pdf)]

**Unpaired Learning of Deep Image Denoising.**<br>
*Xiaohe Wu, Ming Liu, Yue Cao, Dongwei Ren, Wangmeng Zuo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.13711)]

**Dehaze-GLCGAN: Unpaired Single Image De-hazing via Adversarial Training.**<br>
*Zahra Anvari, Vassilis Athitsos.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.06632)]

**Component Divide-and-Conquer for Real-World Image Super-Resolution.**<br>
*Pengxu Wei, Ziwei Xie, Hannan Lu, Zongyuan Zhan, Qixiang Ye, Wangmeng Zuo, Liang Lin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.01928)] [[Github](https://github.com/xiezw5/Component-Divide-and-Conquer-for-Real-World-Image-Super-Resolution)]

**From Shadow Segmentation to Shadow Removal.**<br>
*Hieu Le, Dimitris Samaras.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.00267)] [[Github](https://www3.cs.stonybrook.edu/~cvl/projects/FSS2SR/index.html)]

**DBSN: Unpaired Learning of Deep Image Denoising.**<br>
*Xiaohe Wu, Ming Liu, Yue Cao, Dongwei Ren, Wangmeng Zuo.*<br>
ECCV 2020. [[PDF](https://github.com/XHWXD/DBSN)]

**Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement.**<br>
*Chunle Guo, Chongyi Li, Jichang Guo, Chen Change Loy, Junhui Hou, Sam Kwong, Runmin Cong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2001.06826)] [[Github](https://github.com/Li-Chongyi/Zero-DCE)]

**Unpaired Image Super-Resolution using Pseudo-Supervision.**<br>
*Shunta Maeda.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11397)]

**Domain Adaptation for Image Dehazing.**<br>
*Yuanjie Shao, Lerenhan Li, Wenqi Ren, Changxin Gao, Nong Sang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.04668)]

**Unsupervised Real-world Low-light Image Enhancement with Decoupled Networks.**<br>
*Wei Xiong, Ding Liu, Xiaohui Shen, Chen Fang, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.02818)]

**SimUSR: A Simple but Strong Baseline for Unsupervised Image Super-resolution.**<br>
*Namhyuk Ahn, Jaejun Yoo, Kyung-Ah Sohn.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.11020)]

**Weakly Aligned Joint Cross-Modality Super Resolution.**<br>
*Guy Shacht, Sharon Fogel, Dov Danon, Daniel Cohen-Or.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.09965)]

**Unsupervised Real-world Image Super Resolution via Domain-distance Aware Training.**<br>
*Yunxuan Wei, [Shuhang Gu](https://shuhanggu.github.io/), Yawei Li, Longcun Jin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2004.01178)] [[Github](https://github.com/ShuhangGu/DASR)]

**Robust Image Reconstruction with Misaligned Structural Information.**<br>
*Leon Bungert, Matthias J. Ehrhardt.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00589)]

**Closed-loop Matters: Dual Regression Networks for Single Image Super-Resolution.**<br>
*Yong Guo, Jian Chen, Jingdong Wang, Qi Chen, Jiezhang Cao, Zeshuai Deng, Yanwu Xu, Mingkui Tan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.07018)]

**Learning Invariant Representation for Unsupervised Image Restoration.**<br>
*Wenchao Du, Hu Chen, Hongyu Yang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12769)]

**Meta-Transfer Learning for Zero-Shot Super-Resolution.**<br>
*Jae Woong Soh, Sunwoo Cho, Nam Ik Cho.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.12213)]

**EnlightenGAN: Deep Light Enhancement without Paired Supervision.**<br>
*Yifan Jiang, Xinyu Gong, Ding Liu, Yu Cheng, Chen Fang, Xiaohui Shen, Jianchao Yang, Pan Zhou, Zhangyang Wang.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1906.06972)] [[Github](https://github.com/TAMU-VITA/EnlightenGAN)] [[Dataset](https://github.com/TAMU-VITA/EnlightenGAN/issues/28)] [[KinD](https://arxiv.org/abs/1905.04161)]

**Unpaired Image Enhancement Featuring Reinforcement-Learning-Controlled Image Editing Software.**<br>
*Satoshi Kosugi, Toshihiko Yamasaki.* <br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1912.07833)]

**Single Image Reflection Removal Exploiting Misaligned Training Data and Network Enhancements.**<br>
*Kaixuan Wei, Jiaolong Yang, Ying Fu, David Wipf, Hua Huang.* <br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.00637)] [[Project](https://github.com/Vandermode/ERRNet)]

**Unpaired Image Enhancement Featuring Reinforcement-Learning-Controlled Image Editing Software.**<br>
*Kosugi, Toshihiko Yamasaki.*<br>
arxiv, 2019. [[PDF](https://arxiv.org/pdf/1912.07833.pdfSatoshi)]

**Deep Photo Enhancer: Unpaired Learning for Image Enhancement from Photographs with GANs.**<br>
*Yu-Sheng Chen, Yu-Ching Wang, Man-Hsin Kao, Yung-Yu Chuang.*<br>
CVPR 2018. [[PDF](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/CVPR-2018-DPE.pdf)] [[Supplementary Material](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/CVPR-2018-DPE-sm-compress.pdf)] [[Demo](http://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/)] [[Github](https://github.com/nothinglo/Deep-Photo-Enhancer)]  [[MIT-Adobe FiveK Dataset](https://data.csail.mit.edu/graphics/fivek/)] [[DSLR Photo Enhancement Dataset](http://people.ee.ethz.ch/~ihnatova/#demo)]

**PPN2V: Fully Unsupervised Probabilistic Noise2Void.**<br>
*Mangal Prakash, Manan Lalit, Pavel Tomancak, Alexander Krull, Florian Jug.*<br>
arxiv, 27 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12291)] [[GitHub](https://github.com/juglab/ppn2v)] [[MPI-CBG: Max-Planck Institute of Molecular Cell Biology and Genetics](https://www.mpi-cbg.de/home/)]

**PN2V:Probabilistic Noise2Void: Unsupervised Content-Aware Denoising.**<br>
*Alexander Krull, Tomas Vicar, Florian Jug.*<br>
arxiv, 3 Jun 2019. [[PDF](https://arxiv.org/abs/1906.00651)] [[Github](https://github.com/juglab/pn2v)]

## Deep Image Prior 

**Unsupervised Hyperspectral Mixed Noise Removal Via Spatial-Spectral Constrained Deep Image Prior.**<br>
*Yi-Si Luo, Xi-Le Zhao, Tai-Xiang Jiang, Yu-Bang Zheng, Yi Chang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.09753)]

**The Hessian Penalty: A Weak Prior for Unsupervised Disentanglement.**<br>
*William Peebles, John Peebles, Jun-Yan Zhu, Alexei Efros, Antonio Torralba.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.10599)] [[Poject](https://www.wpeebles.com/hessian-penalty)] [[Github](https://github.com/wpeebles/hessian_penalty)]

**NAS-DIP: Learning Deep Image Prior with Neural Architecture Search.**<br>
*Yun-Chun Chen, Chen Gao, Esther Robb, Jia-Bin Huang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.11713)] [[Poject](https://yunchunchen.github.io/NAS-DIP/)] [[Github](https://github.com/YunChunChen/NAS-DIP-pytorch)]

**Exploiting Deep Generative Prior for Versatile Image Restoration and Manipulation.**<br>
*Xingang Pan, Xiaohang Zhan, Bo Dai, Dahua Lin, Chen Change Loy, Ping Luo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.13659)] [[Github](https://github.com/XingangPan/deepgenerative-prior)]

**Semantic Photo Manipulation with a Generative Image Prior.**<br>
*David Bau, Hendrik Strobelt, William Peebles, Jonas, Bolei Zhou, Jun-Yan Zhu, Antonio Torralba.*<br>
SIGGRAPH 2019. [[PDF](https://arxiv.org/abs/2005.07727)]

**PriorGAN: Real Data Prior for Generative Adversarial Nets.**<br>
*Shuyang Gu, Jianmin Bao, Dong Chen, Fang Wen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16990)]

**CDVD-TSP: Cascaded Deep Video Deblurring Using Temporal Sharpness Prior.**<br>
*Jinshan Pan, Haoran Bai, Jinhui Tang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02501)] [[Github](https://github.com/csbhr/CDVD-TSP)]

**Attention Prior for Real Image Restoration.**<br>
*Saeed Anwar, Nick Barnes, Lars Petersson.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.13524)]

## NAS and AutoML

**NAS-DIP: Learning Deep Image Prior with Neural Architecture Search.**<br>
*Yun-Chun Chen, Chen Gao, Esther Robb, Jia-Bin Huang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.11713)] [[Poject](https://yunchunchen.github.io/NAS-DIP/)] [[Github](https://github.com/YunChunChen/NAS-DIP-pytorch)]

**Efficient Residual Dense Block Search for Image Super-Resolution.**<br>
*Dehua Song, Chang Xu, Xu Jia, Yiyi Chen, Chunjing Xu, [Yunhe Wang](www.wangyunhe.site).*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1909.11409)] [[Github](https://github.com/huawei-noah/vega)]

**CLEARER: Multi-Scale Neural Architecture Search for Image Restoration.**<br>
*Yuanbiao Gou, Boyun Li, Zitao Liu, Songfan Yang, Xi Peng.*<br>
NeurIPS 2020. [[PDF]()]

## Misc

**Self-Adaptively Learning to Demoiré from Focused and Defocused Image Pairs.**<br>
*Lin Liu, Shanxin Yuan, Jianzhuang Liu, Liping Bao, Gregory Slabaugh, Qi Tian.*<br>
NeurIPS 2020. [[PDF]()]

**UnModNet: Learning to Unwrap a Modulo Image for High Dynamic Range Imaging.**<br>
*Chu Zhou, Hang Zhao, Jin Han, Chang Xu, Chao Xu, Tiejun Huang, Boxin Shi.*<br>
NeurIPS 2020. [[PDF]()]

**Cross-scale Internal Graph Convolution Network for Image Super-Resolution.**<br>
*Shangchen Zhou, Jiawei Zhang, Wangmeng Zuo, Chen Change Loy.*<br>
NeurIPS 2020. [[PDF]()]

**Noise2Same: Optimizing A Self-Supervised Bound for Image Denoising.**<br>
*Yaochen Xie, Zhengyang Wang, Shuiwang Ji.*<br>
NeurIPS 2020. [[PDF]()]

**Neural Sparse Representation for Image Restoration.**<br>
*Yuchen Fan, Jiahui Yu, Yiqun Mei, Yulun Zhang, Yun Fu, Ding Liu, Thomas Huang.*<br>
NeurIPS 2020. [[PDF]()]

**Deep Wiener Deconvolution: Wiener Meets Deep Learning for Image Deblurring.**<br>
*Jiangxin Dong, Stefan Roth, Bernt Schiele.*<br>
NeurIPS 2020. [[PDF]()]

**Efficient Image Super-Resolution Using Pixel Attention.**<br>
*Hengyuan Zhao, Xiangtao Kong, Jingwen He, Yu Qiao, Chao Dong.*<br>
ECCVW 2020. [[PDF]((https://arxiv.org/abs/2010.01073)]

**Deformable Kernel Convolutional Network for Video Extreme Super-Resolution.**<br>
*Xuan Xu, Xin Xiong, Jinge Wang, Xin Li.*<br>
ECCVW 2020. [[PDF](https://arxiv.org/abs/2010.00154)]

**Texture-aware Multi-resolution Image Inpainting.**<br>
*Mohamed Abbas Hedjazi, Yakup Genc.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.14721)]

**Blind Video Temporal Consistency via Deep Video Prior.**<br>
NeurIPS 2020. [[Github](https://github.com/ChenyangLEI/deep-video-prior)]

**Texture Memory-Augmented Deep Patch-Based Image Inpainting.**<br> 
*Rui Xu, Minghao Guo, Jiaqi Wang, Xiaoxiao Li, Bolei Zhou, Chen Change Loy.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.13240)]

**Foreground-aware Semantic Representations for Image Harmonization.**<br> 
*Konstantin Sofiiuk, Polina Popenova, Anton Konushin.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.00809)] [[Github](https://github.com/saic-vul/image_harmonization)]

**Progressive Semantic-Aware Style Transformation for Blind Face Restoration.**<br>
*Chaofeng Chen, Xiaoming Li, Lingbo Yang, Xianhui Lin, Lei Zhang, Kwan-Yee K. Wong.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.08709)] [[Github](https://github.com/chaofengc/PSFRGAN)]

**FGVC: Flow-edge Guided Video Completion.**<br>
*Chen Gao, Ayush Saraf, Jia-Bin Huang, Johannes Kopf.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.01835)] [[Project](http://chengao.vision/FGVC/)] [[Github](https://github.com/vt-vl-lab/FGVC)]

**Ordered or Orderless: A Revisit for Video based Person Re-Identification.**<br>
*[Le Zhang](https://zhangleuestc.github.io/), Joey Tianyi Zhou, Ming-Ming Cheng, Yun Liu, Jia-Wang Bian, Zeng Zeng, Chunhua Shen.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/1912.11236)] [[Github](https://github.com/ZhangLeUestc/VideoReid-TPAMI2020)]

**HiFic: High-Fidelity Generative Image Compression.**<br>
*Fabian Mentzer, George Toderici, Michael schannen, Eirikur Agustsson.*<br>
arxiv 2020. [[Project](https://hific.github.io/)] [[Github](https://github.com/Justin-Tan/high-fidelity-generative-compression)]

**STEm-Seg: Spatio-temporal Embeddings for Instance Segmentation in Videos.**<br>
*Ali Athar, Sabarinath Mahadevan, Aljoša Ošep, Laura Leal-Taixé, Bastian Leibe.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.08429)] [[Github](https://github.com/sabarim/STEm-Seg)] [[Project](https://www.vision.rwth-aachen.de/publication/00202/)]

**Adversarial score matching and improved sampling for image generation.**<br>
*Alexia Jolicoeur-Martineau, Rémi Piché-Taillefer, Rémi Tachet des Combes, Ioannis Mitliagkas.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.05475)] [[Github](https://github.com/AlexiaJM/AdversarialConsistentScoreMatching)]

**High-Resolution Deep Image Matting.**<br>
*Haichao Yu, Ning Xu, Zilong Huang, Yuqian Zhou, Humphrey Shi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.06613)]

**Deep Detection for Face Manipulation.**<br>
*Disheng Feng, Xuequan Lu, Xufeng Lin.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2009.05934)]

**Short-Term and Long-Term Context Aggregation Network for Video Inpainting.**<br>
*Ang Li, Shanshan Zhao, Xingjun Ma, Mingming Gong, Jianzhong Qi, Rui Zhang, Dacheng Tao, Ramamohanarao Kotagiri.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.05721)]

**Attention Cube Network for Image Restoration.**<br>
*Yucheng Hang, Qingmin Liao, Wenming Yang, Yupeng Chen, Jie Zhou.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.05907)]

**Understanding Deformable Alignment in Video Super-Resolution.**<br> 
*Kelvin C.K. Chan, Xintao Wang, Ke Yu, Chao Dong, Chen Change Loy.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.07265)]

**Old Photo Restoration via Deep Latent Space Translation.**<br> 
*Ziyu Wan, Bo Zhang, Dongdong Chen, Pan Zhang, Dong Chen, Jing Liao, Fang Wen.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.07047)]

**WDRN : A Wavelet Decomposed RelightNet for Image Relighting.**<br> 
*Densen Puthussery, Hrishikesh P.S., Melvin Kuriakose, Jiji C.V.*<br> 
ECCVW 2020. [[PDF](https://arxiv.org/abs/2009.06678)]

**Learning a Single Model with a Wide Range of Quality Factors for JPEG Image Artifacts Removal.**<br> 
*Jianwei Li, Yongtao Wang, Haihua Xie, Kai-Kuang Ma.*<br> 
TIP 2020. [[PDF](https://arxiv.org/abs/2009.06912)]

**Conditional Sequential Modulation for Efficient Global Image Retouching.**<br> 
*Jingwen He, Yihao Liu, Yu Qiao, Chao Dong.*<br> 
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580664.pdf)]

**Deep Preset: Blending and Retouching Photos with Color Style Transfer.**<br>
*Man M. Ho, Jinjia Zhou.*<br>
arxiv 2020. [[]PDF(https://arxiv.org/abs/2007.10701)] [[Project](https://github.com/minhmanho/deep_preset)]

**Rain Rendering For Evaluating and Improving Robustness to Bad Weather.**<br>
*Maxime Tremblay, Shirsendu Sukanta Halder, Raoul de Charette, Jean-François Lalonde.*<br>
IJCV 2020. [[PDF](https://arxiv.org/abs/2009.03683)]

**Deep Cyclic Generative Adversarial Residual Convolutional Networks for Real Image Super-Resolution.**<br>
*Rao Muhammad Umer, Christian Micheloni.*<br>
ECCVW 2020. [[PDF](https://arxiv.org/abs/2009.03693)]

**Learning Flow-based Feature Warping for Face Frontalization with Illumination Inconsistent Supervision.**<br>  
*Yuxiang Wei, Ming Liu, Haolin Wang, Ruifeng Zhu, Guosheng Hu, Wangmeng Zuo.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570545.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570545-supp.pdf)]

**Face Super-Resolution Guided by 3D Facial Priors.**<br>  
*Xiaobin Hu, Wenqi Ren, John LaMaster, Xiaochun Cao, Xiaoming Li, Zechao Li, Bjoern Menze, Wei Liu.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490732.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490732-supp.pdf)]

**LatticeNet: Towards Lightweight Image Super-resolution with Lattice Block.**<br> 
*Xiaotong Luo, Yuan Xie, Yulun Zhang, Yanyun Qu, Cuihua Li, Yun Fu.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670273.pdf)]

**PIPAL: a Large-Scale Image Quality Assessment Dataset for Perceptual Image Restoration.**<br> 
*Jinjin Gu, Haoming Cai, Haoyu Chen, Xiaoxing Ye, Jimmy S. Ren, Chao Dong.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560613.pdf)]

**Stacking Networks Dynamically for Image Restoration Based on the Plug-and-Play Framework.**<br> 
*Haixin Wang, Tianhao Zhang, Muzhi Yu, Jinan Sun, Wei Ye, Chen Wang , Shikun Zhang.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580443.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580443-supp.zip)]

**Interactive Multi-Dimension Modulation with Dynamic Controllable Residual Learning for Image Restoration.**<br> 
*Jingwen He, Chao Dong, Yu Qiao.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650052.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650052-supp.pdf)]

**Learning Enriched Features for Real Image Restoration and Enhancement.**<br> 
*Syed Waqas Zamir, Aditya Arora, Salman Khan, Munawar Hayat, Fahad Shahbaz Khan, Ming-Hsuan Yang, Ling Shao.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700494.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700494-supp.pdf)]

**Low light video Enhancement using Synthetic Data Produced with an Intermediate Domain Mapping.**<br>
*Danai Triantafyllidou, Sean Moran, Steven McDonagh, Sarah Parisot, Gregory Slabaugh.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580103.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580103-supp.zip)]

**FHDe$^2$Net: Full High Definition Demoireing Network.**<br>
*Bin He, Ce Wang, Boxin Shi, Ling-Yu Duan.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670715.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670715-supp.pdf)]

**Event Enhanced High-Quality Image Recovery.**<br>
*Bishan Wang, Jingwei He, Lei Yu, Gui-Song Xia, Wen Yang.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580154.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580154-supp.pdf)]

**ChromaGAN: Adversarial Picture Colorization with Semantic Class Distribution.**<br>
*Patricia Vitoria, Lara Raad, Coloma Ballester.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/1907.09837)]

**PNEN: Pyramid Non-Local Enhanced Networks.**<br>
*Feida Zhu, Chaowei Fang, Kai-Kuang Ma.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2008.09742)]

**ALANET: Adaptive Latent Attention Network forJoint Video Deblurring and Interpolation.**<br>
*Akash Gupta, Abhishek Aich, Amit K. Roy-Chowdhury.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.01005)]

**Ultra Lightweight Image Super-Resolution with Multi-Attention Layers.**<br>
*Abdul Muqeet, Jiwon Hwang, Subin Yang, Jung Heum Kang, Yongwoo Kim, Sung-Ho Bae.*<br>
ECCVW AIM2020. [[PDF](https://arxiv.org/abs/2008.12912)]

**DALE : Dark Region-Aware Low-light Image Enhancement.**<br>
*Dokyeong Kwon, Guisik Kim, Junseok Kwon.*<br>
BMVC 2020. [[PDF](https://arxiv.org/abs/2008.12493)]

**HRVGAN: High Resolution Video Generation using Spatio-Temporal GAN.**<br>
*Abhinav Sagar.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.09646)]

**Image Colorization: A Survey and Dataset.**<br>
*Saeed Anwar, Muhammad Tahir, Chongyi Li, Ajmal Mian, Fahad Shahbaz Khan, Abdul Wahab Muzaffar.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.10774)] [[Github](https://github.com/saeed-anwar/ColorSurvey)]

**Exploit Camera Raw Data for Video Super-Resolution via Hidden Markov Model Inference.**<br>
*Xiaohong Liu, Kangdi Shi, Zhe Wang, Jun Chen.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2008.10710)]

**GAN Slimming: All-in-One GAN Compression by A Unified Optimization Framework.**<br>
*Haotao Wang, Shupeng Gui, Haichuan Yang, Ji Liu, Zhangyang Wang.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490052.pdf)] [[Github](https://github.com/VITA-Group/GAN-Slimming)]

**Deep Generative Model for Image Inpainting with Local Binary Pattern Learning and Spatial Attention.**<br>
*Haiwei Wu, Jiantao Zhou, Yuanman Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.01031)] [[Project](https://github.com/HighwayWu/ImageInpainting)]

**Flow-edge Guided Video Completion.**<br>
*Chen Gao, Ayush Saraf, Jia-Bin Huang, Johannes Kopf.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.01835)] [[Project](http://chengao.vision/FGVC/)]

**SRFlow: Learning the Super-Resolution Space with Normalizing Flow.**<br>
*Andreas Lugmayr, Martin Danelljan, Luc Van Gool, Radu Timofte.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2006.14200)] [[Github](http://git.io/SRFlow)]

**Delving Deeper into Anti-aliasing in ConvNets.**<br>
*Xueyan Zou, Fanyi Xiao, Zhiding Yu, Yong Jae Lee.*<br>
BMVC 2020. [[PDF](https://arxiv.org/abs/2008.09604)] [[Github](https://maureenzou.github.io/ddac/)]

**Image Stitching and Rectification for Hand-Held Cameras.**<br>
*Bingbing Zhuang, Quoc-Huy Tran.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.09229)] [[Project](https://www.nec-labs.com/~mas/RS-APAP)]

**LIRA: Lifelong Image Restoration from Unknown Blended Distortions.**<br>
*Jianzhao Liu, Jianxin Lin, Xin Li, Wei Zhou, Sen Liu, Zhibo Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.08242)]

**Single Image Super-Resolution via a Holistic Attention Network.**<br>
*Ben Niu, Weilei Wen, Wenqi Ren, Xiangde Zhang, Lianping Yang, Shuzhen Wang, Kaihao Zhang, Xiaochun Cao, Haifeng Shen.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/2008.08767)]

**FourFeat: Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains.**<br>
*Matthew Tancik, Pratul P. Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan T. Barron, Ren Ng.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.10739)] [[Project](https://people.eecs.berkeley.edu/~bmild/fourfeat/)]

**Can You Read Me Now? Content Aware Rectification using Angle Supervision.**<br>
*Amir Markovitz, Inbal Lavi, Or Perel, Shai Mazor, Roee Litman.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02231)]

**DeepGIN: Deep Generative Inpainting Network for Extreme Image Inpainting.**<br>
*Chu-Tak Li, Wan-Chi Siu, Zhi-Song Liu, Li-Wen Wang, Daniel Pak-Kong Lun.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.07173)]

**SRFlow: Learning the Super-Resolution Space with Normalizing Flow.**<br>
*Andreas Lugmayr, Martin Danelljan, Luc Van Gool, Radu Timofte.*<br>
ECCV 2020. [[PDF](http://de.arxiv.org/abs/2006.14200)] [[Github](https://github.com/andreas128/SRFlow)]

**F2GAN: Fusing-and-Filling GAN for Few-shot Image Generation.**<br>
*Yan Hong, Li Niu, Jianfu Zhang, Weijie Zhao, Chen Fu, Liqing Zhang.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.01999)]

**Recurrent Feature Reasoning for Image Inpainting.**<br>
*Jingyuan Li, Ning Wang, Lefei Zhang, Bo Du, Dacheng Tao.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2008.03737)] [[GitHub](https://github.com/jingyuanli001/RFR-Inpainting)]

**Learning When and Where to Zoom With Deep Reinforcement Learning.**<br>
*Burak Uzkent, Stefano Ermon.*<br>
CVPR 2020. [[PDF](https://openaccess.thecvf.com/content_CVPR_2020/papers/Uzkent_Learning_When_and_Where_to_Zoom_With_Deep_Reinforcement_Learning_CVPR_2020_paper.pdf)] [[Github](https://github.com/ermongroup/PatchDrop)]

**ESRGAN+: Further Improving Enhanced Super-Resolution Generative Adversarial Network.**<br>
*Nathanaël Carraz Rakotonirina, Andry Rasoanaivo.*<br>
ICASSP 2020. [[PDF](https://arxiv.org/abs/2001.08073)] [[GitHub](https://github.com/ncarraz/ESRGANplus)]

**Rethinking Image Deraining via Rain Streaks and Vapors.**<br>
*Yinglong Wang, Yibing Song, Chao Ma, Bing Zeng.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.00823)]

**Transmission Map and Atmospheric Light Guided Iterative Updater Network for Single Image Dehazing.**<br>
*Aupendu Kar, Sobhan Kanti Dhara, Debashis Sen, Prabir Kumar Biswas.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.01701)] [[Project](https://aupendu.github.io/iterative-dehaze)]

**Implicit Euler ODE Networks for Single-Image Dehazing.**<br>
*Jiawei Shen, Zhuoyan Li, Lei Yu, Gui-Song Xia, Wen Yang.*<br>
CVPRW 2020. [[PDF](https://arxiv.org/abs/2007.06443)] [[Project](https://github.com/Jiawei-Shen)]

**Wavelet-Based Dual-Branch Network for Image Demoireing.**<br>
*Lin Liu, Jianzhuang Liu, Shanxin Yuan, Gregory Slabaugh, Ales Leonardis, Wengang Zhou, Qi Tian.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.07173)]

**Exploring Multi-Scale Feature Propagation and Communication for Image Super Resolution.**<br>
*Ruicheng Feng, Weipeng Guan, Yu qiao, Chao Dong.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.00239)]

**Deep Photo Cropper and Enhancer.**<br>
*Aaron Ott, Amir Mazaheri, Niels D. Lobo, Mubarak Shah.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.00634)]

**DCSFN: Deep Cross-scale Fusion Network for Single Image Rain Removal.**<br>
*Cong Wang, Xiaoying Xing, Zhixun Su, Junyang Chen.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.00767)] [[Github](https://supercong94.wixsite.com/supercong94)]

**Exploring Image Enhancement for Salient Object Detection in Low Light Images.**<br>
*Xin Xu, Shiqin Wang, Zheng Wang, Xiaolong Zhang, Ruimin Hu.*<br>
ACM Transactions on Multimedia Computing, Communications, and Applications 2020. [[PDF](https://arxiv.org/abs/2007.16124)]

**Cross-Scale Internal Graph Neural Network for Image Super-Resolution.**<br>
*Shangchen Zhou, Jiawei Zhang, Wangmeng Zuo, Chen Change Loy.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16673)]

**Polarized Reflection Removal with Perfect Alignment in the Wild.**<br>
*Chenyang Lei, Xuhua Huang, Mengdi Zhang, Qiong Yan, [Wenxiu Sun](http://wenxiusun.com/), and [Qifeng Chen](https://cqf.io/publication).*</br>
CVPR 2020. [[PDF](http://openaccess.thecvf.com/content_CVPR_2020/papers/Lei_Polarized_Reflection_Removal_With_Perfect_Alignment_in_the_Wild_CVPR_2020_paper.pdf)] [[Project](https://leichenyang.weebly.com/project-polarized.html)] [[Github](https://github.com/ChenyangLEI/CVPR2020-Polarized-Reflection-Removal-with-Perfect-Alignment)]

**MuCAN: Multi-Correspondence Aggregation Network for Video Super-Resolution.**<br>
*Wenbo Li, Xin Tao, Taian Guo, Lu Qi, Jiangbo Lu, Jiaya Jia.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11803)]

**PIPAL: a Large-Scale Image Quality Assessment Dataset for Perceptual Image Restoration.**<br>
*Jinjin Gu, Haoming Cai, Haoyu Chen, Xiaoxing Ye, Jimmy Ren, Chao Dong.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.12142)]

**Guided Deep Decoder: Unsupervised Image Pair Fusion.**<br>
*Tatsumi Uezato, Danfeng Hong, Naoto Yokoya, Wei He.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11766)]

**Learning Disentangled Feature Representation for Hybrid-distorted Image Restoration.**<br>
*Xin Li, Xin Jin, Jianxin Lin, Tao Yu, Sen Liu, Yaojun Wu, Wei Zhou, Zhibo Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11430)]

**Texture Hallucination for Large-Factor Painting Super-Resolution.**<br>
*Yulun Zhang, Zhifei Zhang, Stephen DiVerdi, Zhaowen Wang, Jose Echevarria, Yun Fu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.00515)] [[Github](http://yulunzhang.com/papers/PaintingSR_supp_arXiv.pdf)]

**Microscopy Image Restoration with Deep Wiener-Kolmogorov filters.**<br>
*Valeriya Pronina, Filippos Kokkinos, Dmitry V. Dylov, Stamatios Lefkimmiatis.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1911.10989)]

**Fully Trainable and Interpretable Non-Local Sparse Models for Image Restoration.**<br>
*Bruno Lecouat, Jean Ponce, Julien Mairal.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.02456)]

**Learning Enriched Features for Real Image Restoration and Enhancement.**<br>
*Syed Waqas Zamir, Aditya Arora, Salman Khan, Munawar Hayat, Fahad Shahbaz Khan, Ming-Hsuan Yang, Ling Shao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.06792)] [[Github](https://github.com/swz30/MIRNet)]

**Learning Disentangled Feature Representation for Hybrid-distorted Image Restoration.**<br>
*Xin Li, Xin Jin, Jianxin Lin, Sen Liu, Yaojun Wu, Tao Yu, Wei Zhou, [Zhibo Chen](http://staff.ustc.edu.cn/~chenzhibo/publi.html).*<br>
ECCV 2020.

**LIRA: Lifelong Image Restoration from Unknown Blended Distortions.**<br>
*Jianzhao Liu, Jianxin Lin, Xin Li, Wei Zhou, Sen Liu, Zhibo Chen.*<br>
ECCV 2020.

**Journey Towards Tiny Perceptual Super-Resolution.**<br>
*Royson Lee, Łukasz Dudziak, Mohamed Abdelfattah, Stylianos I. Venieris, Hyeji Kim, Hongkai Wen, Nicholas D. Lane.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.04356)]

**Lightweight Image Super-Resolution with Enhanced CNN.**<br>
*Chunwei Tian, Ruibin Zhuge, Zhihao Wu, Yong Xu, Wangmeng Zuo, Chen Chen, Chia-Wen Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04344)]

**HDR-GAN: HDR Image Reconstruction from Multi-Exposed LDR Images with Large Motions.**<br>
*Yuzhen Niu, Jianbin Wu, Wenxi Liu, Wenzhong Guo, Rynson W.H. Lau.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01628)]

**End-to-end Interpretable Learning of Non-blind Image Deblurring.**<br>
*Thomas Eboli, Jian Sun, Jean Ponce.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.01769)]

**LF-InterNet: Spatial-Angular Interaction for Light Field Image Super-Resolution.**<br>
*Yingqian Wang, Longguang Wang, Jungang Yang, Wei An, Jingyi Yu, Yulan Guo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.07849)] [[Github](https://github.com/YingqianWang/LF-InterNet)]

**Invertible Image Rescaling.**<br>
*Mingqing Xiao, Shuxin Zheng, Chang Liu, Yaolong Wang, Di He, Guolin Ke, Jiang Bian, Zhouchen Lin, Tie-Yan Liu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.05650)] [[Github](https://github.com/pkuxmq/Invertible-Image-Rescaling)]

**You Only Look Yourself: Unsupervised and Untrained Single Image Dehazing Neural Network.**<br>
*Boyun Li, Yuanbiao Gou, Shuhang Gu, Jerry Zitao Liu, Joey Tianyi Zhou, Xi Peng.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16829)]

**Cross-Scale Internal Graph Neural Network for Image Super-Resolution.**<br>
*Shangchen Zhou, Jiawei Zhang, Wangmeng Zuo, Chen Change Loy.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16673)]

**End-to-End Differentiable Learning to HDR Image Synthesis for Multi-exposure Images.**<br>
*Jung Hee Kim, Siyeong Lee, Soyeon Jo, Suk-Ju Kang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.15833)]

**Hierarchical Patch VAE-GAN (HP-VAE-GAN): Generating Diverse Videos from a Single Sample.**<br>
*[Shir Gur](http://www.gurshir.com/), [Sagie Benaim](https://sagiebenaim.github.io/), [Lior Wolf](http://www.cs.tau.ac.il/~wolf/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.12226)] [[Project](https://shirgur.github.io/hp-vae-gan/)] [[Github](https://github.com/shirgur/hp-vae-gan)]

**Sigma-VAE: Simple and Effective VAE Training with Calibrated Decoders.**<br>
*[Oleh Rybkin](https://www.seas.upenn.edu/~oleh/), [Kostas Daniilidis](https://www.cis.upenn.edu/~kostas/), [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.13202)] [[Project](https://orybkin.github.io/sigma-vae/)] [[Github](https://github.com/orybkin/sigma-vae)]

**SRFlow: Learning the Super-Resolution Space with Normalizing Flow.**<br>
*Andreas Lugmayr, Martin Danelljan, Luc Van Gool, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.14200)]

**Burst Photography for Learning to Enhance Extremely Dark Images.**<br>
*Ahmet Serdar Karadeniz, Erkut Erdem, Aykut Erdem.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09845)]

**Structured and Localized Image Restoration.**<br>
*Thomas Eboli, Alex Nowak-Vila, Jian Sun, Francis Bach, Jean Ponce, Alessandro Rudi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09261)]

**USRNet: Deep Unfolding Network for Image Super-Resolution.**<br>
*[Kai Zhang](https://cszn.github.io/), Luc Van Gool, Radu Timofte.*<br>
CVPR 2020. [[PDF](https://arxiv.org/pdf/2003.10428.pdf)] [[Github](https://github.com/cszn/USRNet)]

**Learning to Incorporate Structure Knowledge for Image Inpainting.**<br>
*Jie Yang, Zhiquan Qi, Yong Shi.*<br>
AAAI 2020. [[PDF](https://www.researchgate.net/publication/338984531_Learning_to_Incorporate_Structure_Knowledge_for_Image_Inpainting)] [[Github](https://github.com/YoungGod/sturcture-inpainting)]

**Single Image Reflection Removal through Cascaded Refinement.**<br>
*Chao Li, Yixiao Yang, Kun He, Stephen Lin, John E. Hopcroft.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1911.06634)]

**Single Image Deraining Using Time-lapse Data.**<br>
*Jaehoon Cho, [Seungryong Kim](https://seungryong.github.io/), Dongbo Min, and Kwanghoon Sohn.*<br>
IEEE Trans. on Image Processing (TIP) 2020. [[PDF](https://seungryong.github.io/publication/derain_TIP2020.pdf)]

**GAN-Based Facial Attractiveness Enhancement.**<br>
*Yuhongze Zhou, Qinjie Xiao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.02766)]

**PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models.**<br>
*Sachit Menon, Alexandru Damian, Shijia Hu, Nikhil Ravi, Cynthia Rudin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.03808)] [[Github](https://github.com/adamian98/pulse)]

**DeepUPE: Underexposed Photo Enhancement Using Deep Illumination Estimation.**<br>
*Ruixing Wang, Qing Zhang, Chi-Wing Fu, Xiaoyong Shen, Wei-Shi Zheng, Jiaya Jia.*<br>
CVPR 2019. [[PDF](http://jiaya.me/papers/photoenhance_cvpr19.pdf)] [[Github](https://github.com/luppx/DeepUPE)]

**Image Super-Resolution with Cross-Scale Non-Local Attention and Exhaustive Self-Exemplars Mining.**<br>
*Yiqun Mei, Yuchen Fan, Yuqian Zhou, Lichao Huang, Thomas S. Huang, and Humphrey Shi.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.01424)] [[Github](https://github.com/SHI-Labs/Cross-Scale-Non-Local-Attention)]

**Single Image HDR Reconstruction Using a CNN with Masked Features and Perceptual Loss.**<br>
*Marcel Santana Santos, Tsang Ing Ren, Nima Khademi Kalantari.*<br>
SIGGRAPH 2020. [[PDF](http://faculty.cs.tamu.edu/nimak/Papers/SIGGRAPH2020_HDR/files/SIGGRAPH2020Final.pdf)] [[Project](http://faculty.cs.tamu.edu/nimak/Papers/SIGGRAPH2020_HDR/)]

**Pyramid Attention Networks for Image Restoration.**<br>
*[Yiqun Mei](http://yiqunm2.web.illinois.edu/), [Yuchen Fan](https://scholar.google.com/citations?user=BlfdYL0AAAAJ&hl=en), [Yulun Zhang](http://yulunzhang.com/), [Jiahui Yu](https://jiahuiyu.com/), [Yuqian Zhou](https://yzhouas.github.io/), [Ding Liu](https://scholar.google.com/citations?user=PGtHUI0AAAAJ&hl=en), [Yun Fu](http://www1.ece.neu.edu/~yunfu/), [Thomas S. Huang](http://ifp-uiuc.github.io/), [Honghui Shi](https://www.humphreyshi.com/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2004.13824.pdf)] [[Github](https://github.com/SHI-Labs/Pyramid-Attention-Networks)]

**Multi-Scale Boosted Dehazing Network with Dense Feature Fusion.**<br>
*Hang Dong, Jinshan Pan, Lei Xiang, Zhe Hu, Xinyi Zhang, Fei Wang, Ming-Hsuan Yang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.13388)] [[Github](https://github.com/BookerDeWitt/MSBDN-DFF)]

**Real Image Denoising with Feature Attention.**<br>
*Saeed Anwar, Nick Barnes.*<br>
ICCV 2019, [[PDF](https://arxiv.org/abs/1904.07396)]

**Deploying Image Deblurring across Mobile Devices: A Perspective of Quality and Latency.**<br>
*Cheng-Ming Chiang, Yu Tseng, Yu-Syuan Xu, Hsien-Kai Kuo, Yi-Min Tsai, Guan-Yu Chen, Koan-Sin Tan, Wei-Ting Wang, Yu-Chieh Lin, Shou-Yao Roy Tseng, Wei-Shiang Lin, Chia-Lin Yu, BY Shen, Kloze Kao, Chia-Ming Cheng, Hung-Jen Chen.*<br>
CVPR 2020 Workshop NTIRE. [[PDF](https://arxiv.org/abs/2004.12599)]

**Learning to Autofocus.**<br>
*Charles Herrmann, Richard Strong Bowen, Neal Wadwha, Rahul Garg, Qirui He, Jonathan T. Barron, Ramin Zabih.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.12260)]

**Conditional Variational Image Deraining.**<br>
*Ying-Jun Du, Jun Xu, Xian-Tong Zhen, Ming-Ming Cheng, Ling Shao.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2004.11373)]

**A Review of an Old Dilemma: Demosaicking First, or Denoising First?**<br>
*Qiyu Jin, Gabriele Facciolo, Jean-Michel Morel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.11577)]

**Quantization Guided JPEG Artifact Correction.**<br>
*Max Ehrlich, Ser-Nam Lim, Larry Davis, Abhinav Shrivastava.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.09320)]

**Unified Dynamic Convolutional Network for Super-Resolution with Variational Degradations.**<br>
*Yu-Syuan Xu, Shou-Yao Roy Tseng, Yu Tseng, Hsien-Kai Kuo, Yi-Min Tsai.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.06965)]

**Path-Restore: Learning Network Path Selection for Image Restoration.**<br>
*Ke Yu, Xintao Wang, Chao Dong, Xiaoou Tang, Chen Change Loy.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1904.10343)] [[Project](https://yuke93.github.io/Path-Restore/)]

**ADEFAN: Divergence-Based Adaptive Extreme Video Completion.**<br>
*[Majed El Helou](http://majedelhelou.github.io/), Ruofan Zhou, Frank Schmutz, Fabrice Guibert, Sabine Süsstrunk.*<br>
ICASSP 2020. [[PDF](https://arxiv.org/abs/2004.06409)] [[Github](https://github.com/majedelhelou/ADEFAN)] [[Data](https://ieee-dataport.org/documents/extreme-video-completion-dataset)]

**Bringing Old Photos Back to Life.**<br>
*[Ziyu Wan](http://raywzy.com), Bo Zhang, [Dongdong Chen](http://www.dongdongchen.bid/), Pan Zhang, Dong Chen, Jing Liao, Fan Wen.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.09484)] [[Project](http://raywzy.com/Old_Photo/)]

**A General Decoupled Learning Framework for Parameterized Image Operators.**<br>
*Qingnan Fan, Dongdong Chen, Lu Yuan, Gang Hua, Nenghai Yu, Baoquan Chen.*<br>
TPAMI 2019. [[PDF](https://arxiv.org/abs/1907.05852.pdf)] 

**Decouple Learning for Parameterized Image Operators.**<br>
*Qingnan Fan, Dongdong Chen, Lu Yuan, Gang Hua, Nenghai Yu, Baoquan Chen.*<br>
ECCV 2018. [[PDF](http://www.dongdongchen.bid/pubs/colorization_sig18.pdf)] [[Github](https://github.com/msracver/Deep-Exemplar-based-Colorization)]

**Gated Context Aggregation Network for Image Dehazing and Deraining.**<br>
*Dongdong Chen, Mingming He, Qingnan Fan, Jing Liao, Liheng Zhang, Dongdong Hou, Lu Yuan, Gang Hua.*<br>
WACV 2019. [[PDF](https://arxiv.org/pdf/1811.08747.pdf)] [[Github](https://github.com/cddlyf/GCANet)]

**Spatially-Attentive Patch-Hierarchical Network for Adaptive Motion Deblurring.**<br>
*Maitreya Suin, Kuldeep Purohit, A. N. Rajagopalan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.05343)]

**Learning Event-Based Motion Deblurring.**<br>
*Zhe Jiang, Yu Zhang, Dongqing Zou, Jimmy Ren, Jiancheng Lv, Yebin Liu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.05794)]

**Structure-Preserving Super Resolution with Gradient Guidance.**<br>
*Cheng Ma, Yongming Rao, Yean Cheng, Ce Chen, Jiwen Lu, Jie Zhou.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13081)] [[Github](https://github.com/Maclory/SPSR)]

**DeepSEE: Deep Disentangled Semantic Explorative Extreme Super-Resolution.**<br>
*Marcel Christoph Bühler, Andrés Romero, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.04433)] [[Project](https://mcbuehler.github.io/DeepSEE/)] [[Github](github.com/mcbuehler/DeepSEE)]

**Deblurring using Analysis-Synthesis Networks Pair.**<br>
*Adam Kaufman, Raanan Fattal.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02956)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), [Xingang Pan](https://xingangpan.github.io/), Bo Dai, Ziwei Liu, Dahua Lin, Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Github](https://github.com/XiaohangZhan/deocclusion/)]

**Deep White-Balance Editing.**<br>
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), [Michael S. Brown](http://www.cse.yorku.ca/~mbrown/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01354)]

**What Else Can Fool Deep Learning? Addressing Color Constancy Errors on Deep Neural Network Performance.**<br>
*[Mahmoud Afifi](http://www.cse.yorku.ca/~mafifi/), Michael S. Brown.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Afifi_What_Else_Can_Fool_Deep_Learning_Addressing_Color_Constancy_Errors_ICCV_2019_paper.pdf)] [[Project](http://cvil.eecs.yorku.ca/projects/public_html/wb_emulation/index.html)] [[Github](https://github.com/mahmoudnafifi/WB_color_augmenter)]

**When Color Constancy Goes Wrong: Correcting Improperly White-Balanced Images.**<br>
*Mahmoud Afifi, Brian Price, Scott Cohen, and Michael S. Brown.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Afifi_When_Color_Constancy_Goes_Wrong_Correcting_Improperly_White-Balanced_Images_CVPR_2019_paper.pdf)] [[Github](https://github.com/mahmoudnafifi/WB_sRGB)] 

**Rethinking Data Augmentation for Image Super-resolution: A Comprehensive Analysis and a New Strategy.**<br>
*Jaejun Yoo, Namhyuk Ahn, Kyung-Ah Sohn.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00448)] [[Github](https://github.com/clovaai/cutblur)]

**Learning to See Through Obstructions.**<br>
*Yu-Lun Liu, Wei-Sheng Lai, Ming-Hsuan Yang, Yung-Yu Chuang.*<br>
CVPR 2020. [[PDF](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/ObstructionRemoval_/02197.pdf)] [[Github](https://github.com/alex04072000/ObstructionRemoval)] [[Project](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/ObstructionRemoval)]

**Learning to See Through Obstructions with Layered Decomposition.**<br>
*Yu-Lun Liu, Wei-Sheng Lai, Ming-Hsuan Yang, Yung-Yu Chuang, Jia-Bin Huang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.04902)]

**DeepLPF: Deep Local Parametric Filters for Image Enhancement.**<br>
*Sean Moran, Pierre Marza, Steven McDonagh, Sarah Parisot, Gregory Slabaugh.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13985)]

**Replacing Mobile Camera ISP with a Single Deep Learning Model.**<br>
*Andrey Ignatov, Luc Van Gool, Radu Timofte.* <br>
arxiv, 13 Feb 2020. [[PDF](https://arxiv.org/abs/2002.05509)] [[Github](https://github.com/aiff22/PyNET)] [[Project](http://people.ee.ethz.ch/~ihnatova/pynet.html)]

**EEMEFN: Low-Light Image Enhancement via Edge-Enhanced Multi-Exposure Fusion Network.**<br>
*Minfeng Zhu, Pingbo Pan, Wei Chen, Yi Yang.*<br>
AAAI 2020. [[PDF](http://www.cad.zju.edu.cn/home/vagblog/VAG_Work/EEMEFN-Low%20Light%20Image%20Enhancement%20via%20Edge%20Enhanced%20MultiExposure%20Fusion%20Network.pdf)] [[Project](https://zjuvag.org/publications/eemefn/)]

## Challenge and Survey

**AIM 2020: Scene Relighting and Illumination Estimation Challenge.**<br>
*Majed El Helou, Ruofan Zhou, Sabine Süsstrunk, Radu Timofte, et al.*<br>
ECCVW 2020. [[PDF](https://arxiv.org/abs/2009.12798)] [[Project](https://github.com/majedelhelou/VIDIT)]

**NTIRE 2020 Challenge on Perceptual Extreme Super-Resolution: Methods and Results.**<br>
*Kai Zhang, Shuhang Gu, Radu Timofte, et al.*<br>
NTIRE 2020 [Challenge](https://data.vision.ee.ethz.ch/cvl/ntire20/). [[PDF](https://arxiv.org/abs/2005.01056)]

**NTIRE 2020 Challenge on Image and Video Deblurring.**<br>
*[Seungjun Nah](https://seungjunnah.github.io/), [Sanghyun Son](https://cv.snu.ac.kr/sanghyun_son/sanghyun_son_cv.pdf), [Radu Timofte](https://vision.ee.ethz.ch/~timofter/), Kyoung Mu Lee.*<br>
CVPR 2020 Workshop: New Trends in Image Restoration and Enhancement. [[PDF](https://arxiv.org/abs/2005.01244)]

**NTIRE 2020 Challenge on Image Demoireing: Methods and Results.**<br>
*Shanxin Yuan, Radu Timofte et al.*<br>
NTIRE 2020. [[PDF](https://arxiv.org/abs/2005.03155)]

**AIM 2019 Challenge on Video Temporal Super-Resolution: Methods and Results.**<br>
*Seungjun Nah, Sanghyun Son, Radu Timofte, Kyoung Mu Lee.*<br>
ICCV 2019 Workshop: Advances in Image Manipulation. [[PDF](https://arxiv.org/abs/2005.01233)]


