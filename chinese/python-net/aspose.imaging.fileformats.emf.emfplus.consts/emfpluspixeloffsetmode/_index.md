---
title: "EmfPlusPixelOffsetMode 枚举"
type: docs
weight: 350
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

PixelOffsetMode 枚举定义了像素的偏移方式，指定了渲染速度与质量之间的权衡。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | 像素以整数坐标为中心，优先考虑速度而非质量。 |
| PIXEL_OFFSET_MODE_HALF | 像素以半整数坐标为中心，这意味着像素在 x 和 y 轴上覆盖 0 到 1 的区域，其中心位于 (0.5,0.5)。在渲染过程中对像素进行偏移，可以在牺牲渲染速度的情况下提升渲染质量。 |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | 像素以半整数坐标为中心，类似于 PixelOffsetModeHalf。指定以更高质量为代价牺牲速度。 |
| PIXEL_OFFSET_MODE_HIGH_SPEED | 像素以整数坐标为中心，类似于 PixelOffsetModeNone。指定以更高速度为代价牺牲质量。 |
| PIXEL_OFFSET_MODE_NONE | 像素以原点为中心，这意味着像素在 x 和 y 轴上覆盖 -0.5 到 0.5 的区域，其中心位于 (0,0)。 |
