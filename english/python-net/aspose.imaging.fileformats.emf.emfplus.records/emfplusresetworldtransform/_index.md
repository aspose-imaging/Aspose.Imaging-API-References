---
title: EmfPlusResetWorldTransform Class
type: docs
weight: 390
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetworldtransform/
---

**Summary:** The EmfPlusResetWorldTransform record resets the current world space transform to the identify matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusResetWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

**Aspose.Imaging Version:** 23.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusResetWorldTransform(source)](#EmfPlusResetWorldTransform_source_1) | Initializes a new instance of the [EmfPlusResetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetworldtransform/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusResetWorldTransform(source) {#EmfPlusResetWorldTransform_source_1}


```
 EmfPlusResetWorldTransform(source) 
```

Initializes a new instance of the [EmfPlusResetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetworldtransform/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

