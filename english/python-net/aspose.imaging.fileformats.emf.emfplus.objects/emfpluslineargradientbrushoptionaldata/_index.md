---
title: EmfPlusLinearGradientBrushOptionalData Class
type: docs
weight: 450
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPlusLinearGradientBrushOptionalData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusLinearGradientBrushOptionalData()|Initializes a new instance of the EmfPlusLinearGradientBrushOptionalData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|transform_matrix|Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a<br/>            world space to device space transform for the linear gradient brush. <br/>            This field MUST be present if the BrushDataTransform flag is set in the<br/>            BrushDataFlags field of the EmfPlusLinearGradientBrushData object.|
|blend_pattern|Gets or sets an optional blend pattern for the linear gradient brush. If this field is present, <br/>            it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), <br/>            or one or two EmfPlusBlendFactors objects (section 2.2.2.5), <br/>            but it MUST NOT contain both. The table below shows the valid combinations of <br/>            EmfPlusLinearGradientBrushData BrushData flags and the corresponding blend patterns:<br/>            EmfPlusBlendFactors|
|blend_pattern_as_preset_colors|Gets the blend pattern as preset colors.|
|blend_pattern_as_blend_factors_h|Gets the blend pattern as blend factors h.|
|blend_pattern_as_blend_factors_v|Gets the blend pattern as blend factors v.|
