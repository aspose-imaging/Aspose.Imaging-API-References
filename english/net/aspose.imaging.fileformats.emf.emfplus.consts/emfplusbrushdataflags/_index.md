---
title: Enum EmfPlusBrushDataFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusBrushDataFlags enum. The BrushData flags specify properties of graphics brushes including the presence of optional data fields. These flags can be combined to specify multiple options
type: docs
weight: 4810
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

The BrushData flags specify properties of graphics brushes, including the presence of optional data fields. These flags can be combined to specify multiple options.

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| BrushDataPath | `1` | This flag is meaningful in [`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) objects (section 2.2.2.29). If set, an [`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) object (section 2.2.2.6) MUST be specified in the BoundaryData field of the brush data object. If clear, an [`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) object (section 2.2.2.7) MUST be specified in the BoundaryData field of the brush data object. |
| BrushDataTransform | `2` | This flag is meaningful in [`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) objects (section 2.2.2.24), [`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) objects, and [`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) objects (section 2.2.2.45). If set, a 2x3 world space to device space transform matrix MUST be specified in the OptionalData field of the brush data object. |
| BrushDataPresetColors | `4` | This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects. If set, an [`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) object (section 2.2.2.4) MUST be specified in the OptionalData field of the brush data object. |
| BrushDataBlendFactorsH | `8` | This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects. If set, an [`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) object (section 2.2.2.5) that specifies a blend pattern along a horizontal gradient MUST be specified in the OptionalData field of the brush data object. |
| BrushDataBlendFactorsV | `10` | This flag is meaningful in EmfPlusLinearGradientBrushData objects. If set, an EmfPlusBlendFactors object that specifies a blend pattern along a vertical gradient MUST be specified in the OptionalData field of the brush data object. |
| BrushDataFocusScales | `40` | This flag is meaningful in EmfPlusPathGradientBrushData objects. If set, an[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) object (section 2.2.2.18) MUST be specified in the OptionalData field of the brush data object. |
| BrushDataIsGammaCorrected | `80` | This flag is meaningful in EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData, and EmfPlusTextureBrushData objects. If set, the brush MUST already be gamma corrected; that is, output brightness and intensity have been corrected to match the input image. |
| BrushDataDoNotTransform | `100` | This flag is meaningful in EmfPlusTextureBrushData objects. If set, a world space to device space transform SHOULD NOT be applied to the texture brush. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


