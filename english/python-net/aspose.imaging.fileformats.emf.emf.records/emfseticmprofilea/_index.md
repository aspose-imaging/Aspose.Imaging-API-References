---
title: EmfSetIcmProfileA Class
type: docs
weight: 1140
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---

The EMR_SETICMPROFILEA record specifies a color profile in a file with a name consisting of ASCII<br/>            characters, for graphics output.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileA

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfSetIcmProfileA type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfSetIcmProfileA(source)|Initializes a new instance of the EmfSetIcmProfileA class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|dw_flags|Gets or sets a 32-bit unsigned integer that contains color profile flags.|
|cb_name|Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the ASCII<br/>            name of the desired color profile.|
|cb_data|Gets or sets a 32-bit unsigned integer that specifies the size of the color profile data, if it<br/>            is contained in the Data field.|
|data|Gets or sets an array of size (cbName + cbData) in bytes, which specifies the ASCII<br/>            name and raw data of the desired color profile.|
|name|Gets the name|
|raw_data|Gets the raw data|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
