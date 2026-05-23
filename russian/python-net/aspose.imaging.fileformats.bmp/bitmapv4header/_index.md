---
title: "Класс BitmapV4Header"
type: docs
weight: 30
url: /ru/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

**Summary:** The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

**Inheritance:** BitmapInfoHeader

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
| alpha_mask | int | r/w | Получает или задает маску цвета, указывающую альфа‑компонент каждого пикселя. |
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
| blue_mask | int | r/w | Получает или задает цветовую маску, указывающую синий компонент каждого пикселя, действительна только если bV4Compression установлен в BI_BITFIELDS. |
| cs_type | int | r/w | Получает или задает цветовое пространство DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | Получает или задает класс CoordinatesTriple. |
| extra_bit_masks | int[] | r/w | Получает или задает дополнительные битовые маски.<br/>            Присутствует только в случае, когда заголовок DIB является BITMAPINFOHEADER и [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) установлен либо в [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB), либо в [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | Получает или задает гамму синего. |
| gamma_green | int | r/w | Получает или задает гамму зеленого. |
| gamma_red | int | r/w | Получает или задает гамму красного. |
| green_mask | int | r/w | Получает или задает цветовую маску, указывающую зеленый компонент каждого пикселя, действительна только если bV4Compression установлен в BI_BITFIELDS. |
| header_size | int | r/w | Получает или задает размер этой структуры в байтах. |
| red_mask | int | r/w | Получает или задает цветовую маску, указывающую красный компонент каждого пикселя, действительна только если bV4Compression установлен в BI_BITFIELDS. |


