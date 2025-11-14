---
title: EmfPlusSetCompositingMode Class
type: docs
weight: 490
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---

**Summary:** The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetCompositingMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetCompositingMode(source)](#EmfPlusSetCompositingMode_source_1) | Initializes a new instance of the [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Gets or sets the compositing mode value, from the CompositingMode<br/>            enumeration (section 2.1.1.5). Compositing can be expressed as the state of alpha<br/>            blending, which can either be on or off. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusSetCompositingMode(source) {#EmfPlusSetCompositingMode_source_1}


```
 EmfPlusSetCompositingMode(source) 
```

Initializes a new instance of the [EmfPlusSetCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

