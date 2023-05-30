---
title: EmfStretchDiBits Class
type: docs
weight: 1380
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---

The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster <br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchDiBits

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfStretchDiBits type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfStretchDiBits(source)|Initializes a new instance of the EmfStretchDiBits class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            destination bounding rectangle in device units.|
|x_dest|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|y_dest|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|x_src|Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the upper-left <br/>            corner of the source rectangle.|
|y_src|Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the upper-left <br/>            corner of the source rectangle.|
|cx_src|Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle.|
|cy_src|Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle.|
|usage_src|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).|
|bit_blt_raster_operation|Gets or sets a 32-bit unsigned integer that specifies a raster operation <br/>            code. These codes define how the color data of the source rectangle is to be combined with <br/>            the color data of the destination rectangle and optionally a brush pattern, to achieve the final color.|
|cx_dest|Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle.|
|cy_dest|Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle.|
|source_bitmap|Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_STRETCHDIBITS record. Accordingly, fields in <br/>            this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
