---
title: "BitmapV5Header-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/
---

**Summary:** The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed.<br/>            The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). <br/>            See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, <br/>            and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. <br/>            The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, <br/>            because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. <br/>            (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory.<br/>            For packed DIBs, the profile data should follow the bitmap bits similar to the file format. <br/>            The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER.<br/>            Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV5Header

**Inheritance:** BitmapV4Header

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
| alpha_mask | int | r/w | Hämtar eller anger färgmasken som specificerar alfakomponenten för varje pixel. |
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
| blue_mask | int | r/w | Hämtar eller anger färgmasken som specificerar den blå komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI_BITFIELDS. |
| cs_type | int | r/w | Hämtar eller anger färgrymden för DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | Hämtar eller anger CoordinatesTriple-klassen. |
| extra_bit_masks | int[] | r/w | Hämtar eller anger de extra bitmaskerna.<br/>            Endast när DIB‑huvudet är BITMAPINFOHEADER och [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) är inställt på antingen [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) eller [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | Hämtar eller anger blå gamma. |
| gamma_green | int | r/w | Hämtar eller anger grön gamma. |
| gamma_red | int | r/w | Hämtar eller anger röd gamma. |
| green_mask | int | r/w | Hämtar eller anger färgmasken som specificerar den gröna komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI_BITFIELDS. |
| header_size | int | r/w | Hämtar eller anger storleken på denna struktur i byte. |
| intent | int | r/w | Hämtar eller anger renderingsintentionen för bitmap. |
| profile_data | int | r/w | Hämtar eller anger profildata. |
| profile_size | int | r/w | Hämtar eller anger storleken på profilen. |
| red_mask | int | r/w | Hämtar eller anger färgmasken som specificerar den röda komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI_BITFIELDS. |
| reserverad | int | r/w | Hämtar eller anger den reserverade medlemmen. |


