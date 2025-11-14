---
title: EmfPlusDrawLines Class
type: docs
weight: 150
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Initializes a new instance of the [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Gets or sets a value indicating whether [closed shape]. |
| compressed | bool | r/w | Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is compressed.<br/>            This bit indicates whether the PointData field specifies compressed data.<br/>            If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. <br/>            If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates<br/>            Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+<br/>            Object Table to draw the lines. The value MUST be zero to 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the point data<br/>            An array of Count points that specify the starting and ending points of the lines to be drawn. |
| relative | bool | r/w | Gets or sets a value indicating whether this [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) is relative.<br/>            This bit indicates whether the PointData field specifies relative or absolute locations.<br/>            If set, each element in PointData specifies a location in the coordinate space that is relative <br/>            to the location specified by the previous element in the array. In the case of the first <br/>            element in PointData, a previous location at coordinates (0,0) is assumed. If clear, <br/>            PointData specifies absolute locations according to the C flag.<br/>            Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Initializes a new instance of the [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

