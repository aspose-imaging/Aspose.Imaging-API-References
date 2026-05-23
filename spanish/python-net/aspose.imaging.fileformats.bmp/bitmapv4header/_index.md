---
title: "Clase BitmapV4Header"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/
---

**Summary:** The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV4Header

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
| alpha_mask | int | r/w | Obtiene o establece la máscara de color que especifica el componente alfa de cada píxel. |
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
| blue_mask | int | r/w | Obtiene o establece la máscara de color que especifica el componente azul de cada píxel, válido solo si bV4Compression está configurado a BI_BITFIELDS. |
| cs_type | int | r/w | Obtiene o establece el espacio de color del DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | Obtiene o establece la clase CoordinatesTriple. |
| extra_bit_masks | int[] | r/w | Obtiene o establece las máscaras de bits adicionales.<br/>            Presentes solo en caso de que el encabezado DIB sea BITMAPINFOHEADER y que [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) esté configurado a [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) o [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | Obtiene o establece la gamma azul. |
| gamma_green | int | r/w | Obtiene o establece la gamma verde. |
| gamma_red | int | r/w | Obtiene o establece la gamma roja. |
| green_mask | int | r/w | Obtiene o establece la máscara de color que especifica el componente verde de cada píxel, válido solo si bV4Compression está configurado a BI_BITFIELDS. |
| header_size | int | r/w | Obtiene o establece el tamaño de esta estructura en bytes. |
| red_mask | int | r/w | Obtiene o establece la máscara de color que especifica el componente rojo de cada píxel, válido solo si bV4Compression está configurado a BI_BITFIELDS. |


