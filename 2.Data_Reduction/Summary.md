# 数据处理的一般流程

[TOC]

X射线数据处理基本上可以遵照一些标准化的流程。流程因人而异，但都是[各个X射线望远镜](../1.Introduction/Data_Structure.md)官方网站给出的数据处理分析方法与个人工作经验结合的结果。主要的官方网站如下：

- **Chandra**: https://cxc.cfa.harvard.edu/ciao/threads/index.html
- **XMM-Newton**: https://xmm-tools.cosmos.esa.int/external/xmm_user_support/documentation/sas_usg/USG/
- **Suzaku**: ???

如下列出我自己的一个_**Chandra**_数据处理流程。其他人（牛书：Suzaku，水乃：XMM-Newton/RGS，...）可以把他们自己的补充进去。

## _Chandra_ Imaging Spectroscopy Data Reduction Pipeline

1. Follow [data preparation](Chandra/0.data_preparation.md);
2. Follow [calibration procedure](./Chandra/1.calibration.md);
3. Follow [astrometry correction](./Chandra/2.astrometry.md);
4. Follow [flux image creation](./Chandra/3.fluximage.md);
5. Follow [instrumental background creation](./Chandra/4.background.md);
6. Follow [point-like source detection](./Chandra/5.soudet.md);
7. Follow [color image creation](./Chandra/6.colorimage.md);

##_XMM-Newton_ Imaging Spectroscpic Data Reduction Pipeline

##_XMM-Newton_ Grating Spectroscpic Data Reduction Pipeline

## _Suzaku_/XIS Data Rection Pipeline

