---
title: Enum EmfPointEnum
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfPointEnum enum. The Point enumeration is used to specify how a point is to be used in a drawing call
type: docs
weight: 2880
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
## EmfPointEnum enumeration

The Point enumeration is used to specify how a point is to be used in a drawing call.

```csharp
[Flags]
public enum EmfPointEnum : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PT_CLOSEFIGURE | `1` | A PT_LINETO or PT_BEZIERTO type can be combined with this value by using the bitwise operator OR to indicate that the corresponding point is the last point in a figure and the figure is closed |
| PT_LINETO | `2` | Specifies that a line is to be drawn from the current position to this point, which then becomes the new current position |
| PT_BEZIERTO | `4` | Specifies that this point is a control point or ending point for a Bezier curve. |
| PT_MOVETO | `6` | Specifies that this point starts a disjoint figure. This point becomes the new current position. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


