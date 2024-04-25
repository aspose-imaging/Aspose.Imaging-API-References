---
title: EmfLogFontExDv
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto LogFontExDv especifica el vector de diseño para una fuente lógica extendida.
type: docs
weight: 3050
url: /es/aspose.imaging.fileformats.emf.emf.objects/emflogfontexdv/
---
## EmfLogFontExDv class

El objeto LogFontExDv especifica el vector de diseño para una fuente lógica extendida.

```csharp
public sealed class EmfLogFontExDv : EmfLogFontEx
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfLogFontExDv](emflogfontexdv)(EmfLogFontEx) | Inicializa una nueva instancia del[`EmfLogFontExDv`](../emflogfontexdv) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica el conjunto de glifos de caracteres. DEBE ser un valor en la enumeración del conjunto de caracteres WMF ([MS-WMF] sección 2.1.1.5). Si se desconoce el conjunto de caracteres , el procesamiento de metarchivos NO DEBE intentar traducir o interpretar las cadenas que se representan con esa fuente. |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de recorte. La precisión de recorte define cómo recortar caracteres que están parcialmente fuera de la región de recorte. Puede ser uno o más de los WMF ClipPrecision Flags |
| [DesignVector](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontexdv/designvector) { get; set; } | Obtiene o establece un objeto DesignVector (sección 2.2.3). Este campo NO DEBE tener más de 72 bytes. |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el ángulo, en décimas de grado, entre el vector de escape y el eje x del dispositivo. El vector de escape es paralelo a la línea base de una fila de texto. |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename) { get; set; } | Obtiene o establece un Facename (64 bytes): una cadena de no más de 32 caracteres Unicode que especifica el nombre de tipo de letra de la fuente. Si la longitud de esta cadena es inferior a 32 caracteres, DEBE estar presente un NULL de terminación, después de lo cual DEBE ignorarse el resto de este campo. |
| [FullName](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/fullname) { get; set; } | Obtiene o establece una cadena de 64 caracteres Unicode que contiene el nombre completo de la fuente. Si la longitud de esta cadena es inferior a 64 caracteres, DEBE estar presente un NULL de terminación, después de que DEBE ignorarse el resto de este campo. |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica la altura, en unidades lógicas, del carácter o celda de carácter de la fuente. El valor de la altura del carácter, también conocido como tamaño em, es el valor de la altura de la celda del carácter menos el valor inicial interno. El mapeador de fuentes DEBERÍA interpretar el valor especificado en el campo Altura de la siguiente manera. |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente en cursiva si se establece en 0x01; de lo contrario, DEBE establecerse en 0x00. |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el ángulo, en décimas de grado, entre la línea base de cada carácter y el eje x del dispositivo. |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de salida. La precisión de salida define qué tan cerca se requiere que la fuente coincida con la altura, el ancho, la orientación del carácter , el escape, el paso y el tipo de fuente solicitados. DEBE ser un valor de WMF OutPrecision enumeration |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily) { get; set; } | Obtiene o establece un objeto WMF PitchAndFamily ([MS-WMF] sección 2.2.2.14) que especifica el tono y la familia de la fuente. Las familias de fuentes describen el aspecto de una fuente de forma general . Están destinados a especificar una fuente cuando el tipo de letra especificado no está disponible. |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de salida. La calidad de salida define qué tan cerca se debe intentar hacer coincidir los atributos de la fuente lógica con los de una fuente física real. DEBE ser uno de los valores en la enumeración WMF FontQuality ([MS-WMF] sección 2.1.1.10). |
| [Script](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/script) { get; set; } | Obtiene o establece una cadena de 32 caracteres Unicode que define el conjunto de caracteres de la fuente. Si la longitud de esta cadena es inferior a 32 caracteres, DEBE estar presente un NULL de terminación, después del cual DEBE ignorarse el resto de este campo. |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente tachada si se establece en 0x01; de lo contrario, DEBE establecerse en 0x00. |
| [Style](../../aspose.imaging.fileformats.emf.emf.objects/emflogfontex/style) { get; set; } | Obtiene o establece una cadena de 32 caracteres Unicode que define el estilo de la fuente. Si la longitud de esta cadena es inferior a 32 caracteres, DEBE estar presente un NULL de terminación, después de lo cual DEBE ignorarse el resto de este campo. |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline) { get; set; } | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente subrayada si se establece en 0x01; de lo contrario, DEBE establecerse en 0x00. |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight) { get; set; } | Obtiene o establece un entero con signo de 32 bits que especifica el peso de la fuente en el rango de cero a 1000. Por ejemplo, 400 es normal y 700 es negrita. Si este valor es cero, se puede usar un peso predeterminado . |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el ancho promedio, en unidades lógicas, de caracteres en la fuente. Si el valor del campo Ancho es cero, DEBERÍA calcularse un valor apropiado a partir de otros valores de LogFont para encontrar una fuente que tenga la relación de aspecto prevista por el tipógrafo |

### Ver también

* class [EmfLogFontEx](../emflogfontex)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
