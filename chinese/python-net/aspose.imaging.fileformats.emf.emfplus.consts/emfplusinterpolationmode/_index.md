---
title: "EmfPlusInterpolationMode Enumeration"
type: docs
weight: 200
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

InterpolationMode 枚举定义了执行缩放的方式，包括拉伸和收缩。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | 指定双三次插值，它使用围绕待插值像素的最近 4×4 像素邻域。对这 16 个已知像素值进行加权平均，以确定待插值像素的值。由于已知像素与待插值像素的距离可能不同，距离更近的像素在计算中权重更高。其结果比 InterpolationModeBilinear 更平滑。 |
| INTERPOLATION_MODE_BILINEAR | 指定双线性插值，它使用围绕待插值像素的最近 2×2 像素邻域。对这 4 个已知像素值进行加权平均，以确定待插值像素的值。其结果比 InterpolationModeNearestNeighbor 更平滑。 |
| INTERPOLATION_MODE_DEFAULT | 指定默认的插值模式，定义为 InterpolationModeBilinear。 |
| INTERPOLATION_MODE_HIGH_QUALITY | 指定高质量插值模式，其定义为 InterpolationModeHighQualityBicubic。 |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | 指定带预过滤的双三次插值，在这些选项中产生最高质量的结果。 |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | 指定带预过滤的双线性插值。 |
| INTERPOLATION_MODE_LOW_QUALITY | 指定低质量插值模式，其定义为 InterpolationModeNearestNeighbor。 |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | 指定最近邻插值，仅使用最接近插值像素的像素值。此模式仅复制或删除像素，在这些选项中产生最低质量的结果。 |
