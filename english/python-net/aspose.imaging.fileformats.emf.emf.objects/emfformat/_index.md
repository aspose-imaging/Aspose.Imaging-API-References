---
title: EmfFormat Class
type: docs
weight: 60
url: /python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Namespace:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfFormat type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfFormat()|Initializes a new instance of the EmfFormat class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|signature|Gets or sets a 32-bit unsigned integer that specifies the format of the image data. <br/>            This value MUST be in the FormatSignature enumeration (section 2.1.14).|
|version|Gets or sets a 32-bit unsigned integer that specifies the format version number. <br/>            If the Signature field specifies encapsulated PostScript (EPS), <br/>            this value MUST be 0x00000001; otherwise, this value MUST be ignored|
|size_data|Gets or sets a 32-bit unsigned integer that specifies the size of the data in bytes|
|off_data|Gets or sets 32-bit unsigned integer that specifies the offset to the data from the <br/>            start of the identifier field in an EMR_COMMENT_PUBLIC record (section 2.3.3.4). <br/>            The offset MUST be 32-bit aligned.|
