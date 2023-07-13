---
title: EmfPlusSetWorldTransform Class
type: docs
weight: 590
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---

The EmfPlusSetWorldTransform record sets the world transform according to the values in a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

**Aspose.Imaging Version:** 23.6

The EmfPlusSetWorldTransform type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPlusSetWorldTransform(source)](#EmfPlusSetWorldTransform_source_0) | Initializes a new instance of the [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| flags | short | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix) | r/w | Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the<br/>            new current world transform. |

### EmfPlusSetWorldTransform(source) {#EmfPlusSetWorldTransform_source_0}


```
 EmfPlusSetWorldTransform(source) 
```

Initializes a new instance of the [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

