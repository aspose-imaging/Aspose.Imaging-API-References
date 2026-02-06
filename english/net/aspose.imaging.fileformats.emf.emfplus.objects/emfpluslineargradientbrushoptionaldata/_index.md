---
title: Class EmfPlusLinearGradientBrushOptionalData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLinearGradientBrushOptionalData class. The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush
type: docs
weight: 5690
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
## EmfPlusLinearGradientBrushOptionalData class

The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

```csharp
public sealed class EmfPlusLinearGradientBrushOptionalData : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData](emfpluslineargradientbrushoptionaldata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpattern/) { get; set; } | Gets or sets an optional blend pattern for the linear gradient brush. If this field is present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), or one or two EmfPlusBlendFactors objects (section 2.2.2.5), but it MUST NOT contain both. The table below shows the valid combinations of EmfPlusLinearGradientBrushData BrushData flags and the corresponding blend patterns: EmfPlusBlendFactors |
| [BlendPatternAsBlendFactorsH](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsh/) { get; } | Gets the blend pattern as blend factors h. |
| [BlendPatternAsBlendFactorsV](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsv/) { get; } | Gets the blend pattern as blend factors v. |
| [BlendPatternAsPresetColors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternaspresetcolors/) { get; } | Gets the blend pattern as preset colors. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/transformmatrix/) { get; set; } | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the linear gradient brush. This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusLinearGradientBrushData object. |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


