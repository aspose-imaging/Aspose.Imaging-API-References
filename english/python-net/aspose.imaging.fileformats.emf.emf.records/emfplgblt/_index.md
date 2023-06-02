---
title: EmfPlgBlt Class
type: docs
weight: 740
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlgBlt type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlgBlt(source)|Initializes a new instance of the EmfPlgBlt class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            bounding rectangle, in device units, for output to the destination.|
|aptl_dest|Gets or sets an array of three WMF PointL objects ([MS-WMF] section 2.2.2.15) that <br/>            specifies three corners a parallelogram destination area for the block transfer.<br/>            The upper-left corner of the source rectangle is mapped to the first point in this array, the <br/>            upper-right corner to the second point, and the lower-left corner to the third point. The lower-right corner of the source rectangle is mapped to the implicit fourth point in the <br/>            parallelogram, which is computed from the first three points (A, B, and C) by treating them as <br/>            vectors. <br/>            D = B + C A|
|x_src|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the source rectangle.|
|y_src|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the source rectangle.|
|cx_src|Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle.|
|cy_src|Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle.|
|x_form_src|Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap.|
|bk_src_argb_32_color|Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the <br/>            background color of the source bitmap.|
|usage_src|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration|
|x_mask|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap.|
|y_mask|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap.|
|usage_mask|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the mask bitmap header. This value MUST be in the DIBColors enumeration.|
|source_bitmap|Gets or sets a buffer containing the source bitmap, which are not <br/>            required to be contiguous with the fixed portion of the EMR_PLGBLT record or with each other. <br/>            Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.|
|mask_bitmap|Gets or sets a buffer containing the mask bitmap, which are not <br/>            required to be contiguous with the fixed portion of the EMR_PLGBLT record or with each other. <br/>            Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
