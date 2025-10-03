---
title: EmfPlusFilterType Enumeration
type: docs
weight: 140
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---

The FilterType enumeration defines types of filtering algorithms that can be used for text and graphics quality enhancement and image rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusFilterType

## **Members**
| **Member name** | **Description** |
| :- | :- |
| FILTER_TYPE_BOX | Specifies a box filter algorithm, in which each destination pixel is computed by averaging a rectangle of source pixels. This algorithm is useful only when reducing the size of an image. |
| FILTER_TYPE_GAUSSIAN_QUAD | Specifies that a 4-sample Gaussian filter is used, which creates a blur effect on an image. |
| FILTER_TYPE_LINEAR | Specifies that linear interpolation is performed using the weighted average of a 2x2 area of pixels surrounding the source pixel. |
| FILTER_TYPE_NONE | Specifies that filtering is not performed. |
| FILTER_TYPE_POINT | Specifies that each destination pixel is computed by sampling the nearest pixel from the source image. |
| FILTER_TYPE_PYRAMIDAL_QUAD | Specifies that a 4-sample tent filter is used. |
| FILTER_TYPE_TRIANGLE | Specifies that each pixel in the source image contributes equally to the destination image. This is the slowest of filtering algorithms. |
