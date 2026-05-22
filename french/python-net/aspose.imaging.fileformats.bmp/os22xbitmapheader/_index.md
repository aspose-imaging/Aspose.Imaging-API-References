---
title: "Classe Os22XBitmapHeader"
type: docs
weight: 80
url: /fr/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/
---

**Summary:** An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.Os22XBitmapHeader

**Inheritance:** BitmapInfoHeader

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | La taille de l'en-tête BITMAPCOREHEADER également appelé OS21XBITMAPHEADER |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | La taille de l'en-tête d'information bitmap v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | La taille de l'en-tête d'information bitmap v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | La taille de l'en-tête d'information bitmap v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | La taille de l'en-tête d'information bitmap v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | La taille de l'en-tête d'information du bitmap v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | La taille de l'en-tête principal du bitmap2 |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | La taille de l'en-tête principal du bitmap2 |
| bitmap_colors_important | int | r/w | Obtient ou définit le nombre de couleurs de palette importantes. |
| bitmap_colors_used | int | r/w | Obtient ou définit le nombre de couleurs de palette utilisées. |
| bitmap_compression | int | r/w | Obtient ou définit la compression du bitmap. |
| bitmap_height | int | r/w | Obtient ou définit la hauteur du bitmap. |
| bitmap_image_size | int | r/w | Obtient ou définit la taille des données brutes du bitmap en octets. |
| bitmap_planes | int | r/w | Obtient ou définit le nombre de plans. |
| bitmap_width | int | r/w | Obtient ou définit la largeur du bitmap. |
| bitmap_x_pels_per_meter | int | r/w | Obtient ou définit la résolution horizontale en pixels. |
| bitmap_y_pels_per_meter | int | r/w | Obtient ou définit la résolution verticale en pixels. |
| bits_per_pixel | int | r/w | Obtient ou définit le nombre de bits par pixel. |
| color_encoding | int | r | Obtient le codage couleur. |
| extra_bit_masks | int[] | r/w | Obtient ou définit les masques de bits supplémentaires.<br/>            Présent uniquement lorsque l'en-tête DIB est le BITMAPINFOHEADER et que [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) est défini sur soit [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) ou [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| header_size | int | r/w | Obtient ou définit la taille de cette structure en octets. |
| identifiant | int | r | Obtient l'identifiant. |
| enregistrement | int | r | Obtient l'enregistrement. |
| rendu | int | r | Obtient le rendu. |
| réservé | int | r | Obtient le réservé. |
| size1 | int | r | Obtient la taille1. |
| size2 | int | r | Obtient la taille2. |
| unités | int | r | Obtient les unités. |


