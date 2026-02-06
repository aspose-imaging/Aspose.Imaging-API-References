---
title: Class EmfPlusBlendFactors
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlendFactors class. The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush
type: docs
weight: 5330
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---
## EmfPlusBlendFactors class

The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

```csharp
public sealed class EmfPlusBlendFactors : EmfPlusBlendBase
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusBlendFactors](emfplusblendfactors/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlendFactors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/blendfactors/) { get; set; } | Gets or sets an array of PositionCount 32-bit floating point values that specify proportions of colors at the positions defined in the BlendPositions field. Each value MUST be a number between 0.0 and 1.0 inclusive. |
| [BlendPositions](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/blendpositions/) { get; set; } | Gets or sets blend positions An array of PositionCount 32-bit floating-point values that specify proportions of distance along the gradient line. Each element MUST be a number between 0.0 and 1.0 inclusive. For a linear gradient brush, 0.0 represents the starting point and 1.0 represents the ending point. For a path gradient brush, 0.0 represents the midpoint and 1.0 represents an endpoint |

### See Also

* class [EmfPlusBlendBase](../emfplusblendbase/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


