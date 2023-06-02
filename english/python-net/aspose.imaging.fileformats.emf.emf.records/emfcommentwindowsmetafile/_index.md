---
title: EmfCommentWindowsMetaFile Class
type: docs
weight: 230
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfCommentWindowsMetaFile type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCommentWindowsMetaFile(source)|Initializes a new instance of the EmfCommentWindowsMetaFile class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|data_size|  |
|comment_identifier|Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies <br/>            this as an EMR_COMMENT_PUBLIC record.|
|public_comment_identifier|Gets or sets a 32-bit unsigned integer that identifies the type of <br/>            public comment record. This SHOULD be one of the values listed in the preceding table, which <br/>            are specified in the EmrComment enumeration (section 2.1.10), unless additional public <br/>            comment record types have been implemented on the print server.|
|version|Gets or sets a 16-bit unsigned integer that specifies the WMF metafile version in terms <br/>            of support for device-independent bitmaps (DIBs), from the WMF MetafileVersion <br/>            enumeration ([MS-WMF] section 2.1.1.19).|
|checksum|Gets or sets a 32-bit unsigned integer that specifies the checksum for this record.|
|flags|Gets or sets a 32-bit value that MUST be 0x00000000 and MUST be ignored.|
|win_metafile_size|Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the <br/>            WMF metafile in the WinMetafile field.|
|win_metafile|Gets or sets a buffer that contains the WMF metafile.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
