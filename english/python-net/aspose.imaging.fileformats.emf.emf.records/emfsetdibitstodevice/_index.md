---
title: EmfSetDiBitsToDevice Class
type: docs
weight: 1120
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---

The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of <br/>            a source bitmap to a destination rectangle.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetDiBitsToDevice

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfSetDiBitsToDevice type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfSetDiBitsToDevice(source)|Initializes a new instance of the EmfSetDiBitsToDevice class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|bounds|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the <br/>            destination bounding rectangle in device units.|
|x_dest|Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|y_dest|Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left <br/>            corner of the destination rectangle.|
|x_src|Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the lower-left <br/>            corner of the source rectangle.|
|y_src|Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the lower-left <br/>            corner of the source rectangle.|
|cx_src|Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle.|
|cy_src|Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle|
|usage_src|Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the <br/>            color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).|
|start_scan|Gets or sets a 32-bit unsigned integer that specifies the first scan line in the array.|
|c_scans|Gets or sets a 32-bit unsigned integer that specifies the number of scan lines.|
|source_bitmap|Gets or sets a buffer containing the source bitmap, which is not required to be <br/>            contiguous with the fixed portion of the EMR_SETDIBITSTODEVICE record. Accordingly, fields <br/>            in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
