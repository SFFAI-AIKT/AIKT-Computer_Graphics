# AIKT-Image_Style_Transfer

## 图像风格化

- 非真实感图形学
  - 基于笔触渲染的方(Strokebased Rendering)
  - 基于图像类比的方法(Image Analogy)
  - 基于图像滤波的方法(Image Filtering)

- 纹理建模
  - 基于统计分布的参数化纹理建模方法（Parametric Texture Modelling with Summary Statistics）
  - 基于MRF的非参数化纹理建模方法（Non-parametric Texture Modelling with MRFs）

- 图像重建
 - 基于在线图像优化的慢速图像重建方法（Slow Image Reconstruction based on Online Image Optimisation）
    - 基于统计分布的参数化慢速风格化迁移算法(Parametric Slow Neural Method with Summary Statistics)：Image Style Transfer Using Convolutional Neural Networks [<http://openaccess.thecvf.com/content_cvpr_2016/html/Gatys_Image_Style_Transfer_CVPR_2016_paper.html>]
    - 基于MRF的非参数化慢速风格化迁移算法(Non-parametric Slow Neural Method with MRFs)：Combining Markov Random Fields and Convolutional Neural Networks for Image Synthesis [<https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Li_Combining_Markov_Random_CVPR_2016_paper.html>]
 - 基于离线模型优化的快速图像重建方法（Fast Image Reconstruction based on Offline Model Optimisation）
    - 单模型单风格的快速风格化迁移算法(Per-Style-Per-Model Fast Neural Method)
      - 基于统计分布的参数化快速风格化PSPM算法
        - [Texture Networks: Feed-forward Synthesis of Textures and Stylized Images](http://www.jmlr.org/proceedings/papers/v48/ulyanov16.pdf)
        - [Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://link.springer.com/chapter/10.1007/978-3-319-46475-6_43)
      - 基于MRF的非参数化PSPM算法
        - [Precomputed Real-Time Texture Synthesis with Markovian Generative Adversarial Networks](https://link.springer.com/chapter/10.1007/978-3-319-46487-9_43)
    - 单模型多风格的快速风格化迁移算法(Multiple-Style-Per-Model Fast Neural Method)
      - [A Learned Representation for Artistic Style](https://arxiv.org/catchup?smonth=10&sday=8&group=grp_&archive=cs&num=2000&order=reverse&method=w&syear=2016)
      - [StyleBank: An Explicit Representation for Neural Image Style Transfer](http://openaccess.thecvf.com/content_cvpr_2017/html/Chen_StyleBank_An_Explicit_CVPR_2017_paper.html)
      - [Multi-style Generative Network for Real-time Transfer](https://link.springer.com/chapter/10.1007/978-3-030-11018-5_32)
      - [Diversified Texture Synthesis With Feed-Forward Networks](http://openaccess.thecvf.com/content_cvpr_2017/html/Li_Diversified_Texture_Synthesis_CVPR_2017_paper.html)
    - 单模型任意风格的快速风格化迁移算法(Arbitrary-Style-Per-Model Fast Neural Method)
      - [Fast Patch-based Style Transfer of Arbitrary Style](https://arxiv.org/abs/1612.04337)
      - [Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization](http://openaccess.thecvf.com/content_iccv_2017/html/Huang_Arbitrary_Style_Transfer_ICCV_2017_paper.html)
      - [Exploring the Structure of a Real-time, Arbitrary Neural Artistic Stylization Network](https://arxiv.org/abs/1705.06830)
      - [Universal Style Transfer via Feature Transforms](http://papers.nips.cc/paper/6642-universal-style-transfer-via-feature-transforms)