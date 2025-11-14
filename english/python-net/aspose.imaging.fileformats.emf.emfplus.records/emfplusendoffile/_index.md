---
title: EmfPlusEndOfFile Class
type: docs
weight: 220
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---

**Summary:** The EmfPlusEndOfFile record specifies the end of EMF+ data in the metafile.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndOfFile

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusEndOfFile(source)](#EmfPlusEndOfFile_source_1) | Initializes a new instance of the [EmfPlusEndOfFile](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero<br/>            and MUST be ignored upon receipt |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusEndOfFile(source) {#EmfPlusEndOfFile_source_1}


```
 EmfPlusEndOfFile(source) 
```

Initializes a new instance of the [EmfPlusEndOfFile](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

