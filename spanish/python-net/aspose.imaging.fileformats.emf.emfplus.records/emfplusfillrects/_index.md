---
title: "Clase EmfPlusFillRects"
type: docs
weight: 280
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---

**Summary:** The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusFillRects(source)](#EmfPlusFillRects_source_1) | Inicializa una nueva instancia de la clase [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtiene o establece el identificador del pincel<br/>            Un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| compressed | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) está comprimido.<br/>            Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está despejado, RectData<br/>             contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| is_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia es de color.<br/>            Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1).<br/>            Si está despejado, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece los datos del rectángulo<br/>            Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusFillRects(source) {#EmfPlusFillRects_source_1}


```
 EmfPlusFillRects(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

