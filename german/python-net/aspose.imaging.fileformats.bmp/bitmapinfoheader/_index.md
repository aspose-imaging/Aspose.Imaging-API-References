---
title: "BitmapInfoHeader Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/
---

**Summary:** Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapInfoHeader

**Inheritance:** BitmapCoreHeader

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | Die BITMAPCOREHEADER, auch bekannt als OS21XBITMAPHEADER, Headergröße |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | Die Bitmap-Informations-Headergröße v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | Die Bitmap-Informations-Headergröße v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | Die Bitmap-Informations-Headergröße v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | Die Bitmap-Informations-Headergröße v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | Die Bitmap-Informations-Headergröße v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | Die Bitmap-Core-Header2-Größe |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | Die Bitmap-Core-Header2-Größe |
| bitmap_colors_important | int | r/w | Liest oder setzt die Anzahl wichtiger Palettenfarben. |
| bitmap_colors_used | int | r/w | Liest oder setzt die Anzahl der verwendeten Palettenfarben. |
| bitmap_compression | int | r/w | Liest oder setzt die Bitmap-Kompression. |
| bitmap_height | int | r/w | Liest oder setzt die Bitmap-Höhe. |
| bitmap_image_size | int | r/w | Liest oder setzt die Größe der rohen Bitmap-Daten in Bytes. |
| bitmap_planes | int | r/w | Liest oder setzt die Anzahl der Ebenen. |
| bitmap_width | int | r/w | Liest oder setzt die Bitmap-Breite. |
| bitmap_x_pels_per_meter | int | r/w | Liest oder setzt die horizontale Pixelauflösung. |
| bitmap_y_pels_per_meter | int | r/w | Liest oder setzt die vertikale Pixelauflösung. |
| bits_per_pixel | int | r/w | Liest oder setzt die Bits‑pro‑Pixel‑Anzahl. |
| extra_bit_masks | int[] | r/w | Liest oder setzt die zusätzlichen Bitmasken.<br/>            Nur vorhanden, wenn der DIB‑Header der BITMAPINFOHEADER ist und die [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) entweder auf [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) oder auf [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA) gesetzt ist. |
| header_size | int | r/w | Liest oder setzt die Größe dieser Struktur in Bytes. |


