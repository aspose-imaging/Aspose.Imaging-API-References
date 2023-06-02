---
title: EmfCommentMultiFormats Class
type: docs
weight: 200
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---

The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentMultiFormats

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfCommentMultiFormats type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCommentMultiFormats(source)|Initializes a new instance of the EmfCommentMultiFormats class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|data_size|  |
|comment_identifier|Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies <br/>            this as an EMR_COMMENT_PUBLIC record.|
|public_comment_identifier|Gets or sets a 32-bit unsigned integer that identifies the type of <br/>            public comment record. This SHOULD be one of the values listed in the preceding table, which <br/>            are specified in the EmrComment enumeration (section 2.1.10), unless additional public <br/>            comment record types have been implemented on the print server.|
|output_rect|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the <br/>            output rectangle, in logical coordinates.|
|a_formats|Gets or sets a CountFormats length array of graphics formats, specified by <br/>            EmrFormat objects (section 2.2.4), in order of preference|
|format_data|Gets or sets a variable-length array of bytes of image data for all graphics formats <br/>            contained in this record. <br/>            The size of the data for each image is provided by the DataSize field in the corresponding <br/>            EmrFormat object. Thus, the total size of this field is the sum of DataSize values in all <br/>            EmrFormat objects. <br/>            The graphics format of the data for each image is specified by the Signature field in the <br/>            corresponding EmrFormat object.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
