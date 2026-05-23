---
title: "Clase EmfPlusDrawString"
type: docs
weight: 190
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Inicializa una nueva instancia de la [EmpPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtiene o establece el identificador del pincel<br/>            Un entero sin signo de 32 bits que especifica el pincel, cuyo contenido <br/>            está determinado por el bit S en el campo Flags. Esta definición se usa <br/>            para pintar el color del texto de primer plano; es decir, solo los glifos mismos. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| format_id | int | r/w | Obtiene o establece el identificador de formato<br/>            Un entero sin signo de 32 bits que especifica el índice de un objeto <br/>            EmfPlusStringFormat opcional (sección 2.2.1.9) en la tabla de objetos EMF+. <br/>            Este objeto especifica información de diseño de texto y manipulaciones de visualización <br/>            que se aplicarán a una cadena. |
| is_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia es de color.<br/>            Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1).<br/>            Si no está establecido, BrushId contiene el índice de un objeto EmfPlusBrush <br/>            (sección 2.2.1.1) en la tabla de objetos EMF+. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece el rectángulo de diseño<br/>            Un objeto EmfPlusRectF (sección 2.2.2.39) que define el área delimitadora <br/>            del destino que recibirá la cadena. |
| length | int | r/w | Obtiene o establece la longitud<br/>            Entero sin signo de 32 bits que especifica el número de caracteres en la cadena. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice de un objeto EmfPlusFont (sección 2.2.1.3) en la tabla de objetos EMF+<br/>            para renderizar el texto. El valor DEBE estar entre 0 y 63, inclusive. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| string_data | string | r/w | Obtiene o establece los datos de la cadena<br/>            Una matriz de caracteres Unicode de 16 bits que especifica la cadena a dibujar |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Inicializa una nueva instancia de la [EmpPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) clase.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

