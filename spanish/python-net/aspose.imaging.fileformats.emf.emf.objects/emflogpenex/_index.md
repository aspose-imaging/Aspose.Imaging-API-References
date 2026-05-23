---
title: "Clase EmfLogPenEx"
type: docs
weight: 190
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | Inicializa una nueva instancia de la clase EmfLogPenEx |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8). La interpretación de este<br/> campo depende del valor BrushStyle, como se muestra en la tabla más adelante en esta sección. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece el patrón dib del pincel. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Obtiene o establece el patrón de rayado del pincel. La definición de este campo depende del <br/> valor BrushStyle, como se muestra en la tabla más adelante en esta sección. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica un estilo de pincel para la pluma a partir de la<br/> enumeración WMF BrushStyle ([MS-WMF] sección 2.1.1.4). <br/> Si el tipo de pluma en el campo PenStyle es PS_GEOMETRIC, este valor DEBE ser BS_SOLID o BS_HATCHED. El valor de este campo puede ser BS_NULL, pero solo si el <br/> estilo de línea especificado en PenStyle es PS_NULL. El estilo BS_NULL DEBERÍA usarse <br/> para especificar un pincel que no tiene efecto. |
| num_style_entities | int | r | Obtiene el número de elementos en la matriz especificada en el campo StyleEntry. <br/> Este valor DEBERÍA ser cero si PenStyle no especifica PS_USERSTYLE. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | Obtiene o establece el estilo de la pluma |
| style_entry | int[] | r/w | Obtiene o establece una matriz opcional de enteros sin signo de 32 bits que define las longitudes de <br/> guiones y espacios en la línea dibujada por esta pluma, cuando el valor de PenStyle <br/> es el estilo de línea PS_USERSTYLE para la pluma. La matriz contiene un número de <br/> entradas especificado por NumStyleEntries, pero se usa como si se repitiera indefinidamente <br/> La primera entrada de la matriz especifica la longitud del primer guión. La segunda <br/> entrada especifica la longitud del primer espacio. A partir de ahí, las longitudes de guiones y espacios se alternan.<br/> Si el tipo de pluma en el campo PenStyle es PS_GEOMETRIC, las longitudes se especifican en <br/> unidades lógicas; de lo contrario, se especifican en unidades de dispositivo. |
| width | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el ancho de la línea dibujada por la pluma.<br/> Si el tipo de pluma en el campo PenStyle es PS_GEOMETRIC, este valor es el ancho en<br/> unidades lógicas; de lo contrario, el ancho se especifica en unidades de dispositivo. <br/> Si el tipo de pluma en el campo PenStyle es PS_COSMETIC, este valor DEBE ser 0x00000001. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

Inicializa una nueva instancia de la clase EmfLogPenEx

