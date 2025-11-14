---
title: EmfPlusSetInterpolationMode Class
type: docs
weight: 510
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---

**Summary:** The EmfPlusSetInterpolationMode record specifies how image scaling, including stretching and shrinking, is performed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetInterpolationMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetInterpolationMode(source)](#EmfPlusSetInterpolationMode_source_1) | Initializes a new instance of the [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| interpolation_mode | [EmfPlusInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/) | r/w | Gets or sets the interpolation mode value, from the InterpolationMode enumeration (section 2.1.1.16). |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusSetInterpolationMode(source) {#EmfPlusSetInterpolationMode_source_1}


```
 EmfPlusSetInterpolationMode(source) 
```

Initializes a new instance of the [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

