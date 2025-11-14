---
title: EmfPlusSave Class
type: docs
weight: 420
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---

**Summary:** The EmfPlusSave record saves the graphics state, identified by a specified index, on a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSave

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSave(source)](#EmfPlusSave_source_1) | Initializes a new instance of the [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| stack_index | int | r/w | Gets or sets a 32-bit unsigned integer that specifies a level to associate with the<br/>            graphics state. The level value can be used by a subsequent EmfPlusRestore record (section<br/>            2.3.7.4) operation to retrieve the graphics state. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusSave(source) {#EmfPlusSave_source_1}


```
 EmfPlusSave(source) 
```

Initializes a new instance of the [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

