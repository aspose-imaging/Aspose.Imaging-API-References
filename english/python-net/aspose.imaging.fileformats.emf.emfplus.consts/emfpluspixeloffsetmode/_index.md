---
title: EmfPlusPixelOffsetMode Enumeration
type: docs
weight: 350
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---

The PixelOffsetMode enumeration defines how pixels are offset, which specifies the trade-off between rendering speed and quality.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusPixelOffsetMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| PIXEL_OFFSET_MODE_DEFAULT | Pixels are centered on integer coordinates, specifying speed over quality. |
| PIXEL_OFFSET_MODE_HALF | Pixels are centered on half-integer coordinates, which means that the pixel covers the area from 0 to 1 on both the x and y axes and its center is at (0.5,0.5). By offsetting pixels during rendering, the render quality can be improved at the cost of render speed. |
| PIXEL_OFFSET_MODE_HIGH_QUALITY | Pixels are centered on half-integer coordinates, as with PixelOffsetModeHalf. Higher quality at the expense of speed is specified. |
| PIXEL_OFFSET_MODE_HIGH_SPEED | Pixels are centered on integer coordinates, as with PixelOffsetModeNone. Higher speed at the expense of quality is specified. |
| PIXEL_OFFSET_MODE_NONE | Pixels are centered on the origin, which means that the pixel covers the area from -0.5 to 0.5 on both the x and y axes and its center is at (0,0). |
