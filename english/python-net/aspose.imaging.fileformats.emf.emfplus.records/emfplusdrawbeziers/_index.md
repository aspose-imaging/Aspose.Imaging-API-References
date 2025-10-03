---
title: EmfPlusDrawBeziers Class
type: docs
weight: 80
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Initializes a new instance of the [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Gets or sets a value indicating whether the PointData is compressed. <br/>            If set, PointData specifies absolute locations in the coordinate space with <br/>            16-bit integer coordinates. If clear, PointData specifies absolute locations <br/>            in the coordinate space with 32-bit floating-point coordinates.<br/>            Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the Bezier curves. The value MUST be zero to 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the point data<br/>            An array of Count points that specify the starting, ending, and control points of the Bezier curves. The ending coordinate of one Bezier curve is the starting coordinate of the next. The control points are used for producing the Bezier effect.<br/>            The type of data in this array is specified by the Flags field, as follows: Data Type Meaning<br/>            EmfPlusPointR object (section 2.2.2.37)<br/>            If the P flag is set in the Flags, the points specify relative locations.<br/>            EmfPlusPointF object (section 2.2.2.36)<br/>            If the P and C bits are clear in the Flags field, the points specify absolute locations.<br/>            EmfPlusPoint object (section 2.2.2.35)<br/>            If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations.<br/>            A Bezier curve does not pass through its control points. The control points act as |
| relative | bool | r/w | Gets or sets a value indicating whether the PointData is relative.<br/>            If set, each element in PointData specifies a location in the coordinate space <br/>            that is relative to the location specified by the previous element in the array. <br/>            In the case of the first element in PointData, a previous location at coordinates <br/>            (0,0) is assumed. If clear, PointData specifies absolute locations according <br/>            to the C flag.<br/>            Note If this flag is set, the C flag (above) is undefined and MUST be ignored. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Initializes a new instance of the [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

