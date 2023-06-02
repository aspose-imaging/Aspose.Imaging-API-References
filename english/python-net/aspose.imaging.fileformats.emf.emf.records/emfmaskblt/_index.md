---
title: EmfMaskBlt Class
type: docs
weight: 590
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfMaskBlt type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfMaskBlt(source)|Initializes a new instance of the EmfMaskBlt class|
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
|rop4|Gets or sets a quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.|
|x_src|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle.|
|y_src|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle.|
|xform_src|Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap.|
|argb_32_bk_color_src|Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the <br/>            background color of the source bitmap.|
|usage_src|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).|
|x_mask|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap.|
|y_mask|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap.|
|usage_mask|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the mask bitmap header. This value MUST be in the DIBColors enumeration.|
|source_bitmap|Gets or sets a buffer containing the source bitmaps, which are not <br/>            required to be contiguous with the fixed portion of the EMR_MASKBLT record or with each <br/>            other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and <br/>            MUST be ignored.|
|mask_bitmap|Gets or sets a buffer containing the mask bitmaps, which are not <br/>            required to be contiguous with the fixed portion of the EMR_MASKBLT record or with each <br/>            other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and <br/>            MUST be ignored.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
