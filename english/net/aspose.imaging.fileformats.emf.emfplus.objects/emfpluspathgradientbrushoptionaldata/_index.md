---
title: Class EmfPlusPathGradientBrushOptionalData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathGradientBrushOptionalData class. The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush
type: docs
weight: 5750
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
## EmfPlusPathGradientBrushOptionalData class

The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

```csharp
public sealed class EmfPlusPathGradientBrushOptionalData : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData](emfpluspathgradientbrushoptionaldata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/blendpattern/) { get; set; } | Gets or sets an optional blend pattern for the path gradient brush. If this field is present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), or an EmfPlusBlendFactors object (section 2.2.2.5), but it MUST NOT contain both. The table below shows the valid combinations of EmfPlusPathGradientBrushData BrushData flags and the corresponding blend patterns: |
| [FocusScaleData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/focusscaledata/) { get; set; } | Gets or sets an optional EmfPlusFocusScaleData object (section 2.2.2.18) that specifies focus scales for the path gradient brush. This field MUST be present if the BrushDataFocusScales flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/transformmatrix/) { get; set; } | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the path gradient brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object. |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


