---
title: EmfSetIcmProfileW Class
type: docs
weight: 1150
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---

The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of<br/>            Unicode characters, for graphics output.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileW

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfSetIcmProfileW type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfSetIcmProfileW(source)|Initializes a new instance of the EmfSetIcmProfileW class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|dw_flags|Gets or sets a 32-bit unsigned integer that contains color profile flags.|
|cb_name|Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode<br/>            UTF16-LE name of the desired color profile.|
|cb_data|Gets or sets a 32-bit unsigned integer that specifies the size of color profile data, if attached.|
|data|Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE<br/>            name and raw data of the desired color profile.|
|name|Gets the name|
|raw_data|Gets the raw data|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
