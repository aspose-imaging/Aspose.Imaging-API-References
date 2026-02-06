---
title: Class EmfPlusPathGradientBrushData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathGradientBrushData class. The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush
type: docs
weight: 5740
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
## EmfPlusPathGradientBrushData class

The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

```csharp
public sealed class EmfPlusPathGradientBrushData : EmfPlusBaseBrushData
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusPathGradientBrushData](emfpluspathgradientbrushdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BoundaryData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/boundarydata/) { get; set; } | Gets or sets the boundary of the path gradient brush, which is specified by either a path or a closed cardinal spline. If the BrushDataPath flag is set in the BrushDataFlags field, this field MUST contain an EmfPlusBoundaryPathData object (section 2.2.2.6); otherwise, this field MUST contain an EmfPlusBoundaryPointData object (section 2.2.2.7). |
| [BrushDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/brushdataflags/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a path gradient brush: |
| [CenterArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerargb32color/) { get; set; } | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. The color of the brush changes gradually from the boundary color to the center color as it moves from the boundary to the center point. |
| [CenterPointF](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerpointf/) { get; set; } | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, which is the color that appears at the center point of the brush. The color of the brush changes gradually from the boundary color to the center color as it moves from the boundary to the center point. |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/optionaldata/) { get; set; } | Gets or sets an optional EmfPlusPathGradientBrushOptionalData object (section 2.2.2.30) that specifies additional data for the path gradient brush. The specific contents of this field are determined by the value of the BrushDataFlags field. |
| [SurroundingArgb32Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/surroundingargb32colors/) { get; set; } | Gets or sets array of SurroundingColorCount EmfPlusARGB objects that specify the colors for discrete points on the boundary of the brush. |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/wrapmode/) { get; set; } | Gets or sets 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies whether to paint the area outside the boundary of the brush. When painting outside the boundary, the wrap mode specifies how the color gradient is repeated |

### See Also

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


