---
title: EmfPlusPathGradientBrushData Class
type: docs
weight: 500
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusPathGradientBrushData type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusPathGradientBrushData()|Initializes a new instance of the EmfPlusPathGradientBrushData class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|brush_data_flags|Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field.<br/>            This value MUST be composed of BrushData flags (section 2.1.2.1). The following flags are relevant to a path gradient brush:|
|wrap_mode|Gets or sets 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies<br/>            whether to paint the area outside the boundary of the brush. When painting <br/>            outside the boundary, the wrap mode specifies how the color gradient is repeated|
|center_argb_32_color|Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of <br/>            the path gradient brush, which is the color that appears at the center point of the brush. <br/>            The color of the brush changes gradually from the boundary <br/>            color to the center color as it moves from the boundary to the center point.|
|center_point_f|Gets or sets EmfPlusARGB object (section 2.2.2.1) that specifies the center color of the path gradient brush, <br/>            which is the color that appears at the center point of the brush. The color of the<br/>            brush changes gradually from the boundary color to the center color as it moves<br/>             from the boundary to the center point.|
|surrounding_argb_32_colors|Gets or sets array of SurroundingColorCount EmfPlusARGB objects <br/>            that specify the colors for discrete points on the boundary of the brush.|
|boundary_data|Gets or sets the boundary of the path gradient brush, which is specified by either a path or a closed cardinal spline. <br/>            If the BrushDataPath flag is set in the BrushDataFlags field, this field MUST contain an EmfPlusBoundaryPathData object (section 2.2.2.6); <br/>            otherwise, this field MUST contain an EmfPlusBoundaryPointData object (section 2.2.2.7).|
|optional_data|Gets or sets an optional EmfPlusPathGradientBrushOptionalData object (section 2.2.2.30) that <br/>            specifies additional data for the path gradient brush. <br/>            The specific contents of this field are determined by the value of the BrushDataFlags field.|
