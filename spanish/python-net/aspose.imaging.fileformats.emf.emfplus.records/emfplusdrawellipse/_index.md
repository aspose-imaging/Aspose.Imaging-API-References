---
title: "Clase EmfPlusDrawEllipse"
type: docs
weight: 120
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---

**Summary:** The EmfPlusDrawEllipse record specifies drawing an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawEllipse(source)](#EmfPlusDrawEllipse_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| comprimido | bool | r/w | Obtiene o establece un valor que indica si el PointData está comprimido. <br/>            Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). <br/>            Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+<br/>            para dibujar la elipse. El valor DEBE estar entre cero y 63, inclusive. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece los datos del rectángulo<br/>            Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawEllipse(source) {#EmfPlusDrawEllipse_source_1}


```
 EmfPlusDrawEllipse(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

