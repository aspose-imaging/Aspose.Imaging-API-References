---
title: "BitmapV4Header 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

**Summary:** The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

**Inheritance:** BitmapInfoHeader

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | BITMAPCOREHEADER（亦称 OS21XBITMAPHEADER）头部大小 |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | 位图信息头大小 v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | 位图信息头大小 v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | 位图信息头大小 v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | 位图信息头大小 v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | 位图信息头大小 v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | 位图核心 header2 大小 |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | 位图核心 header2 大小 |
| alpha_mask | int | r/w | 获取或设置指定每个像素的 alpha 分量的颜色掩码。 |
| bitmap_colors_important | int | r/w | 获取或设置重要调色板颜色的数量。 |
| bitmap_colors_used | int | r/w | 获取或设置已使用的调色板颜色数量。 |
| bitmap_compression | int | r/w | 获取或设置位图压缩方式。 |
| bitmap_height | int | r/w | 获取或设置位图高度。 |
| bitmap_image_size | int | r/w | 获取或设置位图原始数据大小（字节）。 |
| bitmap_planes | int | r/w | 获取或设置平面的数量。 |
| bitmap_width | int | r/w | 获取或设置位图宽度。 |
| bitmap_x_pels_per_meter | int | r/w | 获取或设置水平像素分辨率。 |
| bitmap_y_pels_per_meter | int | r/w | 获取或设置垂直像素分辨率。 |
| bits_per_pixel | int | r/w | 获取或设置每像素位数。 |
| blue_mask | int | r/w | 获取或设置指定每个像素蓝色分量的颜色掩码，仅当 bV4Compression 设置为 BI_BITFIELDS 时有效。 |
| cs_type | int | r/w | 获取或设置 DIB 的颜色空间。 |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | 获取或设置 CoordinatesTriple 类。 |
| extra_bit_masks | int[] | r/w | 获取或设置额外的位掩码。<br/>            仅在 DIB 标头为 BITMAPINFOHEADER 且 [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) 设置为 [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)（RGB）或 [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)（RGBA）时出现。 |
| gamma_blue | int | r/w | 获取或设置蓝色伽马。 |
| gamma_green | int | r/w | 获取或设置绿色伽马。 |
| gamma_red | int | r/w | 获取或设置红色伽马。 |
| green_mask | int | r/w | 获取或设置指定每个像素绿色分量的颜色掩码，仅当 bV4Compression 设置为 BI_BITFIELDS 时有效。 |
| header_size | int | r/w | 获取或设置此结构的字节大小。 |
| red_mask | int | r/w | 获取或设置指定每个像素红色分量的颜色掩码，仅当 bV4Compression 设置为 BI_BITFIELDS 时有效。 |


