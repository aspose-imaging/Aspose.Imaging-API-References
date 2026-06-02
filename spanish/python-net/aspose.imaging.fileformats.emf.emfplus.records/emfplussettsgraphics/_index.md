---
title: "Clase EmfPlusSetTsGraphics"
type: docs
weight: 580
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | Inicializa una nueva instancia de la clase [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de líneas,<br/>            incluido el tipo de antialiasing de líneas. DEBE estar definido en la enumeración SmoothingMode<br/>            (sección 2.1.1.28). |
| basic_vga_colors | bool | r | Obtiene un valor que indica si [basic vga colors].<br/>            Si está establecido, la paleta contiene solo los colores VGA básicos. |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se combinan los colores de origen<br/>            con los colores de fondo. DEBE ser un valor de la enumeración CompositingMode<br/>            (sección 2.1.1.5). |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica el grado de<br/>            suavizado a aplicar a líneas, curvas y los bordes de áreas rellenas para que parezcan más<br/>            continuas o definidas con nitidez. DEBE ser un valor de la enumeración CompositingQuality (sección 2.1.1.6). |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica cómo se realiza el escalado, incluido el estiramiento<br/>            y la reducción. DEBE ser un valor de la enumeración FilterType (sección 2.1.1.11). |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| have_palette | bool | r | Obtiene un valor que indica si [have palette].<br/>            Si está establecido, este registro contiene un objeto EmfPlusPalette (sección 2.2.2.28) en el<br/>            campo Palette que sigue a los datos del estado gráfico. |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Obtiene o establece un objeto EmfPlusPalette opcional. |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad general de la imagen<br/>            y del proceso de renderizado de texto. DEBE ser un valor de la enumeración PixelOffsetMode (sección 2.1.1.26). |
| render_origin_x | int | r/w | Obtiene o establece un entero con signo de 16 bits, que es la coordenada horizontal del<br/>            origen para el renderizado de tramado y matrices de dithering. |
| render_origin_y | int | r/w | Obtiene o establece un entero con signo de 16 bits, que es la coordenada vertical del origen<br/>            para el renderizado de tramado y matrices de dithering. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| text_contrast | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma<br/>            utilizado para renderizar texto anti-alias y ClearType. Este valor DEBE estar en el rango de 0 a 12, inclusive. |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Obtiene o establece un entero sin signo de 8 bits que especifica la calidad del renderizado de texto,<br/>            incluido el tipo de anti-aliasing de texto. DEBE estar definido en la enumeración<br/>            TextRenderingHint (sección 2.1.1.32). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto EmfPlusTransformMatrix de 192 bits (sección 2.2.2.47) que<br/> especifica las transformaciones del espacio mundial al espacio del dispositivo. |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

