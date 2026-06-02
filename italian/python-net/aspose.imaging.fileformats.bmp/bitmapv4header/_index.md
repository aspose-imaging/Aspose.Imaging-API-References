---
title: "Classe BitmapV4Header"
type: docs
weight: 30
url: /it/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

**Summary:** The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

**Inheritance:** BitmapInfoHeader

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
| red_mask | int | r/w | Ottiene o imposta la maschera di colore che specifica la componente rossa di ogni pixel, valida solo se bV4Compression è impostato su BI_BITFIELDS. |


