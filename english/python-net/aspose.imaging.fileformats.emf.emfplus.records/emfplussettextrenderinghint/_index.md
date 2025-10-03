---
title: EmfPlusSetTextRenderingHint Class
type: docs
weight: 560
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/
---

**Summary:** The EmfPlusSetTextRenderingHint record specifies the quality of text rendering, including the type of anti-aliasing.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTextRenderingHint

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTextRenderingHint(source)](#EmfPlusSetTextRenderingHint_source_1) | Initializes a new instance of the [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| text_rendering_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Gets or sets the text rendering hint value, from the<br/>            TextRenderingHint enumeration (section 2.1.1.32), which specifies the quality to<br/>            use in subsequent text rendering. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusSetTextRenderingHint(source) {#EmfPlusSetTextRenderingHint_source_1}


```
 EmfPlusSetTextRenderingHint(source) 
```

Initializes a new instance of the [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

