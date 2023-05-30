---
title: BitmapV4Header Class
type: docs
weight: 30
url: /python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.

**Namespace:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Class Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

**Assembly:**  Aspose.Imaging Version: 23.5.6

The BitmapV4Header type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|header_size|  |
|bitmap_width|  |
|bitmap_height|  |
|bitmap_planes|  |
|bits_per_pixel|  |
|BITMAP_CORE_HEADER_SIZE|  |
|OS_22X_BITMAP_HEADER_SIZE|  |
|OS_22X_BITMAP_HEADER_FULL_SIZE|  |
|BITMAP_INFO_HEADER_SIZE|  |
|BITMAP_INFO_HEADER_SIZE_V2|  |
|BITMAP_INFO_HEADER_SIZE_V3|  |
|BITMAP_INFO_HEADER_SIZE_V4|  |
|BITMAP_INFO_HEADER_SIZE_V5|  |
|bitmap_compression|Gets or sets bitmap compression.|
|bitmap_image_size|Gets or sets specifies bitmap raw data size in bytes.|
|bitmap_x_pels_per_meter|Gets or sets horizontal pixels resolution.|
|bitmap_y_pels_per_meter|Gets or sets vertical pixels resolution.|
|bitmap_colors_used|Gets or sets number of palette colors used.|
|bitmap_colors_important|Gets or sets number of important palette colors.|
|extra_bit_masks|Gets or sets the extra bit masks.<br/>            Present only in case the DIB header is the BITMAPINFOHEADER and the [bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) is set to either [BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) or [ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA).|
|red_mask|Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS.|
|green_mask|Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS.|
|blue_mask|Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS.|
|alpha_mask|Gets or sets the color mask that specifies the alpha component of each pixel.|
|cs_type|Gets or sets the color space of the DIB.|
|endpoints|Gets or sets the CoordinatesTriple class.|
|gamma_red|Gets or sets the gamma red.|
|gamma_green|Gets or sets the gamma green.|
|gamma_blue|Gets or sets the gamma blue.|
