[English](README.md) | 简体中文

# Methods

- [1. 简介](#1-简介)
- [2. 图像转换](#2-图像转换)
  - [2.1 可视化](#21-可视化)
- [3. Mosaic](#3-Mosaic)
  - [3.1 Mixup](#31-Mixup)
  - [3.2 Cutout](#32-Cutout)
  - [3.3 Cutmix](#33-Cutmix)
- [4. 生成式方法](#4-生成式方法)

## 1. 简介

涉及多个领域的模型方法介绍与实验

## 2. OCR
### 2.1 [文本检测]()
|模型名称|模型简介|数据集|代码|
| --- | --- | --- | --- |
|DB||ICDAR2015|here|

### 2.2 [文本识别]()
|模型名称|模型简介|数据集|代码|
| --- | --- | --- | --- |
|CRNN||SynthText|here|

## 3. 表格识别

### 3.1 TableMaster

### 3.2 SLANet

### 3.3 RARE

## 4. 医学影像分割

### 4.1 数据来源

彩超数据：百度大脑和中山大学中山眼科中心联合举办的iChallenge比赛

X-ray影像:2017RSNA骨龄预测比赛

CT影像:4C 2021 医学影像挑战赛
    
肺部数据 [COVID-19 CT scans](https://www.kaggle.com/andrewmvd/covid19-ct-scans) 

椎骨数据 [MRISpineSeg](https://aistudio.baidu.com/aistudio/datasetdetail/81211) 

[MSD](http://medicaldecathlon.com/)

[Promise12](https://promise12.grand-challenge.org/)

[Prostate_mri](https://liuquande.github.io/SAML/)等数据集


### 4.2 图像格式 
https://blog.csdn.net/huang1024rui/article/details/121449670
Analyze .img/.hdr

DICOM

NLFTL .nii .img/.hdr

MINC .mnc

AFNI brick .BRIK

### 4.3 2D分割

#### 4.3.1 UNet

#### 4.3.2 Attention UNet

#### 4.3.3 MA-UNet

#### 4.3.4 VNet https://arxiv.org/abs/1606.04797

#### 4.3.5 UNet++

#### 4.3.6 ResUNet

#### 4.3.7 TransUNet

#### 4.3.8 MCTrans

#### 4.3.9 UTNet

#### 4.3.10 PNS-Net

#### 4.3.11 MBT-Net

### 4.4 3D分割 https://zhuanlan.zhihu.com/p/346246175


#### 4.4.1 3D-UNet

#### 4.4.2 3D-VNet

#### 4.4.3 UNETR 

https://arxiv.org/abs/2103.10504  

https://github.com/Project-MONAI/research-contributions/tree/main/UNETR/BTCV
  


 
