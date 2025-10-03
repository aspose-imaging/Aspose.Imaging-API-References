---
title: EmfPlusPathGradientBrushData Class
type: docs
weight: 500
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | Initializes a new instance of the EmfPlusPathGradientBrushData class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Gets or sets the boundary of the path gradient brush, which is specified by either a path or a closed cardinal spline. <br/>            If the BrushDataPath flag is set in the BrushDataFlags field, this field MUST contain an EmfPlusBoundaryPathData object (section 2.2.2.6); <br/>            otherwise, this field MUST contain an EmfPlusBoundaryPointData object (section 2.2.2.7). |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field.<br/>            This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a path gradient brush: |
| center_argb_32_color | int | r/w | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of <br/>            the path gradient brush, which is the color that appears at the center point of the brush. <br/>            The color of the brush changes gradually from the boundary <br/>            color to the center color as it moves from the boundary to the center point. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, <br/>            which is the color that appears at the center point of the brush. The color of the<br/>            brush changes gradually from the boundary color to the center color as it moves<br/>             from the boundary to the center point. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | Gets or sets an optional EmfPlusPathGradientBrushOptionalData object (section 2.2.2.30) that <br/>            specifies additional data for the path gradient brush. <br/>            The specific contents of this field are determined by the value of the BrushDataFlags field. |
| surrounding_argb_32_colors | int[] | r/w | Gets or sets array of SurroundingColorCount EmfPlusARGB objects <br/>            that specify the colors for discrete points on the boundary of the brush. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Gets or sets 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies<br/>            whether to paint the area outside the boundary of the brush. When painting <br/>            outside the boundary, the wrap mode specifies how the color gradient is repeated |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

Initializes a new instance of the EmfPlusPathGradientBrushData class

