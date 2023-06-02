---
title: EmfExtEscape Class
type: docs
weight: 430
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfextescape/
---

The EMR_EXTESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will not result in drawing being done.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtEscape

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfExtEscape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfExtEscape(source)|Initializes a new instance of the EmfExtEscape class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|escape|Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to<br/>            execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17).|
|cj_in|Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver.|
|data|Gets or sets the data to pass to the printer driver. There MUST be cjIn bytes available.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
