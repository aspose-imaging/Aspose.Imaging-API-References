---
title: "Classe BitmapV4Header"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

**Summary:** The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

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
| alpha_mask | int | r/w | Obtient ou définit le masque de couleur qui spécifie le composant alpha de chaque pixel. |
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
| blue_mask | int | r/w | Obtient ou définit le masque de couleur qui spécifie le composant bleu de chaque pixel, valable uniquement si bV4Compression est défini sur BI_BITFIELDS. |
| cs_type | int | r/w | Obtient ou définit l'espace colorimétrique du DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | Obtient ou définit la classe CoordinatesTriple. |
| extra_bit_masks | int[] | r/w | Obtient ou définit les masques de bits supplémentaires.<br/>            Présent uniquement lorsque l'en-tête DIB est le BITMAPINFOHEADER et que [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) est défini sur soit [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) ou [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | Obtient ou définit le gamma bleu. |
| gamma_green | int | r/w | Obtient ou définit le gamma vert. |
| gamma_red | int | r/w | Obtient ou définit le gamma rouge. |
| green_mask | int | r/w | Obtient ou définit le masque de couleur qui spécifie le composant vert de chaque pixel, valable uniquement si bV4Compression est défini sur BI_BITFIELDS. |
| header_size | int | r/w | Obtient ou définit la taille de cette structure en octets. |
| red_mask | int | r/w | Obtient ou définit le masque de couleur qui spécifie le composant rouge de chaque pixel, valable uniquement si bV4Compression est défini sur BI_BITFIELDS. |


