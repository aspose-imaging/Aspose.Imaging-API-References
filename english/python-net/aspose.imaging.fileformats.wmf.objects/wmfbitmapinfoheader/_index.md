---
title: WmfBitmapInfoHeader Class
type: docs
weight: 70
url: /python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Namespace:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/)

**Full Class Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Assembly:**  Aspose.Imaging Version: 23.3.0

The WmfBitmapInfoHeader type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|WmfBitmapInfoHeader()|Initializes a new instance of the WmfBitmapInfoHeader class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|header_size|Gets or sets a 32-bit unsigned integer that defines the size of this<br/>                object, in bytes.|
|planes|Gets or sets a 16-bit unsigned integer that defines the number of<br/>                [None](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) for the target device. This value MUST be<br/>                0x0001.|
|bit_count|Gets or sets a 16-bit unsigned integer that defines the format of<br/>                each pixel, and the maximum number of colors in the DIB. This value<br/>                MUST be in the [bit_count](/imaging/python-net/api-reference/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) Enumeration (section 2.1.1.3).|
|width|Gets or sets a 32-bit signed integer that defines the width of the DIB, in pixels. This value MUST be positive.<br/>                This field SHOULD specify the width of the decompressed image file, if the Compression value specifies JPEG or PNG<br/>                format.|
|height|Gets or sets  32-bit signed integer that defines the height of the DIB, in pixels. This value MUST NOT be zero.<br/>                If this value is positive, the DIB is a bottom-up bitmap, and its origin is the lower-left corner.<br/>                If this value is negative, the DIB is a top-down bitmap, and its origin is the upper-left corner. Top-down bitmaps<br/>                do not support compression.<br/>                This field SHOULD specify the height of the decompressed image file, if the Compression value specifies JPEG or PNG<br/>                format.|
|compression|Gets or sets a 32-bit unsigned integer that defines the compression mode of the DIB. This value MUST be in the<br/>                Compression Enumeration (section 2.1.1.7).<br/>                This value MUST NOT specify a compressed format if the DIB is a top-down bitmap, as indicated by the Height value.|
|image_size|Gets or sets a 32-bit unsigned integer that defines the size, in bytes, of the image.<br/>                If the Compression value is BI_RGB, this value SHOULD be zero and MUST be ignored.<br/>                If the Compression value is BI_JPEG or BI_PNG, this value MUST specify the size of the JPEG or PNG image buffer,<br/>                respectively.|
|x_pels_per_meter|Gets or sets a 32-bit signed integer that defines the horizontal resolution, in pixels-per-meter, of the target<br/>                device for the DIB|
|y_pels_per_meter|Gets or sets a 32-bit signed integer that defines the vertical resolution, in pixels-per-meter, of the target<br/>                device for the DIB|
|color_used|Gets or sets a 32-bit unsigned integer that specifies the number of indexes in the color table used by the DIB, as<br/>                follows:<br/>                If this value is zero, the DIB uses the maximum number of colors that correspond to the BitCount value.<br/>                If this value is nonzero and the BitCount value is less than 16, this value specifies the number of colors used by<br/>                the DIB.<br/>                If this value is nonzero and the BitCount value is 16 or greater, this value specifies the size of the color table<br/>                used to optimize performance of the system palette.<br/>                Note If this value is nonzero and greater than the maximum possible size of the color table based on the BitCount<br/>                value, the maximum color table size SHOULD be assumed.|
|color_important|Gets or sets a 32-bit unsigned integer that defines the number of color indexes that are required for displaying<br/>                the DIB.<br/>                If this value is zero, all color indexes are required|
|STRUCTURE_SIZE|The structure size|
