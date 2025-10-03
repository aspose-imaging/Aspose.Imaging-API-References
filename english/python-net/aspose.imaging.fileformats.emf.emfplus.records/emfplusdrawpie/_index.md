---
title: EmfPlusDrawPie Class
type: docs
weight: 170
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---

**Summary:** The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawPie(source)](#EmfPlusDrawPie_source_1) | Initializes a new instance of the [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Gets or sets a value indicating whether the PointData is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38).<br/>            If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the pie. The value MUST be zero to 63, inclusive. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gets or sets the rectangle datas<br/>            Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the <br/>            ellipse that contains the pie wedge. This rectangle defines the position, size, <br/>            and shape of the pie. The type of object in this field is specified by the value <br/>            of the Flags field. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| start_angle | float | r/w | Gets or sets the start angle<br/>            A 32-bit, non-negative floating-point value that specifies the angle between the <br/>            x-axis and the starting point of the pie wedge. Any value is acceptable, but it <br/>            MUST be interpreted modulo 360, with the result that is used being in the range <br/>            0.0 inclusive to 360.0 exclusive. |
| sweep_angle | float | r/w | Gets or sets the sweep angle<br/>            A 32-bit floating-point value that specifies the extent of the arc that defines <br/>            the pie wedge to draw, as an angle in degrees measured from the starting point <br/>            defined by the StartAngle value. Any value is acceptable, but it MUST be clamped <br/>            to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined <br/>            in a clockwise direction, and a negative value indicates that the sweep is defined <br/>            in a counter-clockwise direction. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawPie(source) {#EmfPlusDrawPie_source_1}


```
 EmfPlusDrawPie(source) 
```

Initializes a new instance of the [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

