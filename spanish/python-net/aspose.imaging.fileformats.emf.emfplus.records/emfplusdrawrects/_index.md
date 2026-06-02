---
title: "Clase EmfPlusDrawRects"
type: docs
weight: 180
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---

**Summary:** The EmfPlusDrawRects record specifies drawing a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawRects(source)](#EmfPlusDrawRects_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| comprimido | bool | r/w | Obtiene o establece un valor que indica si PointData está comprimido.<br/>            Si se establece, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38).<br/>            Si se limpia, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la EMF+<br/>            Tabla de objetos para dibujar los rectángulos. El valor DEBE ser de 0 a 63, inclusive. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece los datos del rectángulo<br/>            Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawRects(source) {#EmfPlusDrawRects_source_1}


```
 EmfPlusDrawRects(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) .

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

