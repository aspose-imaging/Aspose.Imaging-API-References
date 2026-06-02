---
title: "Clase EmfPlusFillEllipse"
type: docs
weight: 240
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---

**Summary:** The EmfPlusFillEllipse record specifies filling the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusFillEllipse(source)](#EmfPlusFillEllipse_source_1) | Inicializa una nueva instancia de la clase [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtiene o establece el identificador del pincel<br/>
            Un entero sin signo de 32 bits que especifica el pincel, cuyo contenido<br/>
            está determinado por el bit S en el campo Flags. Esta definición se usa <br/>
            para rellenar el interior de la elipse. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| is_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia es de color.<br/>            Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1).<br/>            Si no está establecido, BrushId contiene el índice de un objeto EmfPlusBrush <br/>            (sección 2.2.1.1) en la tabla de objetos EMF+. |
| is_compressed | bool | r/w | Obtiene o establece un valor que indica si esta instancia está comprimida.<br/>
            Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). <br/>
            Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece los datos del rectángulo<br/>
            Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusFillEllipse(source) {#EmfPlusFillEllipse_source_1}


```
 EmfPlusFillEllipse(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

