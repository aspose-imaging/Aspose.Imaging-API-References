---
title: EmfPlusDrawPath Class
type: docs
weight: 160
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---

The EmfPlusDrawPath record specifies drawing a graphics path.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPath

**Inheritance:** EmfPlusDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusDrawPath type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusDrawPath(source)](#EmfPlusDrawPath_source_0) | Initializes a new instance of the [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| object_id | byte | r/w | Gets or sets the object identifier.<br/>            The index of the EmfPlusPath object (section 2.2.1.6) to draw, in the<br/>            EMF+ Object Table. The value MUST be zero to 63, inclusive. |
| pen_id | int | r/w | Gets or sets the pen identifier<br/>            A 32-bit unsigned integer that specifies an index in the EMF+ Object Table<br/>            for an EmfPlusPen object (section 2.2.1.7) to use for drawing the EmfPlusPath.<br/>            The value MUST be zero to 63, inclusive |

### EmfPlusDrawPath(source) {#EmfPlusDrawPath_source_0}


```
 EmfPlusDrawPath(source) 
```

Initializes a new instance of the [EmfPlusDrawPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

