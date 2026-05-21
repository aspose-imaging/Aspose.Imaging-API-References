---
title: "EmfPlusDrawArc"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawArc especifica dibujar el arco de una elipse."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawArc especifica dibujar el arco de una elipse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawArc`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDataSize()](#getDataSize--) | Obtiene el tamaño de los datos. |
| [setDataSize(int value)](#setDataSize-int-) | Establece el tamaño de los datos. |
| [getRectFloat()](#getRectFloat--) | Obtiene un valor que indica si los datos contienen registros EmfPlusRectF o EmfPlusRect. Este bit indica si los datos en el campo RectData están comprimidos. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Establece un valor que indica si los datos contienen registros EmfPlusRectF o EmfPlusRect. Este bit indica si los datos en el campo RectData están comprimidos. |
| [getObjectId()](#getObjectId--) | Obtiene el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Establece el identificador del objeto. |
| [getSize()](#getSize--) | Obtiene el tamaño. |
| [setSize(int value)](#setSize-int-) | Establece el tamaño. |
| [getStartAngle()](#getStartAngle--) | Obtiene el ángulo de inicio Un valor de punto flotante no negativo de 32 bits que especifica el ángulo entre el eje x y el punto de inicio del arco. |
| [setStartAngle(float value)](#setStartAngle-float-) | Establece el ángulo de inicio Un valor de punto flotante no negativo de 32 bits que especifica el ángulo entre el eje x y el punto de inicio del arco. |
| [getSweepAngle()](#getSweepAngle--) | Obtiene el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Establece el ángulo de barrido Un valor de punto flotante de 32 bits que especifica la extensión del arco a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. |
| [getRectangleData()](#getRectangleData--) | Obtiene los datos del rectángulo. Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que es colineal con el arco. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Establece los datos del rectángulo. Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse que es colineal con el arco. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawArc`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtiene el tamaño de los datos. Un entero sin signo de 32 bits que especifica el número de bytes alineados a 32 bits de datos específicos del registro que siguen. Para este tipo de registro, el valor DEBE ser uno de los siguientes: 0x00000010 Si el bit C está establecido en el campo Flags. 0x00000018 Si el bit C está despejado en el campo Flags.

**Returns:**
int - El tamaño de los datos.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Establece el tamaño de los datos. Un entero sin signo de 32 bits que especifica el número de bytes alineados a 32 bits de datos específicos del registro que siguen. Para este tipo de registro, el valor DEBE ser uno de los siguientes: 0x00000010 Si el bit C está establecido en el campo Flags. 0x00000018 Si el bit C está despejado en el campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tamaño de los datos. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Obtiene un valor que indica si los datos contienen registros EmfPlusRectF o EmfPlusRect. Este bit indica si los datos en el campo RectData están comprimidos. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39).

**Returns:**
booleano - `true` si es flotante; de lo contrario, `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Establece un valor que indica si los datos contienen registros EmfPlusRectF o EmfPlusRect. Este bit indica si los datos en el campo RectData están comprimidos. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si es flotante; de lo contrario, `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar el arco. El valor DEBE estar entre 0 y 63, inclusive.

**Returns:**
byte - El identificador del objeto.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar el arco. El valor DEBE estar entre 0 y 63, inclusive.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | El identificador del objeto. |

### getSize() {#getSize--}
```
public int getSize()
```


Obtiene el tamaño. Un entero sin signo de 32 bits que especifica el número de bytes alineado a 32 bits en todo el registro, incluyendo el encabezado de 12 bytes y los datos específicos del registro. Para este tipo de registro, el valor DEBE ser uno de los siguientes: 0x0000001C si el bit C está establecido en el campo Flags. 0x00000024 si el bit C está despejado en el campo Flags.

**Returns:**
int - El tamaño.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Establece el tamaño. Un entero sin signo de 32 bits que especifica el número de bytes alineado a 32 bits en todo el registro, incluyendo el encabezado de 12 bytes y los datos específicos del registro. Para este tipo de registro, el valor DEBE ser uno de los siguientes: 0x0000001C si el bit C está establecido en el campo Flags. 0x00000024 si el bit C está despejado en el campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tamaño. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Obtiene el ángulo de inicio. Un valor de punto flotante no negativo de 32 bits que especifica el ángulo entre el eje x y el punto de inicio del arco. Cualquier valor es aceptable, pero DEBE interpretarse módulo 360, con el resultado utilizado en el rango de 0.0 inclusive a 360.0 exclusivo.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Establece el ángulo de inicio. Un valor de punto flotante no negativo de 32 bits que especifica el ángulo entre el eje x y el punto de inicio del arco. Cualquier valor es aceptable, pero DEBE interpretarse módulo 360, con el resultado utilizado en el rango de 0.0 inclusive a 360.0 exclusivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Obtiene el ángulo de barrido. Un valor de punto flotante de 32 bits que especifica la extensión del arco a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. Cualquier valor es aceptable, pero DEBE limitarse a -360.0 a 360.0 inclusive. Un valor positivo indica que el barrido se define en dirección horaria, y un valor negativo indica que se define en dirección antihoraria.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Establece el ángulo de barrido. Un valor de punto flotante de 32 bits que especifica la extensión del arco a dibujar, como un ángulo en grados medido desde el punto de inicio definido por el valor StartAngle. Cualquier valor es aceptable, pero DEBE limitarse a -360.0 a 360.0 inclusive. Un valor positivo indica que el barrido se define en dirección horaria, y un valor negativo indica que se define en dirección antihoraria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Obtiene los datos del rectángulo. Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse colineal con el arco. Este rectángulo define la posición, el tamaño y la forma del arco. El tipo de objeto en este campo se especifica mediante el valor del campo Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Establece los datos del rectángulo. Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse colineal con el arco. Este rectángulo define la posición, el tamaño y la forma del arco. El tipo de objeto en este campo se especifica mediante el valor del campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

