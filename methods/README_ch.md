[English](README.md) | 简体中文

# Methods

- [1. 简介](#1-简介)
- [2. OCR](#2-OCR)
  - [2.1 文本检测](#21-文本检测)
    - [2.1.1 数据集](#211-数据集)
    - [2.1.2 模型集](#212-模型集)
  - [2.2 文本识别](#22-文本识别)
    - [2.2.1 数据集](#221-数据集)
    - [2.2.2 模型集](#222-模型集)
- [3. 表格识别](#3-表格识别)
    - [3.1 数据集](#31-数据集)
    - [3.2 模型集](#32-模型集)
- [4. 医学影像分割](#4-医学影像分割)
    - [4.1 数据集](#41-数据集)
    - [4.2 图像格式以及处理](#42-图像格式以及处理)
    - [4.3 2D分割模型集](#43-2D分割模型集)
    - [4.4 3D分割模型集](#44-3D分割模型集)



## 1. 简介

涉及多个领域的模型方法介绍与实验

## 2. OCR
### 2.1 [文本检测]()

#### 2.1.1 数据集
|名称|简介|下载地址|
| --- | --- |--- |
|ICDAR2015|||

#### 2.1.2 模型集
|模型名称|模型简介|论文|代码|
| --- | --- | --- | --- |
|DB|||here|

### 2.2 [文本识别]()
#### 2.2.1 数据集
|名称|简介|下载地址|
| --- | --- |--- |
|MJSynth|||
|SynthText|||

#### 2.2.2 模型集
|模型名称|模型简介|论文|代码|
| --- | --- | --- | --- |
|CRNN|||here|

## 3. 表格识别
#### 3.1 数据集
|名称|简介|下载地址|
| --- | --- |--- |
|PubTabNet|||

#### 3.2 模型集
|模型名称|模型简介|论文|代码|
| --- | --- | --- | --- |
|TableMaster|||here|
|SLANet|||here|
|RARE|||here|

## 4. 医学影像分割

### 4.1 数据集
|名称|简介|下载地址|
| --- | --- |--- |
|彩超数据|百度大脑和中山大学中山眼科中心联合举办的iChallenge比赛||
|X-ray影像|2017RSNA骨龄预测比赛||
|CT影像|4C 2021 医学影像挑战赛||
|肺部数据|[COVID-19 CT scans](https://www.kaggle.com/andrewmvd/covid19-ct-scans) ||
|椎骨数据|[MRISpineSeg](https://aistudio.baidu.com/aistudio/datasetdetail/81211) ||
|[MSD](http://medicaldecathlon.com/)|||
|[Promise12](https://promise12.grand-challenge.org/)|||
|[Prostate_mri](https://liuquande.github.io/SAML/)等数据集|||


### 4.2 图像格式以及处理
- https://blog.csdn.net/huang1024rui/article/details/121449670

|格式名称|简介|DEMO|
| --- | --- |--- |
|Analyze|.img/.hdr||
|DICOM|||
|NLFTL|.nii .img/.hdr||
|MINC|.mnc||
|AFNI|brick .BRIK||

### 4.3 2D分割模型集
|模型名称|模型简介|论文|代码|
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


### 4.4 3D分割模型集 
- https://zhuanlan.zhihu.com/p/346246175

|模型名称|模型简介|论文|代码|
| --- | --- | --- | --- |
|3D-UNet|||here|
|3D-VNet|||here|
|UNETR||https://arxiv.org/abs/2103.10504|https://github.com/Project-MONAI/research-contributions/tree/main/UNETR/BTCV|

