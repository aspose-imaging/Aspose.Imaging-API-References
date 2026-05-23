---
title: "Clase EmfPlusStringFormat"
type: docs
weight: 650
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | Inicializa una nueva instancia de la clase EmfPlusStringFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Obtiene o establece un objeto EmfPlusLanguageIdentifier que especifica el<br/>            idioma a usar para los dígitos numéricos en la cadena.<br/>            Por ejemplo, si esta cadena contiene dígitos árabes,<br/>            este campo DEBE contener un identificador de idioma que<br/>            especifique un idioma árabe |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo sustituir<br/>            dígitos numéricos en la cadena según una configuración regional o idioma.<br/>            Este valor DEBE estar definido en la enumeración StringDigitSubstitution<br/>            (sección 2.1.1.30). |
| first_tab_offset | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica el número<br/>            de espacios entre el comienzo de una línea de texto y<br/>            la primera tabulación |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el tipo de<br/>            procesamiento que se realiza en una cadena cuando se encuentra un prefijo de atajo de teclado (es decir, una y comercial).<br/>            Básicamente, este campo indica si se deben mostrar<br/>            los prefijos de atajo de teclado relacionados con el texto.<br/>            El valor DEBE estar definido en la enumeración HotkeyPrefix<br/>            (sección 2.1.1.14). |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Obtiene o establece un objeto EmfPlusLanguageIdentifier (sección 2.2.2.23)<br/>            que especifica el idioma a usar para la cadena |
| leading_margin | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud<br/>            del espacio a añadir a la posición inicial de una cadena.<br/>            El valor predeterminado es 1/6 de pulgada; para fuentes tipográficas, el<br/>            valor predeterminado es 0. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo<br/>            alinear la cadena verticalmente en el rectángulo de diseño.<br/>            Este valor DEBE estar definido en la enumeración StringAlignment. |
| range_count | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el número de objetos EmfPlusCharacterRange<br/>            (sección 2.2.2.8) definidos en el campo StringFormatData. |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo<br/>            alinear la cadena horizontalmente en el rectángulo de diseño.<br/>            Este valor DEBE estar definido en la enumeración StringAlignment<br/>            (sección 2.1.1.29). |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Obtiene o establece un objeto EmfPlusStringFormatData (sección 2.2.2.44)<br/>            que especifica datos opcionales de diseño de texto. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica opciones de diseño de texto<br/>            para formateo, recorte y manejo de fuentes.<br/>            Este valor DEBE estar compuesto por banderas StringFormat<br/>            (sección 2.1.2.8). |
| tabstop_count | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el número de tabulaciones<br/>            definidas en el campo StringFormatData. |
| tracking | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica la proporción<br/>            del espacio horizontal asignado a cada carácter en<br/>            una cadena especificada respecto al ancho definido por la fuente del<br/>            carácter. Valores altos para esta propiedad indican amplio<br/>            espacio entre caracteres; valores menores que 1 pueden producir<br/>            superposición de caracteres. El valor predeterminado es 1.03; para fuentes tipográficas,<br/>            el valor predeterminado es 1.00. |
| trailing_margin | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica la longitud<br/>            del espacio que se debe dejar después de una cadena. El valor<br/>            predeterminado es 1/6 de pulgada; para fuentes tipográficas, el valor predeterminado es 0. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Obtiene o establece especifica cómo recortar caracteres de una cadena que es<br/>            demasiado grande para caber en un rectángulo de diseño. Este valor<br/>            DEBE estar definido en la enumeración StringTrimming (sección 2.1.1.31). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtiene o establece la versión. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

Inicializa una nueva instancia de la clase EmfPlusStringFormat

