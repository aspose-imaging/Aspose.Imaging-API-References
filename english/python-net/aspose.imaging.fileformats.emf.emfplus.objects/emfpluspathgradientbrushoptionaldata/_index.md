---
title: EmfPlusPathGradientBrushOptionalData Class
type: docs
weight: 510
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | Initializes a new instance of the EmfPlusPathGradientBrushOptionalData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Gets or sets an optional blend pattern for the path gradient brush. If this field is<br/>            present, it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), <br/>            or an EmfPlusBlendFactors object (section 2.2.2.5), but it MUST NOT contain both. <br/>            The table below shows the valid combinations of EmfPlusPathGradientBrushData<br/>            BrushData flags and the corresponding blend patterns: |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Gets or sets an optional EmfPlusFocusScaleData object (section 2.2.2.18) that specifies <br/>            focus scales for the path gradient brush. This field MUST be present if the<br/>            BrushDataFocusScales flag is set in the BrushDataFlags field of the <br/>            EmfPlusPathGradientBrushData object. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the path gradient brush. <br/>            This field MUST be present if the BrushDataTransform flag is set in the BrushDataFlags field of the EmfPlusPathGradientBrushData object. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

Initializes a new instance of the EmfPlusPathGradientBrushOptionalData class

