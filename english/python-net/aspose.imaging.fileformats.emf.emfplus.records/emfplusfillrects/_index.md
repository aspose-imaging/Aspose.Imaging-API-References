---
title: EmfPlusFillRects Class
type: docs
weight: 280
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---

The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRects

**Inheritance:** EmfPlusDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusFillRects type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusFillRects(source)](#EmfPlusFillRects_source_0) | Initializes a new instance of the [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| is_color | bool | r/w | Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1).<br/>            If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table |
| compressed | bool | r/w | Gets or sets a value indicating whether this [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) is compressed.<br/>            If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData<br/>             contains an EmfPlusRectF object (section 2.2.2.39) object |
| brush_id | int | r/w | Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef) | r/w | Gets or sets the rectangle data<br/>            An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data. |

### EmfPlusFillRects(source) {#EmfPlusFillRects_source_0}


```
 EmfPlusFillRects(source) 
```

Initializes a new instance of the [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

