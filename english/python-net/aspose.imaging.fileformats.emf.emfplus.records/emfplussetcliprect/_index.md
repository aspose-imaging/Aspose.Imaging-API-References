---
title: EmfPlusSetClipRect Class
type: docs
weight: 470
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---

The EmfPlusSetClipRect record combines the current clipping region with a rectangle.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRect

**Inheritance:** EmfPlusClippingRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusSetClipRect type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusSetClipRect(source)](#EmfPlusSetClipRect_source_0) | Initializes a new instance of the [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. See the<br/>            CombineMode enumeration (section 2.1.1.4) for the meanings of the values. |
| clip_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r/w | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines the rectangle to<br/>            use in the CombineMode operation. |

### EmfPlusSetClipRect(source) {#EmfPlusSetClipRect_source_0}


```
 EmfPlusSetClipRect(source) 
```

Initializes a new instance of the [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

