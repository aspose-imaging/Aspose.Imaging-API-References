---
title: EmfColorMatchToTargetW Class
type: docs
weight: 140
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---

The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color<br/>            profile that is specified in a file with a name consisting of Unicode characters.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorMatchToTargetW

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfColorMatchToTargetW type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfColorMatchToTargetW(source)|Initializes a new instance of the EmfColorMatchToTargetW class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|dw_action|Gets or sets a 32-bit unsigned integer that specifies a value from the ColorSpace<br/>            enumeration (section 2.1.7).|
|dw_flags|Gets or sets a 32-bit unsigned integer that specifies a value from the<br/>            ColorMatchToTarget enumeration (section 2.1.6).|
|cb_name|Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode<br/>            UTF16-LE name of the desired color profile.|
|cb_data|Gets or sets a 32-bit unsigned integer that specifies the size of the raw data of the target<br/>            color profile, if it is contained in the Data field.|
|data|Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE<br/>            name and raw data of the desired color profile.|
|name|Gets the name|
|raw_data|Gets the raw data|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
