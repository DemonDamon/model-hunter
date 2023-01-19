English | [简体中文](README_ch.md)

# Methods

- [1. Introduction](#1-Introduction)
- [2. OCR](#2-OCR)
  - [2.1 Text Detection](#21-Text-Detection)
    - [2.1.1 Dataset](#211-Dataset)
    - [2.1.2 Modelset](#212-Modelset)
  - [2.2 Text Recognition](#22-Text-Recognition)
    - [2.2.1 Dataset](#221-Dataset)
    - [2.2.2 Modelset](#222-Modelset)
- [3. Table Recognition](#3-Table-Recognition)
    - [3.1 Dataset](#31-Dataset)
    - [3.2 Modelset](#32-Modelset)
- [4. Medical Image Segmentation](#4-Medical-Image-Segmentation)
    - [4.1 Dataset](#41-Dataset)
    - [4.2 图像格式以及处理](#42-图像格式以及处理)
    - [4.3 2D分割modelset](#43-2D分割模型集)
    - [4.4 3D分割模型集](#44-3D分割模型集)



## 1. Introduction

interfere explanations and experiments of models from different tasks

## 2. OCR
### 2.1 [Text Detection]()

#### 2.1.1 Dataset
|Name|Intro|Download|
| --- | --- |--- |
|ICDAR2015|||

#### 2.1.2 Modelset
|Name|Intro|Paper|Code|
| --- | --- | --- | --- |
|DB|||here|

### 2.2 [Text Recognition]()
#### 2.2.1 Dataset
|Name|Intro|Download|
| --- | --- |--- |
|MJSynth|||
|SynthText|||

#### 2.2.2 Modelset
|Name|Intro|Paper|Code|
| --- | --- | --- | --- |
|CRNN|||here|

## 3. Table Recognition
#### 3.1 Dataset
|Name|Intro|Download|
| --- | --- |--- |
|PubTabNet|||

#### 3.2 ModelSet
|Name|Intro|Paper|Code|
| --- | --- | --- | --- |
|TableMaster|||here|
|SLANet|||here|
|RARE|||here|

## 4. Medical Image Segmentation

### 4.1 Dataset
|Name|Intro|Download|
| --- | --- |--- |
|彩超数据|百度大脑和中山大学中山眼科中心联合举办的iChallenge比赛||
|X-ray影像|2017RSNA骨龄预测比赛||
|CT影像|4C 2021 医学影像挑战赛||
|[COVID-19 CT scans](https://www.kaggle.com/andrewmvd/covid19-ct-scans)|肺部CT数据||
|[MRISpineSeg](https://aistudio.baidu.com/aistudio/datasetdetail/81211)|椎骨MRI数据||
|[MSD](http://medicaldecathlon.com/)|||
|[Promise12](https://promise12.grand-challenge.org/)|||
|[Prostate_mri](https://liuquande.github.io/SAML/)|||


### 4.2 Image Format Processing
- https://blog.csdn.net/huang1024rui/article/details/121449670

|Name|Intro|DEMO|
| --- | --- |--- |
|Analyze|.img/.hdr||
|DICOM|||
|NLFTL|.nii .img/.hdr||
|MINC|.mnc||
|AFNI|brick .BRIK||

### 4.3 2D Segmentation Modelset
|Name|Intro|Paper|Code|
| --- | --- | --- | --- |
|UNet|||here|
|Attention UNet|||here|
|MA-UNet|||here|
|VNet||https://arxiv.org/abs/1606.04797|here|
|UNet++|||here|
|ResUNet|||here|
|TransUNet|||here|
|MCTrans|||here|
|UTNet|||here|
|PNS-Net|||here|
|MBT-Net|||here|


### 4.4 3D Segmentation Modelset
- https://zhuanlan.zhihu.com/p/346246175

|Name|Intro|Paper|Code|
| --- | --- | --- | --- |
|3D-UNet|||here|
|3D-VNet|||here|
|UNETR||https://arxiv.org/abs/2103.10504|https://github.com/Project-MONAI/research-contributions/tree/main/UNETR/BTCV|

