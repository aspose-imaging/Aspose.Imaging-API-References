---
title: "BitmapInfoHeader 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/
---

**Summary:** Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapInfoHeader

**Inheritance:** BitmapCoreHeader

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
| extra_bit_masks | int[] | r/w | 获取或设置额外的位掩码。<br/>            仅在 DIB 标头为 BITMAPINFOHEADER 且 [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) 设置为 [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)（RGB）或 [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)（RGBA）时出现。 |
| header_size | int | r/w | 获取或设置此结构的字节大小。 |


