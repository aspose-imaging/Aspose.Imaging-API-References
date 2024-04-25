---
title: EmfTransparentBlt
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_TRANSPARENTBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino  tratando un color específico como transparente estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino si es necesario
type: docs
weight: 4640
url: /es/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

El registro EMR_TRANSPARENTBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , tratando un color específico como transparente, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si es necesario

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt)(EmfRecord) | Inicializa una nueva instancia del[`EmfTransparentBlt`](../emftransparentblt) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades de dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la altura lógica del rectángulo de destino. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la altura lógica del rectángulo de origen. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap) { get; set; } | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo a la parte fija del registro EMR_TRANSPARENTBLT. En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ignorarse. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color) { get; set; } | Obtiene o establece un objeto WMF ColorRef que especifica el color de fondo del mapa de bits de origen. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color) { get; set; } | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color en el mapa de bits de origen que se tratará como transparente. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9) |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de destino. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc) { get; set; } | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de origen. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de destino. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de origen. |

### Ver también

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
