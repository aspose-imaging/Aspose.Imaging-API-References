---
title: EmfPlusDrawArc Class
type: docs
weight: 70
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Initializes a new instance of the [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets the size of the data.<br/>            A 32-bit unsigned integer that specifies the 32-bit-aligned number of<br/>            bytes of record-specific data that follows.<br/>            For this record type, the value MUST be one of the following:<br/>            0x00000010 If the C bit is set in the Flags field.<br/>            0x00000018 If the C bit is clear in the Flags field. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the<br/>            EMF+ Object Table to draw the arc. The value MUST be zero to 63, inclusive. |
| rect_float | bool | r/w | Gets or sets a value indicating whether the data contains <br/>            EmfPlusRectF or EmfPlusRect records<br/>            This bit indicates whether the data in the RectData field is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38).<br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gets or sets the rectangle data<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box<br/>            of the ellipse that is collinear with the arc. This rectangle defines the<br/>            position, size, and shape of the arc. The type of object in this field is<br/>            specified by the value of the Flags field. |
| size | int | r/w | Gets or sets the size.<br/>            A 32-bit unsigned integer that specifies the 32-bit-aligned number of<br/>            bytes in the entire record, including the 12-byte record header and<br/>            record-specific data. For this record type, the value MUST be one of the following:<br/>            0x0000001C  If the C bit is set in the Flags field.<br/>            0x00000024  If the C bit is clear in the Flags field |
| start_angle | float | r/w | Gets or sets the start angle<br/>            A 32-bit non-negative floating-point value that specifies the angle between<br/>            the x-axis and the starting point of the arc. Any value is acceptable,<br/>            but it MUST be interpreted modulo 360, with the result that is used being<br/>            in the range 0.0 inclusive to 360.0 exclusive. |
| sweep_angle | float | r/w | Gets or sets the sweep angle<br/>            A 32-bit floating-point value that specifies the extent of the arc to draw,<br/>            as an angle in degrees measured from the starting point defined by the<br/>            StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0<br/>            to 360.0 inclusive. A positive value indicates that the sweep is defined in<br/>            a clockwise direction, and a negative value indicates that the sweep is<br/>            defined in a counter-clockwise direction. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Initializes a new instance of the [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

