---
title: EmfPlusCompositingQuality Enumeration
type: docs
weight: 70
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---

The CompositingQuality enumeration defines levels of quality for creating composite images

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusCompositingQuality

## **Members**
| **Member name** | **Description** |
| :- | :- |
| COMPOSITING_QUALITY_ASSUME_LINEAR | No gamma correction is performed; however, using linear values results in better quality than the default at a slightly lower speed. |
| COMPOSITING_QUALITY_DEFAULT | No gamma correction is performed. Gamma correction controls the overall brightness and contrast of an image. Without gamma correction, composited images can appear too light or too dark. |
| COMPOSITING_QUALITY_GAMMA_CORRECTED | Enable gamma correction for higher-quality compositing with lower speed. In terms of the result, there is no difference between this value and CompositingQualityHighQuality. |
| COMPOSITING_QUALITY_HIGH_QUALITY | Gamma correction is performed. Compositing quality is favored at the expense of speed. |
| COMPOSITING_QUALITY_HIGH_SPEED | No gamma correction is performed. Compositing speed is favored at the expense of quality. In terms of the result, there is no difference between this value and CompositingQualityDefault. |
