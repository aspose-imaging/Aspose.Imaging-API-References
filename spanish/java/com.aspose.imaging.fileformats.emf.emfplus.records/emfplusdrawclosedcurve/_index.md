---
title: "EmfPlusDrawClosedCurve"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawClosedCurve especifica dibujar una spline cardinal cerrada."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawClosedCurve especifica dibujar una spline cardinal cerrada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawClosedCurve`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. |
| [getRelative()](#getRelative--) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` es relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` es relativo. |
| [getTension()](#getTension--) | Obtiene o establece la tensión, un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. |
| [setTension(float value)](#setTension-float-) | Obtiene o establece la tensión, un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. |
| [getPointData()](#getPointData--) | Obtiene o establece los datos de punto, una matriz de Count puntos que especifican los extremos de las líneas que definen la spline. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtiene o establece los datos de punto, una matriz de Count puntos que especifican los extremos de las líneas que definen la spline. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawClosedCurve`. RecordType - Un entero sin signo de 16 bits que identifica este tipo de registro como EmfPlusDrawClosedCurve de la enumeración RecordType (sección 2.1.1.1). El valor DEBE ser 0x4017.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la curva cerrada. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la curva cerrada. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. Este bit indica si el campo PointData especifica datos comprimidos. Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota: Si el indicador Relative (abajo) está establecido, este indicador es indefinido y DEBE ser ignorado

Valor: `true` si está comprimido; de lo contrario, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. Este bit indica si el campo PointData especifica datos comprimidos. Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota: Si el indicador Relative (abajo) está establecido, este indicador es indefinido y DEBE ser ignorado

Valor: `true` si está comprimido; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está despejado, PointData especifica ubicaciones absolutas según el indicador C. Nota: Si este indicador está establecido, el indicador Compressed (arriba) es indefinido y DEBE ser ignorado

Valor: `true` si es relativo; de lo contrario, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` es relativo. Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está despejado, PointData especifica ubicaciones absolutas según el indicador C. Nota: Si este indicador está establecido, el indicador Compressed (arriba) es indefinido y DEBE ser ignorado

Valor: `true` si es relativo; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getTension() {#getTension--}
```
public float getTension()
```


Obtiene o establece la tensión Un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. Un valor de 0 indica que la spline es una secuencia de líneas rectas. A medida que el valor aumenta, la curva se vuelve más redondeada. Para más información, consulte [SPLINE77] y [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Obtiene o establece la tensión Un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. Un valor de 0 indica que la spline es una secuencia de líneas rectas. A medida que el valor aumenta, la curva se vuelve más redondeada. Para más información, consulte [SPLINE77] y [PETZOLD].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtiene o establece los datos del punto Un arreglo de Count puntos que especifican los extremos de las líneas que definen la spline. En una spline cardinal cerrada, la curva continúa a través del último punto del arreglo PointData y se conecta con el primer punto del arreglo. El tipo de datos en este arreglo se especifica mediante el campo Flags, como sigue: Tipo de datos Significado EmfPlusPointR object (section 2.2.2.37) Si el indicador P está establecido en Flags, los puntos especifican ubicaciones relativas. EmfPlusPointF object (section 2.2.2.36) Si los bits P y C están establecidos en el campo Flags, los puntos especifican ubicaciones absolutas. EmfPlusPoint object (section 2.2.2.35) Si el bit P está despejado y el bit C está establecido en el campo Flags, los puntos especifican ubicaciones relativas.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtiene o establece los datos del punto Un arreglo de Count puntos que especifican los extremos de las líneas que definen la spline. En una spline cardinal cerrada, la curva continúa a través del último punto del arreglo PointData y se conecta con el primer punto del arreglo. El tipo de datos en este arreglo se especifica mediante el campo Flags, como sigue: Tipo de datos Significado EmfPlusPointR object (section 2.2.2.37) Si el indicador P está establecido en Flags, los puntos especifican ubicaciones relativas. EmfPlusPointF object (section 2.2.2.36) Si los bits P y C están establecidos en el campo Flags, los puntos especifican ubicaciones absolutas. EmfPlusPoint object (section 2.2.2.35) Si el bit P está despejado y el bit C está establecido en el campo Flags, los puntos especifican ubicaciones relativas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

