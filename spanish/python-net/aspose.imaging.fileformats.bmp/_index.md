---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /es/python-net/aspose.imaging.fileformats.bmp/
---


El módulo gestiona el procesamiento del formato de archivo Bmp.

## **Classes**
| **Clase** | **Descripción** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | Dimensiones y formato de color de DIB.<br/> Nombre del encabezado BITMAPCOREHEADER también conocido como OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | Especifica BITMAPINFOHEADER. <br/> Soporte del SO: Windows NT, 3.1x o posterior.<br/> Características: Añade formatos de 16 bpp y 32 bpp. Añade compresión RLE. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | La estructura BitmapV4Header es el archivo de encabezado de información de mapa de bits. Es una versión ampliada de la estructura BITMAPINFOHEADER.<br/> <br/>La estructura BitmapV4Header se amplía para permitir que una imagen JPEG o PNG se pase como imagen de origen a StretchDIBits.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | La estructura BitmapV5Header es el archivo de encabezado de información de mapa de bits. Es una versión ampliada de la estructura BITMAPINFOHEADER.<br/> <br/>Si bV5Height es negativo, lo que indica un DIB de arriba a abajo, bV5Compression debe ser BI_RGB o BI_BITFIELDS. Los DIB de arriba a abajo no pueden comprimirse.<br/> La interfaz Independent Color Management (ICM) 2.0 permite que los perfiles de color del International Color Consortium (ICC) se enlacen o incrusten en los DIB (DIB). <br/> Consulte Using Structures para más información. Cuando un DIB se carga en memoria, los datos del perfil (si están presentes) deben seguir a la tabla de colores, <br/> y bV5ProfileData debe proporcionar el desplazamiento de los datos del perfil desde el comienzo de la estructura BITMAPV5HEADER. <br/> El valor almacenado en bV5ProfileData será diferente del valor devuelto por el operador sizeof con el argumento BITMAPV5HEADER, <br/> porque bV5ProfileData es el desplazamiento en bytes desde el inicio de la estructura BITMAPV5HEADER hasta el comienzo de los datos del perfil. <br/> (Los bits del mapa de bits no siguen a la tabla de colores en memoria). Las aplicaciones deben modificar el miembro bV5ProfileData después de cargar el DIB en memoria.<br/> Para DIB empaquetados, los datos del perfil deben seguir a los bits del mapa de bits de forma similar al formato de archivo. <br/> El miembro bV5ProfileData aún debe proporcionar el desplazamiento de los datos del perfil desde el comienzo de la BITMAPV5HEADER.<br/> Las aplicaciones deben acceder a los datos del perfil solo cuando bV5Size sea igual al tamaño de la BITMAPV5HEADER y bV5CSType sea PROFILE_EMBEDDED o PROFILE_LINKED.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | Puede manejar sin esfuerzo archivos Bitmap (BMP) y Device Independent Bitmap<br/> (DIB), facilitando la manipulación y el procesamiento eficientes de imágenes raster.<br/> Al realizar diversas operaciones sobre las imágenes, esta API simplifica el<br/> flujo de trabajo, ofreciendo a los desarrolladores un conjunto de herramientas fiable para trabajar con los formatos BMP y<br/> DIB en sus aplicaciones de software. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | Un OS/2 2.x OS22XBITMAPHEADER también conocido como BITMAPCOREHEADER2. |
## **Enumerations**
| **Enumeración** | **Descripción** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Especifica diferentes métodos de compresión de bitmap. |
