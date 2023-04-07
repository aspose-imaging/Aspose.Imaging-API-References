---
title: EmfEof Class
type: docs
weight: 380
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfEof type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfEof(record)|Initializes a new instance of the EmfEof class|
|EmfEof()|Initializes a new instance of the [EmfEof](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfeof/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|palette_argb_32_entries|Gets or sets an optional buffer that contains palette data, which is not <br/>            required to be contiguous with the fixed portion of the EMR_EOF <br/>            record. Accordingly, fields in this buffer that are labeled <br/>            "UndefinedSpace" are optional and MUST be ignored. <br/>            The size of this field MUST be a multiple of 4 bytes|
|size_last|Gets or sets a 32-bit unsigned integer that MUST be the same as Size and MUST be the last <br/>            field of the record and hence the metafile. LogPaletteEntry objects, if they <br/>            exist, MUST precede this field.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
