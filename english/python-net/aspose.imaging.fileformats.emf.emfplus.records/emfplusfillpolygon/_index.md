---
title: EmfPlusFillPolygon Class
type: docs
weight: 270
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Initializes a new instance of the [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that defines the brush, the content <br/>            of which is determined by the S bit in the Flags field. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| is_color | bool | r/w | Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). <br/>            If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. |
| is_compressed | bool | r/w | Gets or sets a value indicating whether this instance is compressed.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit <br/>            integer coordinates. If clear, PointData specifies absolute locations in the coordinate <br/>            space with 32-bit floating-point coordinates |
| is_relative | bool | r/w | Gets or sets a value indicating whether this instance is relative.<br/>            If set, each element in PointData specifies a location in the coordinate <br/>            space that is relative to the location specified by the previous element <br/>            in the array. In the case of the first element in PointData, a previous <br/>            location at coordinates (0,0) is assumed. If clear, PointData specifies <br/>            absolute locations according to the C flag |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the point data<br/>            An array of Count points that define the vertices of the polygon. <br/>            The first two points in the array specify the first side of the polygon. <br/>            Each additional point specifies a new side, the vertices of which <br/>            include the point and the previous point. If the last point and the <br/>            first point do not coincide, they specify the last side of the polygon. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Initializes a new instance of the [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

