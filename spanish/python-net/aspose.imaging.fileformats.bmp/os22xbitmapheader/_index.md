---
title: "Os22XBitmapHeader Clase"
type: docs
weight: 80
url: /es/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/
---

**Summary:** An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.Os22XBitmapHeader

**Inheritance:** BitmapInfoHeader

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | El tamaño del encabezado BITMAPCOREHEADER, también conocido como OS21XBITMAPHEADER |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | El tamaño del encabezado de información bitmap v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | El tamaño del encabezado de información bitmap v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | El tamaño del encabezado de información bitmap v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | El tamaño del encabezado de información bitmap v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | El tamaño del encabezado de información del bitmap v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | El tamaño del encabezado central del bitmap2 |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | El tamaño del encabezado central del bitmap2 |
| bitmap_colors_important | int | r/w | Obtiene o establece el número de colores importantes de la paleta. |
| bitmap_colors_used | int | r/w | Obtiene o establece el número de colores de la paleta utilizados. |
| bitmap_compression | int | r/w | Obtiene o establece la compresión del bitmap. |
| bitmap_height | int | r/w | Obtiene o establece la altura del bitmap. |
| bitmap_image_size | int | r/w | Obtiene o establece el tamaño de los datos sin procesar del bitmap en bytes. |
| bitmap_planes | int | r/w | Obtiene o establece el número de planos. |
| bitmap_width | int | r/w | Obtiene o establece el ancho del bitmap. |
| bitmap_x_pels_per_meter | int | r/w | Obtiene o establece la resolución horizontal de píxeles. |
| bitmap_y_pels_per_meter | int | r/w | Obtiene o establece la resolución vertical de píxeles. |
| bits_per_pixel | int | r/w | Obtiene o establece el recuento de bits por píxel. |
| color_encoding | int | r | Obtiene la codificación de color. |
| extra_bit_masks | int[] | r/w | Obtiene o establece las máscaras de bits adicionales.<br/>            Presentes solo en caso de que el encabezado DIB sea BITMAPINFOHEADER y que [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) esté configurado a [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) o [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| header_size | int | r/w | Obtiene o establece el tamaño de esta estructura en bytes. |
| identificador | int | r | Obtiene el identificador. |
| grabación | int | r | Obtiene la grabación. |
| renderizado | int | r | Obtiene el renderizado. |
| reservado | int | r | Obtiene el reservado. |
| size1 | int | r | Obtiene el size1. |
| size2 | int | r | Obtiene el size2. |
| unidades | int | r | Obtiene las unidades. |


