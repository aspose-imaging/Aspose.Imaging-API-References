---
title: "Класс BitmapInfoHeader"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/
---

**Summary:** Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapInfoHeader

**Inheritance:** BitmapCoreHeader

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | Размер заголовка BITMAPCOREHEADER, также известного как OS21XBITMAPHEADER |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | Размер заголовка информации битмапа v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | Размер заголовка информации битмапа v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | Размер заголовка информации битмапа v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | Размер заголовка информации битмапа v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | Размер заголовка информации битмапа v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | Размер bitmap core header2 |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | Размер bitmap core header2 |
| bitmap_colors_important | int | r/w | Получает или задает количество важных цветов палитры. |
| bitmap_colors_used | int | r/w | Получает или задает количество используемых цветов палитры. |
| bitmap_compression | int | r/w | Получает или задает сжатие битмапа. |
| bitmap_height | int | r/w | Получает или задает высоту битмапа. |
| bitmap_image_size | int | r/w | Получает или задает размер необработанных данных битмапа в байтах. |
| bitmap_planes | int | r/w | Получает или задает количество плоскостей. |
| bitmap_width | int | r/w | Получает или задает ширину битмапа. |
| bitmap_x_pels_per_meter | int | r/w | Получает или задает горизонтальное разрешение в пикселях на метр. |
| bitmap_y_pels_per_meter | int | r/w | Получает или задает вертикальное разрешение в пикселях на метр. |
| bits_per_pixel | int | r/w | Получает или задает количество бит на пиксель. |
| extra_bit_masks | int[] | r/w | Получает или задает дополнительные битовые маски.<br/>            Присутствует только в случае, когда заголовок DIB является BITMAPINFOHEADER и [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) установлен либо в [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB), либо в [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| header_size | int | r/w | Получает или задает размер этой структуры в байтах. |


