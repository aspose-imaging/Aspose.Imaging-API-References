---
title: "EmfPlusCompositingQuality Enumeration"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---

CompositingQuality 枚举定义了创建复合图像的质量级别

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusCompositingQuality

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| COMPOSITING_QUALITY_ASSUME_LINEAR | 未执行伽马校正；然而，使用线性值可在略低的速度下获得比默认更好的质量。 |
| COMPOSITING_QUALITY_DEFAULT | 未执行伽马校正。伽马校正控制图像的整体亮度和对比度。如果不进行伽马校正，合成图像可能显得过亮或过暗。 |
| COMPOSITING_QUALITY_GAMMA_CORRECTED | 启用伽马校正以获得更高质量的合成，但速度较慢。就结果而言，此值与 CompositingQualityHighQuality 没有区别。 |
| COMPOSITING_QUALITY_HIGH_QUALITY | 已执行伽马校正。合成质量优先，速度会受到影响。 |
| COMPOSITING_QUALITY_HIGH_SPEED | 未执行伽马校正。合成速度优先，质量会受到影响。就结果而言，此值与 CompositingQualityDefault 没有区别。 |
