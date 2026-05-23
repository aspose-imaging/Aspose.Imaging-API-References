---
title: "Clase EmfPlusFillPie"
type: docs
weight: 260
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---

**Summary:** The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusFillPie(source)](#EmfPlusFillPie_source_1) | Inicializa una nueva instancia de la clase [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtiene o establece el identificador del pincel<br/>            Un entero sin signo de 32 bits que define el pincel, cuyo contenido <br/>            está determinado por el bit S en el campo Flags. |
| comprimido | bool | r/w | Obtiene o establece un valor que indica si PointData está comprimido.<br/>            Si se establece, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38).<br/>            Si se limpia, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| is_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia es de color.<br/>            Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). <br/>            Si no está establecido, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece los datos del rectángulo<br/>            Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador del <br/>            elipse que contiene la porción de pastel. Este rectángulo define la posición, el tamaño, <br/>            y la forma del pastel. El tipo de objeto en este campo se especifica mediante el valor <br/>            del campo Flags. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| start_angle | float | r/w | Obtiene o establece el ángulo inicial<br/>            Un valor de punto flotante de 32 bits, no negativo, que especifica el ángulo entre el <br/>            eje x y el punto de inicio de la porción de pastel. Cualquier valor es aceptable, pero <br/>            DEBE interpretarse módulo 360, con el resultado que se usa en el rango <br/>            de 0.0 inclusive a 360.0 exclusivo. |
| sweep_angle | float | r/w | Obtiene o establece el ángulo de barrido<br/>            Un valor de punto flotante de 32 bits que especifica la extensión del arco que define <br/>            la porción de pastel a dibujar, como un ángulo en grados medido desde el punto de inicio <br/>            definido por el valor StartAngle. Cualquier valor es aceptable, pero DEBE limitarse <br/>            a -360.0 a 360.0 inclusive. Un valor positivo indica que el barrido se define <br/>            en dirección horaria, y un valor negativo indica que el barrido se define <br/>            en dirección antihoraria. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusFillPie(source) {#EmfPlusFillPie_source_1}


```
 EmfPlusFillPie(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

