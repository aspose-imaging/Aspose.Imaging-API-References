---
title: EmfStretchDiBits
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EMR_STRETCHDIBITS especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino  opcionalmente en combinación con un patrón de pincel según una operación de ráster especificada estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino si necesario.
type: docs
weight: 4600
url: /es/net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

El registro EMR_STRETCHDIBITS especifica una transferencia en bloque de píxeles desde un mapa de bits de origen a un rectángulo de destino , opcionalmente en combinación con un patrón de pincel, según una operación de ráster especificada, estirando o comprimiendo la salida para que se ajuste a las dimensiones del destino, si necesario.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits)(EmfRecord) | Inicializa una nueva instancia del[`EmfStretchDiBits`](../emfstretchdibits) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica un código de operación ráster . Estos códigos definen cómo se combinarán los datos de color del rectángulo de origen con los datos de color del rectángulo de destino y, opcionalmente, un patrón de pincel, para lograr el color final. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds) { get; set; } | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el rectángulo delimitador de destino en unidades de dispositivo. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el ancho en píxeles del rectángulo de origen. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la altura lógica del rectángulo de destino. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la altura en píxeles del rectángulo de origen. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Obtiene o establece el tamaño del registro |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap) { get; set; } | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea contiguo a la parte fija del registro EMR_STRETCHDIBITS. En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ignorarse. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Obtiene o establece el tipo. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores en el encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x lógica de la esquina superior izquierda del rectángulo de destino. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada x en píxeles de la esquina superior izquierda del rectángulo de origen. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y lógica de la esquina superior izquierda del rectángulo de destino. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la coordenada y en píxeles de la esquina superior izquierda del rectángulo de origen. |

### Observaciones

Este registro admite imágenes de origen en formatos JPEG y PNG. El campo Compresión en el encabezado de mapa de bits de origen especifica el formato de la imagen. Si los signos de los campos de alto y ancho de origen y destino difieren, este registro especifica una copia de imagen reflejada del mapa de bits de origen en el destino. Es decir, si cxSrc y cxDest tienen signos diferentes, se especifica una imagen reflejada del mapa de bits de origen a lo largo del eje x. Si cySrc y cyDest tienen signos diferentes, se especifica una imagen reflejada del mapa de bits de origen a lo largo del eje y.

### Ver también

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
