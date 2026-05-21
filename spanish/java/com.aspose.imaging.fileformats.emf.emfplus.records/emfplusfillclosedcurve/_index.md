---
title: "EmfPlusFillClosedCurve"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusFillClosedCurve especifica el relleno del interior de una spline cardinal cerrada"
type: docs
weight: 32
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

El registro EmfPlusFillClosedCurve especifica el relleno del interior de una spline cardinal cerrada
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusFillClosedCurve`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` está comprimido. |
| [getWinding()](#getWinding--) | Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es winding. |
| [setWinding(boolean value)](#setWinding-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es winding. |
| [getRelative()](#getRelative--) | Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es relativo. |
| [getBrushId()](#getBrushId--) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el EmfPlusBrush, cuyo contenido está determinado por el bit S en el campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el EmfPlusBrush, cuyo contenido está determinado por el bit S en el campo Flags. |
| [getTension()](#getTension--) | Obtiene o establece la tensión, un valor de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. |
| [setTension(float value)](#setTension-float-) | Obtiene o establece la tensión, un valor de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. |
| [getPointData()](#getPointData--) | Obtiene o establece los datos de punto, una matriz de Count puntos que especifican los extremos de las líneas que definen la spline. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtiene o establece los datos de punto, una matriz de Count puntos que especifican los extremos de las líneas que definen la spline. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusFillClosedCurve`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

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

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` está comprimido. Este bit indica si el campo PointData especifica datos comprimidos. Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. ---------------------- Una operación de relleno \"winding\" llena áreas según la regla de \"paridad impar\". Según esta regla, se puede determinar si un punto de prueba está dentro o fuera de una curva cerrada de la siguiente manera: Dibuje una línea desde el punto de prueba a un punto que esté alejado de la curva. Si esa línea cruza la curva un número impar de veces, el punto de prueba está dentro de la curva; de lo contrario, el punto de prueba está fuera de la curva. --------------------- Una operación de relleno \"alternate\" llena áreas según la regla \"non-zero\". Según esta regla, se puede determinar si un punto de prueba está dentro o fuera de una curva cerrada de la siguiente manera: Dibuje una línea desde un punto de prueba a un punto que esté alejado de la curva. Cuente el número de veces que la curva cruza la línea de prueba de izquierda a derecha, y cuente el número de veces que la curva cruza la línea de prueba de derecha a izquierda. Si esos dos números son iguales, el punto de prueba está fuera de la curva; de lo contrario, el punto de prueba está dentro de la curva.

Valor: `true` si está comprimido; de lo contrario, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` está comprimido. Este bit indica si el campo PointData especifica datos comprimidos. Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. ---------------------- Una operación de relleno \"winding\" llena áreas según la regla de \"paridad impar\". Según esta regla, se puede determinar si un punto de prueba está dentro o fuera de una curva cerrada de la siguiente manera: Dibuje una línea desde el punto de prueba a un punto que esté alejado de la curva. Si esa línea cruza la curva un número impar de veces, el punto de prueba está dentro de la curva; de lo contrario, el punto de prueba está fuera de la curva. --------------------- Una operación de relleno \"alternate\" llena áreas según la regla \"non-zero\". Según esta regla, se puede determinar si un punto de prueba está dentro o fuera de una curva cerrada de la siguiente manera: Dibuje una línea desde un punto de prueba a un punto que esté alejado de la curva. Cuente el número de veces que la curva cruza la línea de prueba de izquierda a derecha, y cuente el número de veces que la curva cruza la línea de prueba de derecha a izquierda. Si esos dos números son iguales, el punto de prueba está fuera de la curva; de lo contrario, el punto de prueba está dentro de la curva.

Valor: `true` si está comprimido; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es winding. Este bit indica cómo realizar la operación de relleno. Si está establecido, el relleno es un relleno \"winding\". Si está despejado, el relleno es un relleno \"alternate\".

Valor: `true` si es winding; de lo contrario, `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es winding. Este bit indica cómo realizar la operación de relleno. Si está establecido, el relleno es un relleno \"winding\". Si está despejado, el relleno es un relleno \"alternate\".

Valor: `true` si es winding; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está despejado, PointData especifica ubicaciones absolutas según el indicador C. Nota: Si este indicador está establecido, el indicador C (arriba) es indefinido y DEBE ser ignorado.

Valor: `true` si es relativo; de lo contrario, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusFillClosedCurve` es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está despejado, PointData especifica ubicaciones absolutas según el indicador C. Nota: Si este indicador está establecido, el indicador C (arriba) es indefinido y DEBE ser ignorado.

Valor: `true` si es relativo; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el EmfPlusBrush, cuyo contenido está determinado por el bit S en el campo Flags. Este pincel se utiliza para rellenar el interior de la spline cardinal cerrada.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el EmfPlusBrush, cuyo contenido está determinado por el bit S en el campo Flags. Este pincel se utiliza para rellenar el interior de la spline cardinal cerrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


Obtiene o establece la tensión, un valor de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. Un valor de 0.0 indica que la spline es una secuencia de líneas rectas. A medida que el valor aumenta, la curva se vuelve más redondeada. Para más información, consulte [SPLINE77] y [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Obtiene o establece la tensión, un valor de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. Un valor de 0.0 indica que la spline es una secuencia de líneas rectas. A medida que el valor aumenta, la curva se vuelve más redondeada. Para más información, consulte [SPLINE77] y [PETZOLD].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtiene o establece los datos de punto, una matriz de Count puntos que especifican los extremos de las líneas que definen la spline. En una spline cardinal cerrada, la curva continúa a través del último punto en la matriz PointData y se conecta con el primer punto de la matriz

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtiene o establece los datos de punto, una matriz de Count puntos que especifican los extremos de las líneas que definen la spline. En una spline cardinal cerrada, la curva continúa a través del último punto en la matriz PointData y se conecta con el primer punto de la matriz

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

