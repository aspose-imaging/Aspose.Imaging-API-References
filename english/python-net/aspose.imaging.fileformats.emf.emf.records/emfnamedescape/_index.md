---
title: EmfNamedEscape Class
type: docs
weight: 650
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---

The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfNamedEscape

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfNamedEscape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfNamedEscape(source)|Initializes a new instance of the EmfNamedEscape class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|escape|Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to<br/>            execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17).|
|cj_driver|Gets or sets A 32-bit unsigned integer that specifies the number of bytes in the<br/>            DriverName field. This value MUST be an even number.|
|cj_in|Gets or sets A 32-bit unsigned integer specifying the number of bytes to pass to the printer driver.|
|driver_name|Gets or sets A string of 16-bit Unicode characters that specifies the name of the<br/>            printer driver that will receive data. This value MUST be cjDriver bytes long, and it MUST be<br/>            terminated with a null character.|
|data|Gets or sets The data to pass to the printer driver. There MUST be cjIn bytes available.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
