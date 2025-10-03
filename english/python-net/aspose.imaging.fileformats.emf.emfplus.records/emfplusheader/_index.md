---
title: EmfPlusHeader Class
type: docs
weight: 310
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Initializes a new instance of the [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| dual_mode | bool | r/w | Gets or sets a value indicating whether [dual mode].<br/>            If set, this flag indicates that this metafile is "dual-mode", which means<br/>             that it contains two sets of records, each of which completely specifies <br/>            the graphics content. If clear, the graphics content is specified by EMF+ <br/>            records, and possibly EMF records that are preceded by an EmfPlusGetDC record. <br/>            If this flag is set, EMF records alone SHOULD suffice to define the <br/>            graphics content. Note that whether the "dual-mode" flag is set or not, some <br/>            EMF records are always present, namely EMF control records and the EMF records <br/>            that contain EMF+ records. EMF control records are specified in [MS-EMF] <br/>            section 2.3.4. |
| emf_plus_flags | int | r/w | Gets or sets the EMF plus flags.<br/>            A 32-bit unsigned integer that contains information about how this metafile was recorded.<br/>            if 31-st bit of the field is set, this flag indicates that the metafile was recorded with <br/>            a reference device context for a video display. If clear, the metafile was recorded with<br/>             a reference device context for a printer. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| is_valid | bool | r | Gets a value indicating whether this instance is valid. |
| logical_dpi_x | int | r/w | Gets or sets the logical dpi x.<br/>            A 32-bit unsigned integer that specifies the horizontal resolution for which the metafile <br/>            was recorded, in units of pixels per inch. |
| logical_dpi_y | int | r/w | Gets or sets the logical dpi y.<br/>            A 32-bit unsigned integer that specifies the vertical resolution for which the metafile <br/>            was recorded, in units of lines per inch |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Gets or sets the version.<br/>            An EmfPlusGraphicsVersion object (section 2.2.2.19) that specifies the version of operating<br/>            system graphics that was used to create this metafile. |
| video_display | bool | r/w | Gets or sets a value indicating whether video display.<br/>            if set, this flag indicates that the metafile was recorded with a reference device<br/>            context for a video display. If clear, the metafile was recorded with a reference device<br/>            context for a printer. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Initializes a new instance of the [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

