---
title: EmfTransparentBlt Class
type: docs
weight: 1420
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---

The EMR_TRANSPARENTBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, treating a specified color as transparent, stretching or compressing the output <br/>            to fit the dimensions of the destination, if necessary

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfTransparentBlt

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfTransparentBlt type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfTransparentBlt(source)|Initializes a new instance of the EmfTransparentBlt class|
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
|transparent_argb_32_color|Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies <br/>            the color in the source bitmap to be treated as transparent.|
|x_src|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle.|
|y_src|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle.|
|xform_src|Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap.|
|src_bk_argb_32_color|Gets or sets a WMF ColorRef object that specifies the background color of the source bitmap.|
|usage_src|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9)|
|cx_src|Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle.|
|cy_src|Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle.|
|source_bitmap|Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_TRANSPARENTBLT record. Accordingly, fields in <br/>            this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
