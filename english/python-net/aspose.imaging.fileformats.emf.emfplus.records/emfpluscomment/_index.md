---
title: EmfPlusComment Class
type: docs
weight: 50
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---

The EmfPlusComment record specifies arbitrary private data.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusComment

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfPlusComment type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusComment(source)|Initializes a new instance of the EmfPlusComment class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|Gets a 16-bit unsigned integer that identifies the record type.|
|flags|Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero<br/>            and MUST be ignored upon receipt|
|size|Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data.|
|data_size|Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header.|
|private_data|Gets or sets a DataSize-length byte array of private data.<br/>            bytes of record-specific data that follows.|
