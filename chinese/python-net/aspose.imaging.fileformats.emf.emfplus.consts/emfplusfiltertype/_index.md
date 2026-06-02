---
title: "EmfPlusFilterType 枚举"
type: docs
weight: 140
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---

FilterType 枚举定义了可用于文本和图形质量提升以及图像渲染的过滤算法类型。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusFilterType

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| FILTER_TYPE_BOX | 指定一种盒式过滤算法，其中每个目标像素通过对源像素矩形区域取平均值来计算。此算法仅在缩小图像尺寸时有用。 |
| FILTER_TYPE_GAUSSIAN_QUAD | 指定使用 4 采样高斯过滤器，可在图像上产生模糊效果。 |
| FILTER_TYPE_LINEAR | 指定使用线性插值，通过对源像素周围 2×2 区域的像素进行加权平均来实现。 |
| FILTER_TYPE_NONE | 指定不执行过滤。 |
| FILTER_TYPE_POINT | 指定每个目标像素通过采样源图像中最近的像素来计算。 |
| FILTER_TYPE_PYRAMIDAL_QUAD | 指定使用 4 采样帐篷过滤器。 |
| FILTER_TYPE_TRIANGLE | 指定源图像中的每个像素对目标图像贡献相等。这是所有过滤算法中最慢的。 |
