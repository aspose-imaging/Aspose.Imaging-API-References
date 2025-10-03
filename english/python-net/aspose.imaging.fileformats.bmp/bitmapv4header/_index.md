---
title: BitmapV4Header Class
type: docs
weight: 30
url: /python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

**Summary:** The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

**Inheritance:** BitmapInfoHeader

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | The BITMAPCOREHEADER aka OS21XBITMAPHEADER header size |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | The bitmap information header size v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | The bitmap information header size v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | The bitmap information header size v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | The bitmap information header size v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | The bitmap information header size v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | The bitmap core header2 size |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | The bitmap core header2 size |
| alpha_mask | int | r/w | Gets or sets the color mask that specifies the alpha component of each pixel. |
| bitmap_colors_important | int | r/w | Gets or sets number of important palette colors. |
| bitmap_colors_used | int | r/w | Gets or sets number of palette colors used. |
| bitmap_compression | int | r/w | Gets or sets bitmap compression. |
| bitmap_height | int | r/w | Gets or sets bitmap height. |
| bitmap_image_size | int | r/w | Gets or sets specifies bitmap raw data size in bytes. |
| bitmap_planes | int | r/w | Gets or sets number of planes. |
| bitmap_width | int | r/w | Gets or sets bitmap width. |
| bitmap_x_pels_per_meter | int | r/w | Gets or sets horizontal pixels resolution. |
| bitmap_y_pels_per_meter | int | r/w | Gets or sets vertical pixels resolution. |
| bits_per_pixel | int | r/w | Gets or sets bits per pixel count. |
| blue_mask | int | r/w | Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| cs_type | int | r/w | Gets or sets the color space of the DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | Gets or sets the CoordinatesTriple class. |
| extra_bit_masks | int[] | r/w | Gets or sets the extra bit masks.<br/>            Present only in case the DIB header is the BITMAPINFOHEADER and the [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) is set to either [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) or [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | Gets or sets the gamma blue. |
| gamma_green | int | r/w | Gets or sets the gamma green. |
| gamma_red | int | r/w | Gets or sets the gamma red. |
| green_mask | int | r/w | Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| header_size | int | r/w | Gets or sets size of this structure in bytes. |
| red_mask | int | r/w | Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |


