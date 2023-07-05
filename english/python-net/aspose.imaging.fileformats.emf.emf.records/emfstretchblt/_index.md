---
title: EmfStretchBlt Class
type: docs
weight: 1370
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---

The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchBlt

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfStretchBlt type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfStretchBlt(source)|Initializes a new instance of the EmfStretchBlt class|
|EmfStretchBlt()|Initializes a new instance of the [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            destination bounding rectangle in device units.|
|x_dest|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|y_dest|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|cx_dest|Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle.|
|cy_dest|Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle.|
|bit_blt_raster_operation|Gets or sets a 32-bit unsigned integer that specifies the raster operation <br/>            code. This code defines how the color data of the source rectangle is to be combined with the <br/>            color data of the destination rectangle and optionally a brush pattern, to achieve the final color|
|x_src|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle.|
|y_src|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle.|
|xform_src|Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap.|
|argb_32_bk_color_src|Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the <br/>            background color of the source bitmap.|
|usage_src|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).|
|cx_src|Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle.|
|cy_src|Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle.|
|source_bitmap|Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_STRETCHBLT record. Accordingly, fields in this <br/>            buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.|
|src_rect|Gets or sets the source rect.|
|dest_rect|Gets or sets the dest rect.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
