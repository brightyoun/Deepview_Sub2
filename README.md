# Deepview_Sub2

## 1 Description
   * DerainZoo: A list of deraining methods. Papers, codes and datasets are maintained. Other sources about deraining can be observed in [web1](https://github.com/TaiXiangJiang/FastDeRain) and [web2](https://github.com/hongwang01/Video-and-Single-Image-Deraining).

   * Datasets for single image deraining are available at the [website](https://github.com/nnUyi/DerainZoo/blob/master/DerainDatasets.md).
   
   * More datasets about other image processing task (brightening, HDR, color enhancement, and inpainting) are available [here](https://github.com/nnUyi/Image-Processing-Datasets).

## 2 전역 추적 기술
* PSNR (Peak Signal-to-Noise Ratio) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4550695) [[matlab code]](https://www.mathworks.com/help/images/ref/psnr.html) [[python code]](https://github.com/aizvorski/video-quality)
* SSIM (Structural Similarity) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1284395) [[matlab code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) [[python code]](https://github.com/aizvorski/video-quality/blob/master/ssim.py)
* VIF (Visual Quality) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1576816) [[matlab code]](http://sse.tongji.edu.cn/linzhang/IQA/Evalution_VIF/eva-VIF.htm)
* FSIM (Feature Similarity) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5705575) [[matlab code]](http://sse.tongji.edu.cn/linzhang/IQA/FSIM/FSIM.htm)
* NIQE (Naturalness Image Quality Evaluator) [[paper]](http://live.ece.utexas.edu/research/Quality/niqe_spl.pdf)[[matlab code]](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)[[python code]](https://github.com/aizvorski/video-quality/blob/master/niqe.py)

**Image & Video Quality Assessment Algorithms [[software release]](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)[[Texas Lab]](http://live.ece.utexas.edu/research/quality/)**

## 3 이상상황 인식 기술
### 3.1 Datasets
------------
#### 3.1.1 Synthetic Datasets
* Rain12 [[paper](https://ieeexplore.ieee.org/document/7780668/)] [[dataset](http://yu-li.github.io/paper/li_cvpr16_rain.zip)] (2016 CVPR)
* Rain100L_old_version [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_Deep_Joint_Rain_CVPR_2017_paper.pdf)][[dataset](http://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html)](2017 CVPR)
  * Rain100L_new_version [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_Deep_Joint_Rain_CVPR_2017_paper.pdf)][[dataset](http://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html)]
* Rain100H_old_version [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_Deep_Joint_Rain_CVPR_2017_paper.pdf)][[dataset](https://github.com/nnUyi/DerainZoo/blob/master/DerainDatasets.md)](2017 CVPR)
  * Rain100H_new_version [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_Deep_Joint_Rain_CVPR_2017_paper.pdf)][[dataset](http://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html)]
* Rain800 [[paper](https://arxiv.org/abs/1701.05957)][[dataset](https://github.com/hezhangsprinter/ID-CGAN)] (2017 Arxiv)
* Rain1200 [[paper](https://arxiv.org/abs/1802.07412)][[dataset](https://github.com/hezhangsprinter/DID-MDN)] (2018 CVPR)
* Rain1400 [[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Fu_Removing_Rain_From_CVPR_2017_paper.pdf)][[dataset](https://xueyangfu.github.io/projects/cvpr2017.html)] (2017 CVPR)
* Heavy Rain Dataset [[paper](http://export.arxiv.org/pdf/1904.05050)][[dataset](https://drive.google.com/file/d/1rFpW_coyxidYLK8vrcfViJLDd-BcSn4B/view)] (2019 CVPR)
