---
title: EmfMetafileHeader Class
type: docs
weight: 600
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---

The EMR_HEADER record types define the starting points of EMF metafiles<br/>            and specify properties of the device on which the image in the metafile<br/>            was created. The information in the header record makes it possible for<br/>            EMF metafiles to be independent of any specific output device.<br/>            The value of the Size field can be used to distinguish between the different<br/>            EMR_HEADER record types listed earlier in this section.<br/>            There are three possible headers:<br/>            The base header, which is the EmfMetafileHeader record.<br/>            The fixed-size part of this header is 88 bytes, and it contains a Header object.<br/>            The first extension header, which is the EmfMetafileHeaderExtension1 record.<br/>            The fixed-size part of this header is 100 bytes, and it contains a Header object<br/>            and a HeaderExtension1 object (section 2.2.10).<br/>            The second extension header, which is the EmfMetafileHeaderExtension2 record.<br/>            The fixed-size part of this header is 108 bytes, and it contains a Header object,<br/>            a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfMetafileHeader type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfMetafileHeader(record)|Initializes a new instance of the EmfMetafileHeader class|
|EmfMetafileHeader()|Initializes a new instance of the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) class.|
|EmfMetafileHeader(header)|Initializes a new instance of the EmfMetafileHeader class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|Gets or sets the type.|
|size|Gets or sets the size of the record|
|emf_header|Gets or sets a Header object (section 2.2.9), which contains information about the content<br/>            and structure of the metafile|
|emf_header_record_buffer|Gets or sets an optional array of bytes that contains the remainder of the EMF header record. <br/>            The size of this field MUST be a multiple of 4 bytes|
|emf_description_buffer|Gets or sets the EMF description buffer<br/>            An optional array of bytes that contains the EMF description string, which is <br/>            not required to be contiguous with the fixed portion of the EmfMetafileHeader <br/>            record. Accordingly, the field in this buffer that is labeled "UndefinedSpace" <br/>            is optional and MUST be ignored.|
|emf_description|Gets or sets the EMF description<br/>            An optional, null-terminated Unicode UTF16-LE string of arbitrary length and content. <br/>            Its location in the record and number of characters are specified by the offDescription <br/>            and nDescription fields, respectively, in EmfHeader. If the value of either field <br/>            is zero, no description string is present.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(record)|Initializes a new instance of the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) class.|
|create_from_type(type)|Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.|
|create_from_header(header)|Initializes a new instance of the [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) class.|
