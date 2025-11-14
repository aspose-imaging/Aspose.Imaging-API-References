---
title: EmfPlusSetAntiAliasMode Class
type: docs
weight: 450
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---

**Summary:** The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetAntiAliasMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetAntiAliasMode(source)](#EmfPlusSetAntiAliasMode_source_1) | Initializes a new instance of the [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| anti_aliasing | bool | r/w | Gets or sets a value indicating whether [anti aliasing].<br/>            If set, anti-aliasing SHOULD be performed.<br/>            If clear, anti-aliasing SHOULD NOT be performed. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| smoothing_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Gets or sets the smoothing mode.<br/>            (7 bits): The smoothing mode value, from the SmoothingMode enumeration (section 2.1.1.28) |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusSetAntiAliasMode(source) {#EmfPlusSetAntiAliasMode_source_1}


```
 EmfPlusSetAntiAliasMode(source) 
```

Initializes a new instance of the [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

