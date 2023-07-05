---
title: EmfMetafileHeaderExtension2 Class
type: docs
weight: 620
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/
---

The EmfMetafileHeaderExtension2 record is the header record used in the second extension to EMF<br/>            metafiles. Following the EmfHeaderExtension2 field, the remaining fields are optional and<br/>            can be present in any order.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension2

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfMetafileHeaderExtension2 type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfMetafileHeaderExtension2(header)|Initializes a new instance of the EmfMetafileHeaderExtension2 class|
|EmfMetafileHeaderExtension2(header)|Initializes a new instance of the EmfMetafileHeaderExtension2 class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|emf_header|  |
|emf_header_record_buffer|  |
|emf_description_buffer|  |
|emf_description|  |
|emf_header_extension1|Gets or sets a HeaderExtension1 object, which specifies additional information about the image in the metafile.|
|emf_pixel_format_buffer|Gets or sets an optional array of bytes that contains the EMF pixel format descriptor, which is not required to<br/>            be contiguous with the fixed portion of the EmfMetafileHeaderExtension1 record or with the EMF <br/>            description string. Accordingly, the field in this buffer that is labeled "UndefinedSpace" is <br/>            optional and MUST be ignored|
|emf_header_extension2|Gets or sets a HeaderExtension2 object, which specifies additional information about the image in the metafile|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(record)|  |
|create_from_type(type)|  |
|create_from_header(header)|Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.|
|create_from_header_extension1(header)|Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.|
|create_from_header_extension2(header)|Initializes a new instance of the [EmfMetafileHeaderExtension2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/) class.|
