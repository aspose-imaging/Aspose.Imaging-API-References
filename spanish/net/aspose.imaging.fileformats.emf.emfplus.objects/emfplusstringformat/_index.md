---
title: EmfPlusStringFormat
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El objeto EmfPlusStringFormat especifica el diseño del texto manipulaciones de visualización e identificación de idioma
type: docs
weight: 5780
url: /es/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

El objeto EmfPlusStringFormat especifica el diseño del texto, manipulaciones de visualización e identificación de idioma

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | Obtiene o establece un objeto EmfPlusLanguageIdentifier que especifica el idioma que se utilizará para los dígitos numéricos en la cadena. Por ejemplo, si esta cadena contiene dígitos árabes, este campo DEBE contener un identificador de idioma que especifica un idioma árabe |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo sustituir dígitos numéricos en la cadena según una configuración regional o idioma. Este valor DEBE definirse en la enumeración StringDigitSubstitution (sección 2.1.1.30). |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | Obtiene o establece un valor de punto flotante de 32 bits que especifica el número de espacios entre el comienzo de una línea de texto y la primera tabulación |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el tipo de procesamiento que se realiza en una cadena cuando se encuentra un prefijo de método abreviado de teclado (es decir, un ampersand). relacionado con text. El valor DEBE definirse en la enumeración HotkeyPrefix (sección 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | Obtiene o establece un objeto EmfPlusLanguageIdentifier (sección 2.2.2.23) que especifica el idioma a usar para la cadena |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio para agregar a la posición inicial de una cadena. El valor predeterminado es 1/6 de pulgada; para fuentes tipográficas, el valor predeterminado de es 0. |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena verticalmente en el rectángulo de diseño. Este valor DEBE definirse en la enumeración StringAlignment. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el número de objetos EmfPlusCharacterRange (sección 2.2.2.8) definidos en el campo StringFormatData. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica cómo alinear la cadena horizontalmente en el rectángulo de diseño. Este valor DEBE definirse en la enumeración StringAlignment (sección 2.1.1.29). |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | Obtiene o establece un objeto EmfPlusStringFormatData (sección 2.2.2.44) que especifica datos de diseño de texto opcionales. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de diseño de texto para formato, recorte y manejo de fuentes. Este valor DEBE estar compuesto por StringFormat flags (sección 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | Obtiene o establece un entero de 32 bits con signo que especifica el número de tabulaciones definidas en el campo StringFormatData. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | Obtiene o establece un valor de coma flotante de 32 bits que especifica la proporción del espacio horizontal asignado a cada carácter en una cadena especificada al ancho definido por la fuente del carácter . Los valores grandes para esta propiedad especifican un espacio amplio entre caracteres; los valores inferiores a 1 pueden producir una superposición de caracteres . El valor predeterminado es 1,03; para fuentes tipográficas , el valor predeterminado es 1.00. |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud del espacio que se deja después de una cadena. El default es 1/6 de pulgada; para fuentes tipográficas, el valor predeterminado es 0. |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Obtiene o establece cómo recortar los caracteres de una cadena que es demasiado grande para caber en un rectángulo de diseño. Este valor DEBE definirse en la enumeración StringTrimming (sección 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Obtiene o establece la versión. |

### Ver también

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
