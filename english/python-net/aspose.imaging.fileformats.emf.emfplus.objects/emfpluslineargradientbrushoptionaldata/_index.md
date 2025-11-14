---
title: EmfPlusLinearGradientBrushOptionalData Class
type: docs
weight: 450
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | Initializes a new instance of the EmfPlusLinearGradientBrushOptionalData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Gets or sets an optional blend pattern for the linear gradient brush. If this field is present, <br/>            it MUST contain either an EmfPlusBlendColors object (section 2.2.2.4), <br/>            or one or two EmfPlusBlendFactors objects (section 2.2.2.5), <br/>            but it MUST NOT contain both. The table below shows the valid combinations of <br/>            EmfPlusLinearGradientBrushData BrushData flags and the corresponding blend patterns:<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Gets the blend pattern as blend factors h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Gets the blend pattern as blend factors v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Gets the blend pattern as preset colors. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a<br/>            world space to device space transform for the linear gradient brush. <br/>            This field MUST be present if the BrushDataTransform flag is set in the<br/>            BrushDataFlags field of the EmfPlusLinearGradientBrushData object. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

Initializes a new instance of the EmfPlusLinearGradientBrushOptionalData class

