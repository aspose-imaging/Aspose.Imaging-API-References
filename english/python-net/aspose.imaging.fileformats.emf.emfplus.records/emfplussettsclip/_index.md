---
title: EmfPlusSetTsClip Class
type: docs
weight: 570
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---

The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsClip

**Inheritance:** EmfPlusTerminalServerRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusSetTsClip type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusSetTsClip(source)](#EmfPlusSetTsClip_source_0) | Initializes a new instance of the [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| compressed | bool | r | Gets a value indicating whether this [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) is compressed.<br/>            This bit specifies the format of the rectangle data in the rects field. If set, each<br/>            rectangle is defined in 4 bytes. If clear, each rectangle is defined in 8 bytes. |
| num_rects | short | r | Gets the number rects.<br/>            This field specifies the number of rectangles that are defined in the rect field. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets an array of NumRects rectangles that define clipping areas. The format of<br/>            this data is determined by the C bit in the Flags field. |

### EmfPlusSetTsClip(source) {#EmfPlusSetTsClip_source_0}


```
 EmfPlusSetTsClip(source) 
```

Initializes a new instance of the [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

