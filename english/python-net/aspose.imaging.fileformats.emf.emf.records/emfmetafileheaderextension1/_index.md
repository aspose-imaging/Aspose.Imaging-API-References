---
title: EmfMetafileHeaderExtension1 Class
type: docs
weight: 610
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfMetafileHeaderExtension1 type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfMetafileHeaderExtension1(header)|Initializes a new instance of the EmfMetafileHeaderExtension1 class|
|EmfMetafileHeaderExtension1(header)|Initializes a new instance of the EmfMetafileHeaderExtension1 class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|emf_header|Gets or sets a Header object (section 2.2.9), which contains information about the content<br/>            and structure of the metafile|
|emf_header_record_buffer|Gets or sets an optional array of bytes that contains the remainder of the EMF header record. <br/>            The size of this field MUST be a multiple of 4 bytes|
|emf_description_buffer|Gets or sets the EMF description buffer<br/>            An optional array of bytes that contains the EMF description string, which is <br/>            not required to be contiguous with the fixed portion of the EmfMetafileHeader <br/>            record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" <br/>            is optional and MUST be ignored.|
|emf_description|Gets or sets the EMF description<br/>            An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. <br/>            Its location in the record and number of characters are specified by the offDescription <br/>            and nDescription fields, respectively, in EmfHeader. If the value of either field <br/>            is zero, no description string is present.|
|emf_header_extension1|Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile.|
|emf_pixel_format_buffer|Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to<br/>            be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF <br/>            description string. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is <br/>            optional and MUST be ignored|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(record)|Initializes a new instance of the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) class.|
|create_from_type(type)|  |
|create_from_header(header)|Initializes a new instance of the [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.|
|create_from_header_extension1(header)|Initializes a new instance of the [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) class.|
