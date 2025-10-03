---
title: EmfPlusBrushDataFlags Enumeration
type: docs
weight: 30
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

The BrushData flags specify properties of graphics brushes, including the presence of optional data fields. These flags can be combined to specify multiple options.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects.<br/>            If set, an [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) object (section 2.2.2.5) that specifies a blend pattern along a horizontal gradient MUST be specified in the OptionalData field of the brush data object. |
| BRUSH_DATA_BLEND_FACTORS_V | This flag is meaningful in EmfPlusLinearGradientBrushData objects.<br/>            If set, an EmfPlusBlendFactors object that specifies a blend pattern along a vertical gradient MUST be specified in the OptionalData field of the brush data object. |
| BRUSH_DATA_DO_NOT_TRANSFORM | This flag is meaningful in EmfPlusTextureBrushData objects.<br/>            If set, a world space to device space transform SHOULD NOT be applied to the texture brush. |
| BRUSH_DATA_FOCUS_SCALES | This flag is meaningful in EmfPlusPathGradientBrushData objects.<br/>            If set, an[EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) object (section 2.2.2.18) MUST be specified in the OptionalData field of the brush data object. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | This flag is meaningful in EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData, and EmfPlusTextureBrushData objects.<br/>            If set, the brush MUST already be gamma corrected; that is, output brightness and intensity have been corrected to match the input image. |
| BRUSH_DATA_PATH | This flag is meaningful in [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) objects (section 2.2.2.29).<br/>            If set, an [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) object (section 2.2.2.6) MUST be specified in the BoundaryData field of the brush data object.<br/>            If clear, an [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) object (section 2.2.2.7) MUST be specified in the BoundaryData field of the brush data object. |
| BRUSH_DATA_PRESET_COLORS | This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects.<br/>            If set, an [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) object (section 2.2.2.4) MUST be specified in the OptionalData field of the brush data object. |
| BRUSH_DATA_TRANSFORM | This flag is meaningful in [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) objects (section 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) objects, and [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) objects (section 2.2.2.45).<br/>            If set, a 2x3 world space to device space transform matrix MUST be specified in the OptionalData field of the brush data object. |
