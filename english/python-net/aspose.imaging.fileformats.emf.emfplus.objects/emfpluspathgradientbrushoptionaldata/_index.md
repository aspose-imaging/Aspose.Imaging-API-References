---
title: EmfPlusPathGradientBrushOptionalData Class
type: docs
weight: 510
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusPathGradientBrushOptionalData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusPathGradientBrushOptionalData()|Initializes a new instance of the EmfPlusPathGradientBrushOptionalData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|transform_matrix|Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the path gradient brush. <br/>            This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object.|
|blend_pattern|Gets or sets an optional blend pattern for the path gradient brush. If this field is<br/>            present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), <br/>            or an EmfPlusBlendFactors object (section 2.2.2.5), but it MUST NOT contain both. <br/>            The table below shows the valid combinations of EmfPlusPathGradientBrushData<br/>            BrushData flags and the corresponding blend patterns:|
|focus_scale_data|Gets or sets an optional EmfPlusFocusScaleData object (section 2.2.2.18) that specifies <br/>            focus scales for the path gradient brush. This field MUST be present if the<br/>            BrushDataFocusScales flag is set in the BrushDataFlags field of the <br/>            EmfPlusPathGradientBrushData object.|
