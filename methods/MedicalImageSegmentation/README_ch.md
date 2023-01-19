# 医学影像分割

- [1. 简介](#1-简介)
- [2. 数据集](#2-数据集)
- [3. 图像格式以及处理](#3-图像格式以及处理)
- [4. 2D分割模型集](#4-2D分割模型集)
- [5. 3D分割模型集](#5-3D分割模型集)


## 1. 简介

## 2. 数据集
|名称|简介|下载地址|
| --- | --- |--- |
|彩超数据|百度大脑和中山大学中山眼科中心联合举办的iChallenge比赛||
|X-ray影像|2017RSNA骨龄预测比赛||
|CT影像|4C 2021 医学影像挑战赛||
|[COVID-19 CT scans](https://www.kaggle.com/andrewmvd/covid19-ct-scans)|肺部CT数据||
|[MRISpineSeg](https://aistudio.baidu.com/aistudio/datasetdetail/81211)|椎骨MRI数据||
|[MSD](http://medicaldecathlon.com/)|||
|[Promise12](https://promise12.grand-challenge.org/)|||
|[Prostate_mri](https://liuquande.github.io/SAML/)|||

## 3. 图像格式以及处理
- https://blog.csdn.net/huang1024rui/article/details/121449670

|格式名称|简介|DEMO|
| --- | --- |--- |
|Analyze|.img/.hdr||
|DICOM|||
|NLFTL|.nii .img/.hdr||
|MINC|.mnc||
|AFNI|brick .BRIK||

## 4. 2D分割模型集
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


## 5. 3D分割模型集
- https://zhuanlan.zhihu.com/p/346246175

|模型名称|模型简介|论文|代码|
| --- | --- | --- | --- |
|3D-UNet|||here|
|3D-VNet|||here|
|UNETR||https://arxiv.org/abs/2103.10504|https://github.com/Project-MONAI/research-contributions/tree/main/UNETR/BTCV|

