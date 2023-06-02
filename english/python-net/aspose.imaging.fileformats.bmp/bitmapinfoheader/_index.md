---
title: BitmapInfoHeader Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/
---

Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.

**Namespace:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Class Name:** aspose.imaging.fileformats.bmp.BitmapInfoHeader

**Assembly:**  Aspose.Imaging Version: 23.5.0

The BitmapInfoHeader type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|header_size|Gets or sets size of this structure in bytes.|
|bitmap_width|Gets or sets bitmap width.|
|bitmap_height|Gets or sets bitmap height.|
|bitmap_planes|Gets or sets number of planes.|
|bits_per_pixel|Gets or sets bits per pixel count.|
|BITMAP_CORE_HEADER_SIZE|The BITMAPCOREHEADER aka OS21XBITMAPHEADER header size|
|OS_22X_BITMAP_HEADER_SIZE|The bitmap core header2 size|
|OS_22X_BITMAP_HEADER_FULL_SIZE|The bitmap core header2 size|
|BITMAP_INFO_HEADER_SIZE|The bitmap information header size v3|
|BITMAP_INFO_HEADER_SIZE_V2|The bitmap information header size v2|
|BITMAP_INFO_HEADER_SIZE_V3|The bitmap information header size v3|
|BITMAP_INFO_HEADER_SIZE_V4|The bitmap information header size v4|
|BITMAP_INFO_HEADER_SIZE_V5|The bitmap information header size v5|
|bitmap_compression|Gets or sets bitmap compression.|
|bitmap_image_size|Gets or sets specifies bitmap raw data size in bytes.|
|bitmap_x_pels_per_meter|Gets or sets horizontal pixels resolution.|
|bitmap_y_pels_per_meter|Gets or sets vertical pixels resolution.|
|bitmap_colors_used|Gets or sets number of palette colors used.|
|bitmap_colors_important|Gets or sets number of important palette colors.|
|extra_bit_masks|Gets or sets the extra bit masks.<br/>            Present only in case the DIB header is the BITMAPINFOHEADER and the [bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) is set to either [BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) or [ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA).|
