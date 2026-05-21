---
title: "EmfPlusDrawPie"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawPie especifica dibujar una sección del interior de una elipse."
type: docs
weight: 26
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawPie especifica dibujar una sección del interior de una elipse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawPie`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getStartAngle()](#getStartAngle--) | Obtiene o establece el ángulo de inicio Un valor de punto flotante de 32 bits, no negativo, que especifica el ángulo entre el eje x y el punto de inicio del sector de pastel. |
| [setStartAngle(float value)](#setStartAngle-float-) | Obtiene o establece el ángulo de inicio Un valor de punto flotante de 32 bits, no negativo, que especifica el ángulo entre el eje x y el punto de inicio del sector de pastel. |
| [getSweepAngle()](#getSweepAngle--) | Obtiene o establece el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco que define el sector de pastel a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Obtiene o establece el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco que define el sector de pastel a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. |
| [getRectData()](#getRectData--) | Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que contiene el sector de pastel. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que contiene el sector de pastel. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawPie`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la porción. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la porción. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

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

