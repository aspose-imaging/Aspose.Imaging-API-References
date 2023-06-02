---
title: EmfCreateColorSpaceW Class
type: docs
weight: 270
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---

The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with<br/>            a name consisting of Unicode characters.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpaceW

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfCreateColorSpaceW type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCreateColorSpaceW(source)|Initializes a new instance of the EmfCreateColorSpaceW class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|ih_cs|Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space<br/>            object in the EMF object table (section 3.1.1.1). This index MUST be saved so that this object<br/>            can be reused or modified.|
|lcs|Gets or sets a WMF LogColorSpaceW object ([MS-WMF] section 2.2.2.12) that can specify<br/>            the name of a color profile in Unicode UTF16-LE characters|
|dw_flags|Gets or sets a 32-bit unsigned integer that provides information about the data in this record.|
|cb_data|Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field.|
|data|Gets or sets an optional array of bytes that specifies color profile data.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
