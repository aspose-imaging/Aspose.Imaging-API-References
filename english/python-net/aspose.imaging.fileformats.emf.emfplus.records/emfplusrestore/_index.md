---
title: EmfPlusRestore Class
type: docs
weight: 400
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---

The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRestore

**Inheritance:** EmfPlusStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusRestore type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusRestore(source)](#EmfPlusRestore_source_0) | Initializes a new instance of the [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| stack_index | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the level associated with a<br/>            graphics state. The level value was assigned to the graphics state by a previous EmfPlusSave record (section 2.3.7.5). |

### EmfPlusRestore(source) {#EmfPlusRestore_source_0}


```
 EmfPlusRestore(source) 
```

Initializes a new instance of the [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

