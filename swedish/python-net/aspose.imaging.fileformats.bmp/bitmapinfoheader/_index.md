---
title: "BitmapInfoHeader klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/
---

**Summary:** Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapInfoHeader

**Inheritance:** BitmapCoreHeader

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | Storleken på BITMAPCOREHEADER, även kallad OS21XBITMAPHEADER |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | Bitmap‑informationshuvudets storlek v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | Bitmap‑informationshuvudets storlek v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | Bitmap‑informationshuvudets storlek v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | Bitmap‑informationshuvudets storlek v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | Den bitmap-informationens headerstorlek v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | Den bitmap-kärnheader2-storleken |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | Den bitmap-kärnheader2-storleken |
| bitmap_colors_important | int | r/w | Hämtar eller anger antalet viktiga palettfärger. |
| bitmap_colors_used | int | r/w | Hämtar eller anger antalet använda palettfärger. |
| bitmap_compression | int | r/w | Hämtar eller anger bitmap-komprimering. |
| bitmap_height | int | r/w | Hämtar eller anger bitmap-höjd. |
| bitmap_image_size | int | r/w | Hämtar eller anger bitmap-rawdatastorlek i byte. |
| bitmap_planes | int | r/w | Hämtar eller anger antalet plan. |
| bitmap_width | int | r/w | Hämtar eller anger bitmap-bredd. |
| bitmap_x_pels_per_meter | int | r/w | Hämtar eller anger horisontell pixelupplösning. |
| bitmap_y_pels_per_meter | int | r/w | Hämtar eller anger vertikal pixelupplösning. |
| bits_per_pixel | int | r/w | Hämtar eller anger antalet bitar per pixel. |
| extra_bit_masks | int[] | r/w | Hämtar eller anger de extra bitmaskerna.<br/>            Endast när DIB‑huvudet är BITMAPINFOHEADER och [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) är inställt på antingen [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) eller [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| header_size | int | r/w | Hämtar eller anger storleken på denna struktur i byte. |


