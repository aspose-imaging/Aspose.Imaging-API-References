---
title: "Класс BitmapV5Header"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/
---

**Summary:** The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed.<br/>            The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). <br/>            See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, <br/>            and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. <br/>            The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, <br/>            because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. <br/>            (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory.<br/>            For packed DIBs, the profile data should follow the bitmap bits similar to the file format. <br/>            The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER.<br/>            Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV5Header

**Inheritance:** BitmapV4Header

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
| intent | int | r/w | Получает или задает цель отображения для bitmap. |
| profile_data | int | r/w | Получает или задает данные профиля. |
| profile_size | int | r/w | Получает или задает размер профиля. |
| red_mask | int | r/w | Получает или задает цветовую маску, указывающую красный компонент каждого пикселя, действительна только если bV4Compression установлен в BI_BITFIELDS. |
| зарезервировано | int | r/w | Получает или задает зарезервированный член. |


