---
title: Os22XBitmapHeader Class
type: docs
weight: 80
url: /python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/
---

**Summary:** An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.Os22XBitmapHeader

**Inheritance:** BitmapInfoHeader

**Aspose.Imaging Version:** 23.6

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | The BITMAPCOREHEADER aka OS21XBITMAPHEADER header size |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | The bitmap information header size v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | The bitmap information header size v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | The bitmap information header size v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | The bitmap information header size v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | The bitmap information header size v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | The bitmap core header2 size |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | The bitmap core header2 size |
| bitmap_colors_important | uint | r/w | Gets or sets number of important palette colors. |
| bitmap_colors_used | uint | r/w | Gets or sets number of palette colors used. |
| bitmap_compression | uint | r/w | Gets or sets bitmap compression. |
| bitmap_height | int | r/w | Gets or sets bitmap height. |
| bitmap_image_size | uint | r/w | Gets or sets specifies bitmap raw data size in bytes. |
| bitmap_planes | ushort | r/w | Gets or sets number of planes. |
| bitmap_width | int | r/w | Gets or sets bitmap width. |
| bitmap_x_pels_per_meter | int | r/w | Gets or sets horizontal pixels resolution. |
| bitmap_y_pels_per_meter | int | r/w | Gets or sets vertical pixels resolution. |
| bits_per_pixel | ushort | r/w | Gets or sets bits per pixel count. |
| color_encoding | int | r | Gets the color encoding. |
| extra_bit_masks | int | r/w | Gets or sets the extra bit masks.<br/>            Present only in case the DIB header is the BITMAPINFOHEADER and the [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) is set to either [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) or [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| header_size | uint | r/w | Gets or sets size of this structure in bytes. |
| identifier | int | r | Gets the identifier. |
| recording | int | r | Gets the recording. |
| rendering | int | r | Gets the rendering. |
| reserved | int | r | Gets the reserved. |
| size1 | int | r | Gets the size1. |
| size2 | int | r | Gets the size2. |
| units | int | r | Gets the units. |


