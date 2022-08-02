---
title: EmfMaskBlt
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_MASKBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino  opcionalmente en combinación con un patrón de pincel y con la aplicación de un mapa de bits de máscara de color  de acuerdo con las operaciones de trama de fondo y primer plano especificadas.
type: docs
weight: 3800
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

El registro EMR_MASKBLT especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel y con la aplicación de un mapa de bits de máscara de color , de acuerdo con las operaciones de trama de fondo y primer plano especificadas.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfMaskBlt](emfmaskblt)(EmfRecord) | Inicializa una nueva instancia del[`EmfMaskBlt`](../emfmaskblt) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc) { get; set; } | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8 que especifica el color de fondo del mapa de bits de origen. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades de dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la altura lógica del rectángulo de destino. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap) { get; set; } | Obtiene o establece un búfer que contiene los mapas de bits de máscara, que no requieren que sean contiguos a la parte fija del registro EMR_MASKBLT o entre sí . En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ignorarse. |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4) { get; set; } | Obtiene o establece una operación de ráster cuaternario, que especifica operaciones de ráster ternario para los colores frontal y de fondo de un mapa de bits. Estos valores definen cómo se combinarán los datos de color de el rectángulo de origen con los datos de color del rectángulo de destino. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap) { get; set; } | Obtiene o establece un búfer que contiene los mapas de bits de origen, que no requieren que sean contiguos a la parte fija del registro EMR_MASKBLT o entre sí . En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ignorarse. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado del mapa de bits de la máscara. Este valor DEBE estar en la enumeración DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de destino. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc) { get; set; } | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de origen. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de destino. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de origen. |

### Ver también

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
