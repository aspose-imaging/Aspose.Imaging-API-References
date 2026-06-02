---
title: "EmfPlusFillPie"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusFillPie especifica el relleno de una sección del interior de una elipse"
type: docs
weight: 35
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

El registro EmfPlusFillPie especifica el relleno de una sección del interior de una elipse
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusFillPie`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [getStartAngle()](#getStartAngle--) | Obtiene o establece el ángulo de inicio Un valor de punto flotante de 32 bits, no negativo, que especifica el ángulo entre el eje x y el punto de inicio del sector de pastel. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtiene o establece el ángulo de inicio Un valor de punto flotante de 32 bits, no negativo, que especifica el ángulo entre el eje x y el punto de inicio del sector de pastel. |
| [getSweepAngle()](#getSweepAngle--) | Obtiene o establece el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco que define el sector de pastel a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtiene o establece el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco que define el sector de pastel a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. |
| [getRectData()](#getRectData--) | Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que contiene el sector de pastel. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que contiene el sector de pastel. |
| [getBrushId()](#getBrushId--) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusFillPie`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtiene o establece un valor que indica si el PointData está comprimido. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39).

Valor: `true` si está comprimido; de lo contrario, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si el PointData está comprimido. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39).

Valor: `true` si está comprimido; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtiene o establece un valor que indica si esta instancia es de color. Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si está borrado, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+.

Valor: `true` si esta instancia es de color; de lo contrario, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es de color. Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si está borrado, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+.

Valor: `true` si esta instancia es de color; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtiene o establece el ángulo de inicio Un valor de punto flotante de 32 bits, no negativo, que especifica el ángulo entre el eje x y el punto de inicio del sector de pastel. Cualquier valor es aceptable, pero DEBE interpretarse módulo 360, con el resultado que se usa estando en el rango de 0.0 inclusive a 360.0 exclusivo.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Obtiene o establece el ángulo de inicio Un valor de punto flotante de 32 bits, no negativo, que especifica el ángulo entre el eje x y el punto de inicio del sector de pastel. Cualquier valor es aceptable, pero DEBE interpretarse módulo 360, con el resultado que se usa estando en el rango de 0.0 inclusive a 360.0 exclusivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtiene o establece el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco que define el sector de pastel a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. Cualquier valor es aceptable, pero DEBE limitarse a -360.0 a 360.0 inclusive. Un valor positivo indica que el barrido se define en dirección horaria, y un valor negativo indica que el barrido se define en dirección antihoraria.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Obtiene o establece el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco que define el sector de pastel a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. Cualquier valor es aceptable, pero DEBE limitarse a -360.0 a 360.0 inclusive. Un valor positivo indica que el barrido se define en dirección horaria, y un valor negativo indica que el barrido se define en dirección antihoraria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que contiene el sector de pastel. Este rectángulo define la posición, el tamaño y la forma del pastel. El tipo de objeto en este campo se especifica mediante el valor del campo Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que contiene el sector de pastel. Este rectángulo define la posición, el tamaño y la forma del pastel. El tipo de objeto en este campo se especifica mediante el valor del campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

