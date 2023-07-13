---
title: EmfPlusDrawCurve Class
type: docs
weight: 100
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusDrawCurve type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_0) | Initializes a new instance of the [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| compressed | bool | r/w | Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. <br/>            If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates<br/>            Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored |
| object_id | byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the curve. The value MUST be zero to 63, inclusive. |
| tension | float | r/w | Gets or sets the tension<br/>            A 32-bit floating point number that specifies how tightly the spline <br/>            bends as it passes through the points. A value of 0 specifies that <br/>            the spline is a sequence of straight lines. As the value increases, <br/>            the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD]. |
| num_segments | int | r/w | Gets or sets the segments count <br/>            A 32-bit unsigned integer that specifies the number of line segments making up the spline. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | r/w | Gets or sets an array of either 32-bit signed integers or 32-bit floating-point numbers of <br/>            Count length that defines coordinate values of the endpoints of the lines to be stroked. |

### EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_0}


```
 EmfPlusDrawCurve(source) 
```

Initializes a new instance of the [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

