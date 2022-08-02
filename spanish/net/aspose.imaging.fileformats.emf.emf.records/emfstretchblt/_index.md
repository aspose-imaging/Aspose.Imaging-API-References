---
title: EmfStretchBlt
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_STRETCHBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino  opcionalmente en combinación con un patrón de pincel de acuerdo con una operación raster especificada estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino si es necesario .
type: docs
weight: 4590
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

El registro EMR_STRETCHBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel, de acuerdo con una operación raster especificada, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si es necesario .

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfStretchBlt](emfstretchblt#constructor)() | Inicializa una nueva instancia del[`EmfStretchBlt`](../emfstretchblt) clase. |
| [EmfStretchBlt](emfstretchblt#constructor_1)(EmfRecord) | Inicializa una nueva instancia del[`EmfStretchBlt`](../emfstretchblt) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc) { get; set; } | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8 que especifica el color de fondo del mapa de bits de origen. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el código de operación ráster . Este código define cómo se combinarán los datos de color del rectángulo de origen con los datos de color del rectángulo de destino y, opcionalmente, un patrón de pincel, para lograr el color final. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades de dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la altura lógica del rectángulo de destino. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect) { get; set; } | Obtiene o establece el dest rect. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap) { get; set; } | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo a la parte fija del registro EMR_STRETCHBLT. En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ignorarse. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect) { get; set; } | Obtiene o establece la fuente rect. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de destino. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc) { get; set; } | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de origen. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de destino. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de origen. |

### Ver también

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
