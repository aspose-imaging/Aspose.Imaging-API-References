---
title: "Clase EmfPlusDrawArc"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece el tamaño de los datos.<br/> Un entero sin signo de 32 bits que especifica el número alineado a 32 bits de<br/> bytes de datos específicos del registro que siguen.<br/> Para este tipo de registro, el valor DEBE ser uno de los siguientes:<br/> 0x00000010 Si el bit C está establecido en el campo Flags.<br/> 0x00000018 Si el bit C está despejado en el campo Flags. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/> El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la<br/> tabla de objetos EMF+ para dibujar el arco. El valor DEBE estar entre 0 y 63, inclusive. |
| rect_float | bool | r/w | Obtiene o establece un valor que indica si los datos contienen <br/> registros EmfPlusRectF o EmfPlusRect<br/> Este bit indica si los datos en el campo RectData están comprimidos.<br/> Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38).<br/> Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece los datos del rectángulo<br/> Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador<br/> de la elipse que es colineal con el arco. Este rectángulo define la<br/> posición, tamaño y forma del arco. El tipo de objeto en este campo está<br/> especificado por el valor del campo Flags. |
| tamaño | int | r/w | Obtiene o establece el tamaño.<br/> Un entero sin signo de 32 bits que especifica el número alineado a 32 bits de<br/> bytes en todo el registro, incluyendo el encabezado de registro de 12 bytes y<br/> los datos específicos del registro. Para este tipo de registro, el valor DEBE ser uno de los siguientes:<br/> 0x0000001C  Si el bit C está establecido en el campo Flags.<br/> 0x00000024  Si el bit C está despejado en el campo Flags |
| start_angle | float | r/w | Obtiene o establece el ángulo inicial<br/> Un valor de punto flotante no negativo de 32 bits que especifica el ángulo entre<br/> el eje x y el punto de inicio del arco. Cualquier valor es aceptable,<br/> pero DEBE interpretarse módulo 360, con el resultado usado en el rango de 0.0 inclusive a 360.0 exclusivo. |
| sweep_angle | float | r/w | Obtiene o establece el ángulo de barrido<br/> Un valor de punto flotante de 32 bits que especifica la extensión del arco a dibujar,<br/> como un ángulo en grados medido desde el punto de inicio definido por el<br/> valor StartAngle. Cualquier valor es aceptable, pero DEBE limitarse a entre -360.0<br/> y 360.0 inclusive. Un valor positivo indica que el barrido se define en<br/> dirección horaria, y un valor negativo indica que el barrido se define en<br/> dirección antihoraria. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

