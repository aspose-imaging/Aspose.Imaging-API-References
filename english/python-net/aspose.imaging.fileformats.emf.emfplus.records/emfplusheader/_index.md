---
title: EmfPlusHeader Class
type: docs
weight: 310
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusHeader type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusHeader(source)|Initializes a new instance of the EmfPlusHeader class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|dual_mode|Gets or sets a value indicating whether [dual mode].<br/>            If set, this flag indicates that this metafile is "dual-mode", which means<br/>             that it contains two sets of records, each of which completely specifies <br/>            the graphics content. If clear, the graphics content is specified by EMF+ <br/>            records, and possibly EMF records that are preceded by an EmfPlusGetDC record. <br/>            If this flag is set, EMF records alone SHOULD suffice to define the <br/>            graphics content. Note that whether the "dual-mode" flag is set or not, some <br/>            EMF records are always present, namely EMF control records and the EMF records <br/>            that contain EMF+ records. EMF control records are specified in [MS-EMF] <br/>            section 2.3.4.|
|video_display|Gets or sets a value indicating whether video display.<br/>            if set, this flag indicates that the metafile was recorded with a reference device<br/>            context for a video display. If clear, the metafile was recorded with a reference device<br/>            context for a printer.|
|emf_plus_flags|Gets or sets the EMF plus flags.<br/>            A 32-bit unsigned integer that contains information about how this metafile was recorded.<br/>            if 31-st bit of the field is set, this flag indicates that the metafile was recorded with <br/>            a reference device context for a video display. If clear, the metafile was recorded with<br/>             a reference device context for a printer.|
|logical_dpi_x|Gets or sets the logical dpi x.<br/>            A 32-bit unsigned integer that specifies the horizontal resolution for which the metafile <br/>            was recorded, in units of pixels per inch.|
|logical_dpi_y|Gets or sets the logical dpi y.<br/>            A 32-bit unsigned integer that specifies the vertical resolution for which the metafile <br/>            was recorded, in units of lines per inch|
|version|Gets or sets the version.<br/>            An EmfPlusGraphicsVersion object (section 2.2.2.19) that specifies the version of operating<br/>            system graphics that was used to create this metafile.|
|is_valid|Gets a value indicating whether this instance is valid.|
