---
title: "Clase EmfLogFont"
type: docs
weight: 130
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---

**Summary:** The LogFont object specifies the basic attributes of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFont

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfLogFont()](#EmfLogFont__1) | Inicializa una nueva instancia de la clase EmfLogFont |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica el conjunto de glifos de caracteres. DEBE <br/>            ser un valor de la enumeración WMF CharacterSet ([MS-WMF] sección 2.1.1.5). Si el <br/>            conjunto de caracteres es desconocido, el procesamiento de metaficheros NO DEBERÍA intentar traducir o interpretar <br/>            cadenas que se renderizan con esa fuente. |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de recorte. La <br/>            precisión de recorte define cómo recortar caracteres que están parcialmente fuera de la región de recorte. <br/>            Puede ser una o más de las banderas WMF ClipPrecision. |
| escapement | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado, <br/>            entre el vector de escapamiento y el eje x del dispositivo. El vector de escapamiento es <br/>            paralelo a la línea base de una fila de texto. |
| facename | string | r/w | Obtiene o establece un Facename (64 bytes):  Una cadena de no más de 32 caracteres Unicode que especifica el <br/>            nombre de la tipografía de la fuente. Si la longitud de esta cadena es menor a 32 caracteres, debe estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado. |
| height | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura, en unidades lógicas, de la celda de carácter o carácter de la fuente.<br/>            El valor de altura del carácter, también conocido como tamaño em, es el valor de altura de la celda de carácter menos el valor de interlínea interno.<br/>            El asignador de fuentes DEBERÍA interpretar el valor especificado en el campo Height de la siguiente manera. |
| cursiva | System.Byte | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente cursiva si se establece en 0x01; <br/>            DEBE estar presente un NULL terminador, después del cual el resto de este campo DEBE ser ignorado. |
| orientación | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ángulo, en décimas de grado,<br/>            entre la línea base de cada carácter y el eje x del dispositivo. |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la precisión de salida. La <br/>            precisión de salida define cuán estrechamente se requiere que la fuente coincida con la altura, anchura, <br/>            orientación de carácter, escapamiento, paso y tipo de fuente solicitados. DEBE ser un valor de la enumeración WMF OutPrecision. |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | Obtiene o establece un objeto WMF PitchAndFamily ([MS-WMF] sección 2.2.2.14) que <br/>            especifica el paso y la familia de la fuente. Las familias de fuentes describen el aspecto de una fuente de manera general.<br/>            Se utilizan para especificar una fuente cuando el tipo de letra especificado no está disponible. |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad de salida. La calidad de salida <br/>            define cuán de cerca se debe intentar coincidir los atributos de la fuente lógica con los de una fuente física real. DEBE ser uno de los valores de la enumeración WMF FontQuality ([MS-WMF] <br/>            sección 2.1.1.10). |
| tachado | System.Byte | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente tachada si se establece en 0x01; <br/>            de lo contrario, DEBE establecerse en 0x00. |
| subrayado | System.Byte | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica una fuente subrayada si se establece en 0x01; <br/>            de lo contrario, DEBE establecerse en 0x00. |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el grosor de la fuente en el rango <br/>            de cero a 1000. Por ejemplo, 400 es normal y 700 es negrita. Si este valor es cero, se puede usar un grosor predeterminado. |
| width | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ancho promedio, en unidades lógicas, de <br/>            los caracteres de la fuente. Si el valor del campo Width es cero, DEBERÍA calcularse un valor apropiado a partir de otros valores LogFont para encontrar una fuente que tenga la relación de aspecto prevista por el tipógrafo. |


### Constructor: EmfLogFont() {#EmfLogFont__1}


```
 EmfLogFont() 
```

Inicializa una nueva instancia de la clase EmfLogFont

