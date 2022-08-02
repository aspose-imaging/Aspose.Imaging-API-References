---
title: EmfPlusSetTsGraphics
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusSetTSGraphics especifica el estado de un contexto de dispositivo de gráficos para un servidor terminal.
type: docs
weight: 6410
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

El registro EmfPlusSetTSGraphics especifica el estado de un contexto de dispositivo de gráficos para un servidor terminal.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de la representación de línea, incluido el tipo de suavizado de líneas. DEBE estar definido en la enumeración SmoothingMode (sección 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | Obtiene un valor que indica si [colores vga básicos]. Si se establece, la paleta contiene solo los colores básicos de VGA. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se combinan los colores de origen con los colores de fondo. DEBE ser un valor en la enumeración CompositingMode (sección 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica el grado de suavizado que se aplica a líneas, curvas y bordes de áreas rellenas para que parezcan más continuos o bien definidos. DEBE ser un valor en la enumeración CompositingQuality (sección 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se realiza el escalado, incluida la ampliación y la reducción. DEBE ser un valor en la enumeración FilterType (sección 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | Obtiene un valor que indica si [tiene paleta]. Si se establece, este registro contiene un objeto EmfPlusPalette (sección 2.2.2.28) en el campo Palette que sigue a los datos de estado de gráficos. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | Obtiene o establece un objeto EmfPlusPalette opcional. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad general de la imagen y el proceso de representación de texto. DEBE ser un valor en la enumeración PixelOffsetMode (sección 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | Obtiene o establece un entero con signo de 16 bits, que es la coordenada horizontal del origen para renderizar matrices de tramado y medios tonos. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | Obtiene o establece un entero con signo de 16 bits, que es la coordenada vertical del origen para renderizar matrices de tramado y medios tonos. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma que se usa para representar texto suavizado y ClearType. Este valor DEBE estar en el rango de 0 a 12, inclusive. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de la representación de text , incluido el tipo de suavizado de texto. DEBE estar definido en la enumeración TextRenderingHint (sección 2.1.1.32). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | Obtiene o establece un objeto EmfPlusTransformMatrix de 192 bits (sección 2.2.2.47) que especifica las transformaciones del espacio mundial al espacio del dispositivo. |

### Ver también

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
