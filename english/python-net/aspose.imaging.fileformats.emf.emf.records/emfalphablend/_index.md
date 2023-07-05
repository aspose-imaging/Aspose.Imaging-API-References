---
title: EmfAlphaBlend Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfAlphaBlend type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfAlphaBlend(source)|Initializes a new instance of the EmfAlphaBlend class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            destination bounding rectangle in device units.|
|x_dest|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|y_dest|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|cx_dest|Gets or sets a 32-bit signed integer that specifies the logical width of the destination <br/>            rectangle. This value MUST be greater than zero.|
|cy_dest|Gets or sets a 32-bit signed integer that specifies the logical height of the destination <br/>            rectangle. This value MUST be greater than zero.|
|blend_function|Gets or sets a structure that specifies the blending operations for source and <br/>            destination bitmaps|
|x_src|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle.|
|y_src|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle.|
|xform_sr|Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap.|
|bk_src_argb_32_color|Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the<br/>            background color of the source bitmap.|
|usage_src|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).|
|cx_src|Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. <br/>            This value MUST be greater than zero.|
|cy_src|Gets or sets a 32-bit signed integer that specifies the logical height of the source <br/>            rectangle. This value MUST be greater than zero.|
|source_bitmap|Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_ALPHABLEND record. Accordingly, fields in this <br/>            buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
