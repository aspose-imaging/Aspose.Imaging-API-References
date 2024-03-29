---
title: EmfLogPenEx
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto LogPenEx especifica el estilo el ancho y el color de una pluma lógica extendida.
type: docs
weight: 3090
url: /es/net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
## EmfLogPenEx class

El objeto LogPenEx especifica el estilo, el ancho y el color de una pluma lógica extendida.

```csharp
public sealed class EmfLogPenEx : EmfBasePen
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfLogPenEx](emflogpenex)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Argb32ColorRef](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/argb32colorref) { get; set; } | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8). La interpretación de este campo depende del valor de BrushStyle, como se muestra en la tabla más adelante en esta sección. |
| [BrushDibPattern](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushdibpattern) { get; set; } | Obtiene o establece el patrón dib del pincel. |
| [BrushHatch](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushhatch) { get; set; } | Obtiene o establece el patrón de sombreado del pincel. La definición de este campo depende del valor BrushStyle, como se muestra en la tabla más adelante en esta sección. |
| [BrushStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/brushstyle) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica un estilo de pincel para el lápiz de la enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). Si el tipo de pluma en el campo PenStyle es PS_GEOMETRIC, este valor DEBE ser BS_SOLID o BS_HATCHED. El valor de este campo puede ser BS_NULL, pero solo si el estilo de línea especificado en PenStyle es PS_NULL. El estilo BS_NULL DEBE usarse para especificar un pincel que no tiene efecto. |
| [NumStyleEntities](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/numstyleentities) { get; } | Obtiene el número de elementos de la matriz especificada en el campo StyleEntry. Este valor DEBE ser cero si PenStyle no especifica PS_USERSTYLE. |
| override [PenStyle](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/penstyle) { get; set; } | Obtiene o establece el estilo de pluma |
| [StyleEntry](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/styleentry) { get; set; } | Obtiene o establece una matriz opcional de enteros sin signo de 32 bits que define la longitud de los guiones y los espacios en la línea dibujada por esta pluma, cuando el valor de PenStyle es el estilo de línea PS_USERSTYLE para la pluma. La matriz contiene una cantidad de entradas especificadas por NumStyleEntries, pero se usa como si se repitiera indefinidamente. La primera entrada de la matriz especifica la longitud del primer guión. La segunda entrada especifica la longitud del primer espacio. A partir de entonces, se alternan las longitudes de los guiones y los espacios. Si el tipo de pluma en el campo PenStyle es PS_GEOMETRIC, las longitudes se especifican en unidades lógicas; de lo contrario, las longitudes se especifican en unidades de dispositivo. |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogpenex/width) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el ancho de la línea dibujada por la pluma. Si el tipo de pluma en el campo PenStyle es PS_GEOMETRIC, este valor es el ancho en unidades lógicas; de lo contrario, el ancho se especifica en unidades de dispositivo. Si el tipo de bolígrafo en el campo PenStyle es PS_COSMETIC, este valor DEBE ser 0x00000001. |

### Ver también

* class [EmfBasePen](../emfbasepen)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
