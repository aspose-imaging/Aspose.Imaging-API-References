---
title: "Classe Os22XBitmapHeader"
type: docs
weight: 80
url: /it/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/
---

**Summary:** An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.Os22XBitmapHeader

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
| color_encoding | int | r | Ottiene la codifica del colore. |
| extra_bit_masks | int[] | r/w | Ottiene o imposta le maschere di bit aggiuntive.<br/>            Presenti solo nel caso in cui l'intestazione DIB sia BITMAPINFOHEADER e il [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) sia impostato su [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) o [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| header_size | int | r/w | Ottiene o imposta la dimensione di questa struttura in byte. |
| identificatore | int | r | Ottiene l'identificatore. |
| recording | int | r | Ottiene la registrazione. |
| rendering | int | r | Ottiene il rendering. |
| riservato | int | r | Ottiene il riservato. |
| size1 | int | r | Ottiene la size1. |
| size2 | int | r | Ottiene la size2. |
| unità | int | r | Ottiene le unità. |


