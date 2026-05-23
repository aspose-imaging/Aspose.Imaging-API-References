---
title: "EmfPlusDrawDriverString Class"
type: docs
weight: 110
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtiene o establece el identificador del pincel<br/>            Un entero sin signo de 32 bits que especifica ya sea el color de primer plano del texto o un pincel gráfico,<br/>            dependiendo del valor de la bandera S en Flags. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Obtiene o establece las banderas de opciones de cadena de controlador<br/>            Un entero sin signo de 32 bits que especifica el espaciado, la orientación y la calidad de renderizado de la cadena. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| glyph_count | int | r/w | Obtiene o establece el recuento de glifos<br/>            Un entero sin signo de 32 bits que especifica el número de glifos en la cadena. |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece la matriz de posiciones de glifos<br/>            Una matriz de objetos EmfPlusPointF (sección 2.2.2.36) que especifican la posición de salida de cada glifo de carácter.<br/>            DEBE haber elementos GlyphCount, que tienen una correspondencia uno a uno con los elementos de la matriz Glyphs.<br/>            Las posiciones de los glifos se calculan a partir de la posición del primer glifo si la bandera DriverStringOptionsRealizedAdvance<br/>            en las banderas DriverStringOptions está establecida. En este caso, GlyphPos especifica solo la posición del primer glifo. |
| glyphs | int[] | r/w | Obtiene o establece la matriz de glifos<br/>            Una matriz de valores de 16 bits que define la cadena de texto a dibujar.<br/>            Si la bandera DriverStringOptionsCmapLookup en el campo DriverStringOptionsFlags está establecida, cada valor en esta<br/>            matriz especifica un carácter Unicode. De lo contrario, cada valor especifica un índice a un<br/>            glifo de carácter en el objeto ***EmfPlusFont*** especificado por el valor ObjectId en el campo Flags. |
| is_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia es de color.<br/>            Este bit indica el tipo de datos en el campo BrushId.<br/>            Si está establecido, BrushId especifica el valor de color en un objeto EmfPlusARGB<br/>            (sección 2.2.2.1). Si está despejado, BrushId contiene el índice de la tabla de objetos EMF+<br/>            de un objeto EmfPlusBrush (sección 2.2.1.1). |
| matrix_present | int | r/w | Obtiene o establece si la bandera de matriz presente<br/>            Un entero sin signo de 32 bits que especifica si una matriz de transformación está presente en el campo TransformMatrix<br/>            0 - no hay matriz presente. 1 - la matriz de transformación está en el campo TransformMatrix. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice de la tabla de objetos EMF+ de un objeto ***EmfPlusFont*** (sección<br/>            2.2.1.3) para renderizar el texto. El valor DEBE estar entre 0 y 63, inclusive. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece la matriz de transformación<br/>            Un objeto opcional EmfPlusTransformMatrix (sección 2.2.2.47) que especifica la transformación a aplicar a<br/>            cada valor en la matriz de texto. La presencia de estos datos se determina a partir del campo MatrixPresent. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

