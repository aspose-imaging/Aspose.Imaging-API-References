---
title: EmfPlusDrawArc Class
type: docs
weight: 70
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusDrawArc type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawArc(source)|Initializes a new instance of the EmfPlusDrawArc class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|Gets or sets the size.<br/>            A 32-bit unsigned integer that specifies the 32-bit-aligned number of<br/>            bytes in the entire record, including the 12-byte record header and<br/>            record-specific data. For this record type, the value MUST be one of the following:<br/>            0x0000001C  If the C bit is set in the Flags field.<br/>            0x00000024  If the C bit is clear in the Flags field|
|data_size|Gets or sets the size of the data.<br/>            A 32-bit unsigned integer that specifies the 32-bit-aligned number of<br/>            bytes of record-specific data that follows.<br/>            For this record type, the value MUST be one of the following:<br/>            0x00000010 If the C bit is set in the Flags field.<br/>            0x00000018 If the C bit is clear in the Flags field.|
|rect_float|Gets or sets a value indicating whether the data contains <br/>            EmfPlusRectF or EmfPlusRect records<br/>            This bit indicates whether the data in the RectData field is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38).<br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).|
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the<br/>            EMF+ Object Table to draw the arc. The value MUST be zero to 63, inclusive.|
|start_angle|Gets or sets the start angle<br/>            A 32-bit non-negative floating-point value that specifies the angle between<br/>            the x-axis and the starting point of the arc. Any value is acceptable,<br/>            but it MUST be interpreted modulo 360, with the result that is used being<br/>            in the range 0.0 inclusive to 360.0 exclusive.|
|sweep_angle|Gets or sets the sweep angle<br/>            A 32-bit floating-point value that specifies the extent of the arc to draw,<br/>            as an angle in degrees measured from the starting point defined by the<br/>            StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0<br/>            to 360.0 inclusive. A positive value indicates that the sweep is defined in<br/>            a clockwise direction, and a negative value indicates that the sweep is<br/>            defined in a counter-clockwise direction.|
|rectangle_data|Gets or sets the rectangle data<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box<br/>            of the ellipse that is collinear with the arc. This rectangle defines the<br/>            position, size, and shape of the arc. The type of object in this field is<br/>            specified by the value of the Flags field.|
