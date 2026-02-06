---
title: Enum WmfPenStyle
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfPenStyle enum. The 16bit PenStyle Enumeration is used to specify different types of pens that can be used in graphics operations
type: docs
weight: 8450
url: /net/aspose.imaging.fileformats.wmf.consts/wmfpenstyle/
---
## WmfPenStyle enumeration

The 16-bit PenStyle Enumeration is used to specify different types of pens that can be used in graphics operations.

```csharp
public enum WmfPenStyle : short
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Cosmetic | `0` | The cosmetic |
| EndcapRound | `0` | The line end caps are round. |
| JoinRound | `0` | Line joins are round. |
| Solid | `0` | The pen is solid. |
| Dash | `1` | The pen is dashed. |
| Dot | `2` | The pen is dotted. |
| Dashdot | `3` | The pen has alternating dashes and dots. |
| Dashdotdot | `4` | The pen has dashes and double dots. |
| Null | `5` | The pen is invisible. |
| Insideframe | `6` | The pen is solid. When this pen is used in any drawing record that takes a bounding rectangle, the dimensions of the figure are shrunk so that it fits entirely in the bounding rectangle, taking into account the width of the pen. |
| Userstyle | `7` | The pen uses a styling array supplied by the user. |
| Alternate | `8` | The pen sets every other pixel (this style is applicable only for cosmetic pens). |
| EndcapSquare | `256` | Line end caps are square. |
| EndcapFlat | `512` | Line end caps are flat. |
| JoinBevel | `4096` | Line joins are beveled. |
| JoinMiter | `8192` | Line joins are mitered when they are within the current limit set by the SETMITERLIMIT META_ESCAPE record. A join is beveled when it would exceed the limit. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


