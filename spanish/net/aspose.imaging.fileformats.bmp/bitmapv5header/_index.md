---
title: BitmapV5Header
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La estructura BitmapV5Header es el archivo de encabezado de información de mapa de bits. Es una versión extendida de la estructura BITMAPINFOHEADER. Si bV5Height es negativo lo que indica un DIB de arriba hacia abajo bV5Compression debe ser BI_RGB o BI_BITFIELDS. Los DIB de arriba hacia abajo no se pueden comprimir. La interfaz de administración de color independiente ICM 2.0 permite que los perfiles de color del International Color Consortium ICC se vinculen o incrusten en DIB DIB. Consulte Uso de estructuras para obtener más información. Cuando se carga un DIB en la memoria los datos del perfil si están presentes deben seguir la tabla de colores y bV5ProfileData debe proporcionar el desplazamiento de los datos del perfil desde el comienzo de la estructura BITMAPV5HEADER. El valor almacenado en bV5ProfileData será diferente del valor devuelto por el operador sizeof dado el argumento BITMAPV5HEADER porque bV5ProfileData es el desplazamiento en bytes desde el comienzo de la estructura BITMAPV5HEADER hasta el comienzo de los datos del perfil. los bits del mapa de bits no siguen la tabla de colores en la memoria. Las aplicaciones deben modificar el miembro bV5ProfileData después de cargar el DIB en la memoria. Para los DIB empaquetados los datos del perfil deben seguir los bits de mapa de bits similares al formato de archivo. El miembro bV5ProfileData aún debe proporcionar el desplazamiento de los datos de perfil desde el principio de BITMAPV5HEADER. Las aplicaciones deben acceder a los datos de perfil solo cuando bV5Size es igual al tamaño de BITMAPV5HEADER y bV5CSType es igual a PROFILE_EMBEDDED o PROFILE_LINKED.
type: docs
weight: 1370
url: /es/net/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

La estructura BitmapV5Header es el archivo de encabezado de información de mapa de bits. Es una versión extendida de la estructura BITMAPINFOHEADER. Si bV5Height es negativo, lo que indica un DIB de arriba hacia abajo, bV5Compression debe ser BI_RGB o BI_BITFIELDS. Los DIB de arriba hacia abajo no se pueden comprimir. La interfaz de administración de color independiente (ICM) 2.0 permite que los perfiles de color del International Color Consortium (ICC) se vinculen o incrusten en DIB (DIB). Consulte Uso de estructuras para obtener más información. Cuando se carga un DIB en la memoria, los datos del perfil (si están presentes) deben seguir la tabla de colores, y bV5ProfileData debe proporcionar el desplazamiento de los datos del perfil desde el comienzo de la estructura BITMAPV5HEADER. El valor almacenado en bV5ProfileData será diferente del valor devuelto por el operador sizeof dado el argumento BITMAPV5HEADER, porque bV5ProfileData es el desplazamiento en bytes desde el comienzo de la estructura BITMAPV5HEADER hasta el comienzo de los datos del perfil. (los bits del mapa de bits no siguen la tabla de colores en la memoria). Las aplicaciones deben modificar el miembro bV5ProfileData después de cargar el DIB en la memoria. Para los DIB empaquetados, los datos del perfil deben seguir los bits de mapa de bits similares al formato de archivo. El miembro bV5ProfileData aún debe proporcionar el desplazamiento de los datos de perfil desde el principio de BITMAPV5HEADER. Las aplicaciones deben acceder a los datos de perfil solo cuando bV5Size es igual al tamaño de BITMAPV5HEADER y bV5CSType es igual a PROFILE_EMBEDDED o PROFILE_LINKED.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Obtiene o establece la máscara de color que especifica el componente alfa de cada píxel. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Obtiene o establece el número de colores importantes de la paleta. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Obtiene o establece el número de colores de la paleta utilizados. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Obtiene o establece la compresión de mapa de bits. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Obtiene o establece la altura del mapa de bits. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Obtiene o establece especifica el tamaño de los datos sin formato de mapa de bits en bytes. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Obtiene o establece el número de planos. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Obtiene o establece el ancho del mapa de bits. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Obtiene o establece la resolución de píxeles horizontales. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Obtiene o establece la resolución de píxeles verticales. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Obtiene o establece el número de bits por píxel. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Obtiene o establece la máscara de color que especifica el componente azul de cada píxel, válido solo si bV4Compression se establece en BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | Obtiene o establece el espacio de color del DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | Obtiene o establece la clase CoordinatesTriple. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Obtiene o establece las máscaras de bits adicionales. Presente solo en caso de que el encabezado DIB sea BITMAPINFOHEADER y el[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) está configurado para cualquieraBitfields (RGB) oAlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Obtiene o establece el azul gamma. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Obtiene o establece el verde gamma. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Obtiene o establece el rojo gamma. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Obtiene o establece la máscara de color que especifica el componente verde de cada píxel, válido solo si bV4Compression se establece en BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Obtiene o establece el tamaño de esta estructura en bytes. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Obtiene o establece el intento de representación del mapa de bits. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Obtiene o establece los datos del perfil. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Obtiene o establece el tamaño del perfil. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Obtiene o establece la máscara de color que especifica el componente rojo de cada píxel, válido solo si bV4Compression se establece en BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Obtiene o establece el miembro reservado. |

### Ver también

* class [BitmapV4Header](../bitmapv4header)
* espacio de nombres [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
