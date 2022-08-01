---
title: EmfPlgBlt
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_PLGBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un paralelogramo de destino con la aplicación de un mapa de bits de máscara de color.
type: docs
weight: 3950
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

El registro EMR_PLGBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un paralelogramo de destino, con la aplicación de un mapa de bits de máscara de color.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlgBlt](emfplgblt)(EmfRecord) | Inicializa una nueva instancia del[`EmfPlgBlt`](../emfplgblt) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest) { get; set; } | Obtiene o establece una matriz de tres objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que especifica tres esquinas de un área de destino de paralelogramo para la transferencia en bloque. La esquina superior izquierda del rectángulo de origen se asigna al primer punto de esta matriz, la esquina superior derecha al segundo punto y la esquina inferior izquierda al tercer punto. La esquina inferior derecha del rectángulo de origen se asigna al cuarto punto implícito en el paralelogramo , que se calcula a partir de los tres primeros puntos (A, B y C) tratándolos como vectores . D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color) { get; set; } | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el color de fondo del mapa de bits de origen. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador , en unidades de dispositivo, para la salida al destino. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap) { get; set; } | Obtiene o establece un búfer que contiene el mapa de bits de máscara, que no requiere que sean contiguos a la parte fija del registro EMR_PLGBLT o entre sí. En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ignorarse. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap) { get; set; } | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no requiere que sean contiguos a la parte fija del registro EMR_PLGBLT o entre sí. En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ignorarse. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado del mapa de bits de la máscara. Este valor DEBE estar en la enumeración DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado del mapa de bits de origen. Este valor DEBE estar en DIBColors enumeration |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc) { get; set; } | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de origen. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de origen. |

### Ver también

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
