---
title: Enum EmfPenStyle
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfPenStyle enum. The PenStyle enumeration defines the attributes of pens that can be used in graphics operations. A pen style is a combination of pen type line style line cap and line join
type: docs
weight: 2870
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
## EmfPenStyle enumeration

The PenStyle enumeration defines the attributes of pens that can be used in graphics operations. A pen style is a combination of pen type, line style, line cap, and line join.

```csharp
[Flags]
public enum EmfPenStyle
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PS_COSMETIC | `0` | A pen type that specifies a line with a width of one logical unit and a style that is a solid color |
| PS_ENDCAP_ROUND | `0` | A line cap that specifies round ends. |
| PS_JOIN_ROUND | `0` | A line join that specifies round joins |
| PS_SOLID | `0` | A line style that is a solid color |
| PS_DASH | `1` | A line style that is dashed |
| PS_DOT | `2` | A line style that is dotted. |
| PS_DASHDOT | `3` | A line style that consists of alternating dashes and dots |
| PS_DASHDOTDOT | `4` | A line style that consists of dashes and double dots. |
| PS_NULL | `5` | A line style that is invisible. |
| PS_INSIDEFRAME | `6` | A line style that is a solid color. When this style is specified in a drawing record that takes a bounding rectangle, the dimensions of the figure are shrunk so that it fits entirely in the bounding rectangle, taking into account the width of the pen. |
| PS_USERSTYLE | `7` | A line style that is defined by a styling array, which specifies the lengths of dashes and gaps in the line |
| PS_ALTERNATE | `8` | A line style in which every other pixel is set. This style is applicable only to a pen type of PS_COSMETIC |
| PS_ENDCAP_SQUARE | `100` | A line cap that specifies square ends. |
| PS_ENDCAP_FLAT | `200` | A line cap that specifies flat ends. |
| PS_JOIN_BEVEL | `1000` | A line join that specifies beveled joins. |
| PS_JOIN_MITER | `2000` | A line join that specifies mitered joins when the lengths of the joins are within the current miter length limit that is set in the playback device context. If the lengths of the joins exceed the miter limit, beveled joins are specified |
| PS_GEOMETRIC | `10000` | A pen type that specifies a line with a width that is measured in logical units and a style that can contain any of the attributes of a brush. |
| StyleMask | `F` | The style mask |
| EndCapMask | `F00` | The end cap mask |
| JoinMask | `F000` | The join mask |
| TypeMask | `F0000` | The type mask |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


