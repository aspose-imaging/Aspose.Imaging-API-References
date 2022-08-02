---
title: WmfBitmapInfoHeader
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto BitmapInfoHeader contiene información sobre las dimensiones y el formato de color de un mapa de bits DIB independiente del dispositivo.
type: docs
weight: 8470
url: /es/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

El objeto BitmapInfoHeader contiene información sobre las dimensiones y el formato de color de un mapa de bits (DIB) independiente del dispositivo.

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que define el formato de de cada píxel y el número máximo de colores en el DIB. Este value DEBE estar en el[`BitCount`](../wmfbitmapbaseheader/bitcount) Enumeración (apartado 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que define el número de índices de color necesarios para mostrar el DIB. Si este valor es cero, se requieren todos los índices de color |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número de índices en la tabla de colores que usa el DIB, como sigue : Si este valor es cero, el DIB usa el número máximo de colores que corresponden al valor BitCount. Si este valor es distinto de cero y el valor de BitCount es menor que 16, este valor especifica el número de colores utilizados por el DIB. Si este valor es distinto de cero y el valor de BitCount es 16 o mayor, este valor especifica el tamaño del color table utilizado para optimizar el rendimiento de la paleta del sistema. Nota Si este valor es distinto de cero y mayor que el tamaño máximo posible de la tabla de colores según el valor BitCount , se DEBERÍA asumir el tamaño máximo de la tabla de colores. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que define el modo de compresión del DIB. Este valor DEBE estar en la Enumeración de compresión (sección 2.1.1.7). Este valor NO DEBE especificar un formato comprimido si el DIB es un mapa de bits de arriba hacia abajo, como lo indica el valor de Altura. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que define el tamaño de este objeto , en bytes. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | Obtiene o establece un entero de 32 bits con signo que define la altura del DIB, en píxeles. Este valor NO DEBE ser cero. Si este valor es positivo, el DIB es un mapa de bits de abajo hacia arriba y su origen es la esquina inferior izquierda. Si este valor es negativo, el DIB es un mapa de bits de arriba hacia abajo y su origen es la esquina superior izquierda. Los mapas de bits de arriba hacia abajo no admiten compresión. Este campo DEBERÍA especificar la altura del archivo de imagen descomprimido, si el valor de Compresión especifica formato JPEG o PNG . |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que define el tamaño, en bytes, de la imagen. Si el valor de compresión es BI_RGB, este valor DEBE ser cero y DEBE ignorarse. Si el valor de compresión es BI_JPEG o BI_PNG, este valor DEBE especificar el tamaño del búfer de imagen JPEG o PNG, respectivamente. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que define el número de planes para el dispositivo de destino. Este valor DEBE ser 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | Obtiene o establece un entero con signo de 32 bits que define el ancho del DIB, en píxeles. Este valor DEBE ser positivo. Este campo DEBE especificar el ancho del archivo de imagen descomprimido, si el valor de Compresión especifica formato JPEG o PNG . |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | Obtiene o establece un entero con signo de 32 bits que define la resolución horizontal, en píxeles por metro, del dispositivo target para DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | Obtiene o establece un entero con signo de 32 bits que define la resolución vertical, en píxeles por metro, del dispositivo target para DIB |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | El tamaño de la estructura |

### Ver también

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* espacio de nombres [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
