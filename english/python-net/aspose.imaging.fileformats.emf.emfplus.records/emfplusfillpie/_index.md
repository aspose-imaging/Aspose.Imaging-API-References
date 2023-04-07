---
title: EmfPlusFillPie Class
type: docs
weight: 260
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---

The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPie

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusFillPie type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusFillPie(source)|Initializes a new instance of the EmfPlusFillPie class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|compressed|Gets or sets a value indicating whether the PointData is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38).<br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).|
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). <br/>            If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.|
|start_angle|Gets or sets the start angle<br/>            A 32-bit, non-negative floating-point value that specifies the angle between the <br/>            x-axis and the starting point of the pie wedge. Any value is acceptable, but it <br/>            MUST be interpreted modulo 360, with the result that is used being in the range <br/>            0.0 inclusive to 360.0 exclusive.|
|sweep_angle|Gets or sets the sweep angle<br/>            A 32-bit floating-point value that specifies the extent of the arc that defines <br/>            the pie wedge to draw, as an angle in degrees measured from the starting point <br/>            defined by the StartAngle value. Any value is acceptable, but it MUST be clamped <br/>            to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined <br/>            in a clockwise direction, and a negative value indicates that the sweep is defined <br/>            in a counter-clockwise direction.|
|rect_data|Gets or sets the rectangle datas<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the <br/>            ellipse that contains the pie wedge. This rectangle defines the position, size, <br/>            and shape of the pie. The type of object in this field is specified by the value <br/>            of the Flags field.|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that defines the brush, the content of which <br/>            is determined by the S bit in the Flags field.|
