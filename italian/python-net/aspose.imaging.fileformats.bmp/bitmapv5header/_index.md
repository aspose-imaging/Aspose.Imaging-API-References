---
title: "Classe BitmapV5Header"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/
---

**Summary:** The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed.<br/>            The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). <br/>            See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, <br/>            and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. <br/>            The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, <br/>            because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. <br/>            (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory.<br/>            For packed DIBs, the profile data should follow the bitmap bits similar to the file format. <br/>            The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER.<br/>            Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV5Header

**Inheritance:** BitmapV4Header

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | La dimensione dell'intestazione BITMAPCOREHEADER, nota anche come OS21XBITMAPHEADER |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | La dimensione dell'intestazione delle informazioni bitmap v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | La dimensione dell'intestazione delle informazioni bitmap v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | La dimensione dell'intestazione delle informazioni bitmap v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | La dimensione dell'intestazione delle informazioni bitmap v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | La dimensione dell'intestazione delle informazioni bitmap v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | La dimensione dell'intestazione core bitmap2 |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | La dimensione dell'intestazione core bitmap2 |
| alpha_mask | int | r/w | Ottiene o imposta la maschera di colore che specifica il componente alfa di ogni pixel. |
| bitmap_colors_important | int | r/w | Ottiene o imposta il numero di colori importanti della palette. |
| bitmap_colors_used | int | r/w | Ottiene o imposta il numero di colori della palette utilizzati. |
| bitmap_compression | int | r/w | Ottiene o imposta la compressione bitmap. |
| bitmap_height | int | r/w | Ottiene o imposta l'altezza del bitmap. |
| bitmap_image_size | int | r/w | Ottiene o imposta la dimensione dei dati grezzi bitmap in byte. |
| bitmap_planes | int | r/w | Ottiene o imposta il numero di piani. |
| bitmap_width | int | r/w | Ottiene o imposta la larghezza del bitmap. |
| bitmap_x_pels_per_meter | int | r/w | Ottiene o imposta la risoluzione orizzontale dei pixel. |
| bitmap_y_pels_per_meter | int | r/w | Ottiene o imposta la risoluzione verticale dei pixel. |
| bits_per_pixel | int | r/w | Ottiene o imposta il conteggio dei bit per pixel. |
| blue_mask | int | r/w | Ottiene o imposta la maschera di colore che specifica la componente blu di ogni pixel, valida solo se bV4Compression è impostato su BI_BITFIELDS. |
| cs_type | int | r/w | Ottiene o imposta lo spazio colore del DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | Ottiene o imposta la classe CoordinatesTriple. |
| extra_bit_masks | int[] | r/w | Ottiene o imposta le maschere di bit aggiuntive.<br/>            Presenti solo nel caso in cui l'intestazione DIB sia BITMAPINFOHEADER e il [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) sia impostato su [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) o [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | Ottiene o imposta il gamma blu. |
| gamma_green | int | r/w | Ottiene o imposta il gamma verde. |
| gamma_red | int | r/w | Ottiene o imposta il gamma rosso. |
| green_mask | int | r/w | Ottiene o imposta la maschera di colore che specifica la componente verde di ogni pixel, valida solo se bV4Compression è impostato su BI_BITFIELDS. |
| header_size | int | r/w | Ottiene o imposta la dimensione di questa struttura in byte. |
| intent | int | r/w | Ottiene o imposta l'intento di rendering per il bitmap. |
| profile_data | int | r/w | Ottiene o imposta i dati del profilo. |
| profile_size | int | r/w | Ottiene o imposta la dimensione del profilo. |
| red_mask | int | r/w | Ottiene o imposta la maschera di colore che specifica la componente rossa di ogni pixel, valida solo se bV4Compression è impostato su BI_BITFIELDS. |
| riservato | int | r/w | Ottiene o imposta il membro riservato. |


