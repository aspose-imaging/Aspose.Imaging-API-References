---
title: Class EmfPlusBlendColors
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlendColors class. The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush
type: docs
weight: 5320
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---
## EmfPlusBlendColors class

The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

```csharp
public sealed class EmfPlusBlendColors : EmfPlusBlendBase
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusBlendColors](emfplusblendcolors/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlendArgb32Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/blendargb32colors/) { get; set; } | Gets or sets an array of PositionCount EmfPlusARGB objects (section 2.2.2.1) that specify colors at the positions defined in the BlendPositions field. |
| [BlendPositions](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/blendpositions/) { get; set; } | Gets or sets blend positions An array of PositionCount 32-bit floating-point values that specify proportions of distance along the gradient line. Each element MUST be a number between 0.0 and 1.0 inclusive. For a linear gradient brush, 0.0 represents the starting point and 1.0 represents the ending point. For a path gradient brush, 0.0 represents the midpoint and 1.0 represents an endpoint |

### See Also

* class [EmfPlusBlendBase](../emfplusblendbase/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


