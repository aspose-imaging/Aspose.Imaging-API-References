---
title: "EmfLogFontPanose Clase"
type: docs
weight: 160
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---

**Summary:** The LogFontPanose object specifies the PANOSE characteristics of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontPanose

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfLogFontPanose(emf_log_font)](#EmfLogFontPanose_emf_log_font_1) | Inicializa una nueva instancia de la clase [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica el conjunto de glifos de caracteres. DEBE <br/>            ser un valor de la enumeración WMF CharacterSet ([MS-WMF] sección 2.1.1.5). Si el <br/>            conjunto de caracteres es desconocido, el procesamiento de metaficheros NO DEBERÍA intentar traducir o interpretar <br/>            cadenas que se renderizan con esa fuente. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de recorte. La <br/>            precisión de recorte define cómo recortar caracteres que están parcialmente fuera de la región de recorte. <br/>            Puede ser una o más de las banderas WMF ClipPrecision. |
| culture | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse en cero y DEBE ser ignorado. |
| escapement | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, <br/>            entre el vector de escapamiento y el eje x del dispositivo. El vector de escapamiento es <br/>            paralelo a la línea base de una fila de texto. |
| facename | string | r/w | Obtiene o establece un Facename (64 bytes):  Una cadena de no más de 32 caracteres Unicode que especifica el <br/>            nombre de la tipografía de la fuente. Si la longitud de esta cadena es menor a 32 caracteres, debe estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado. |
| full_name | string | r/w | Obtiene o establece una cadena de 64 caracteres Unicode que define el nombre completo de la fuente. Si <br/> la longitud de esta cadena es menor que 64 caracteres, debe estar presente un NULL terminador, después <br/> del cual el resto de este campo DEBE ser ignorado. |
| height | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura, en unidades lógicas, de la celda de carácter o carácter de la fuente.<br/>            El valor de altura del carácter, también conocido como tamaño em, es el valor de altura de la celda de carácter menos el valor de interlínea interno.<br/>            El asignador de fuentes DEBERÍA interpretar el valor especificado en el campo Height de la siguiente manera. |
| cursiva | System.Byte | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente cursiva si se establece en 0x01; <br/>            DEBE estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado. |
| match | int | r/w | Obtiene o establece Este campo DEBE ser ignorado. |
| orientación | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado,<br/>            entre la línea base de cada carácter y el eje x del dispositivo. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de salida. La <br/>            precisión de salida define cuán estrechamente se requiere que la fuente coincida con la altura, anchura, <br/>            orientación de carácter, escapamiento, paso y tipo de fuente solicitados. DEBE ser un valor de la enumeración WMF OutPrecision. |
| padding | int | r/w | Obtiene o establece un campo que existe solo para garantizar la alineación de 32 bits de esta estructura. DEBE ser ignorado |
| panose | [EmfPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpanose/) | r/w | Obtiene o establece un objeto Panose (sección 2.2.21) que especifica las características PANOSE <br/> de la fuente lógica. Si todos los campos de este objeto son cero, DEBE ser ignorado. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Obtiene o establece un objeto WMF PitchAndFamily ([MS-WMF] sección 2.2.2.14) que <br/>            especifica el paso y la familia de la fuente. Las familias de fuentes describen el aspecto de una fuente de manera general.<br/>            Se utilizan para especificar una fuente cuando el tipo de letra especificado no está disponible. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de salida. La calidad de salida <br/>            define cuán de cerca se debe intentar coincidir los atributos de la fuente lógica con los de una fuente física real. DEBE ser uno de los valores de la enumeración WMF FontQuality ([MS-WMF] <br/>            sección 2.1.1.10). |
| tachado | System.Byte | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente tachada si se establece en 0x01; <br/>            de lo contrario, DEBE establecerse en 0x00. |
| estilo | string | r/w | Obtiene o establece una cadena de 32 caracteres Unicode que define el estilo de la fuente. Si la longitud de <br/>            esta cadena es inferior a 32 caracteres, DEBE estar presente un NULL terminador, después del cual el <br/>            resto de este campo DEBE ser ignorado. |
| style_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de punto en el que se realiza el hinting de fuentes <br/> si se establece en cero, el hinting de fuentes se realiza en el tamaño de punto correspondiente <br/> al campo Height del objeto LogFont en el campo LogFont. |
| subrayado | System.Byte | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente subrayada si se establece en 0x01; <br/>            de lo contrario, DEBE establecerse en 0x00. |
| vendor_id | int | r/w | Obtiene o establece Este campo DEBE ser ignorado. |
| versión | int | r/w | Obtiene o establece Este campo DEBE ser ignorado. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el grosor de la fuente en el rango <br/>            de cero a 1000. Por ejemplo, 400 es normal y 700 es negrita. Si este valor es cero, se puede usar un grosor predeterminado. |
| width | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ancho promedio, en unidades lógicas, de <br/>            los caracteres de la fuente. Si el valor del campo Width es cero, DEBERÍA calcularse un valor apropiado a partir de otros valores LogFont para encontrar una fuente que tenga la relación de aspecto prevista por el tipógrafo. |


### Constructor: EmfLogFontPanose(emf_log_font) {#EmfLogFontPanose_emf_log_font_1}


```
 EmfLogFontPanose(emf_log_font) 
```

Inicializa una nueva instancia de la clase [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | La base log font. |

