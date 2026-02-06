---
title: Enum EmfPlusPixelOffsetMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPixelOffsetMode enum. The PixelOffsetMode enumeration defines how pixels are offset which specifies the tradeoff between rendering speed and quality
type: docs
weight: 5140
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/
---
## EmfPlusPixelOffsetMode enumeration

The PixelOffsetMode enumeration defines how pixels are offset, which specifies the trade-off between rendering speed and quality.

```csharp
public enum EmfPlusPixelOffsetMode : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PixelOffsetModeDefault | `0` | Pixels are centered on integer coordinates, specifying speed over quality. |
| PixelOffsetModeHighSpeed | `1` | Pixels are centered on integer coordinates, as with PixelOffsetModeNone. Higher speed at the expense of quality is specified. |
| PixelOffsetModeHighQuality | `2` | Pixels are centered on half-integer coordinates, as with PixelOffsetModeHalf. Higher quality at the expense of speed is specified. |
| PixelOffsetModeNone | `3` | Pixels are centered on the origin, which means that the pixel covers the area from -0.5 to 0.5 on both the x and y axes and its center is at (0,0). |
| PixelOffsetModeHalf | `4` | Pixels are centered on half-integer coordinates, which means that the pixel covers the area from 0 to 1 on both the x and y axes and its center is at (0.5,0.5). By offsetting pixels during rendering, the render quality can be improved at the cost of render speed. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


