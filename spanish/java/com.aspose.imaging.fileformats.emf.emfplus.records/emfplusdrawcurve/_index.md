---
title: "EmfPlusDrawCurve"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawCurve especifica el dibujo de una spline cardinal NOTA ObjectID 1 byte El índice de un objeto EmfPlusPen sección 2.2.1.7 en la tabla de objetos EMF para dibujar la curva."
type: docs
weight: 19
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawCurve especifica el dibujo de una spline cardinal NOTA: ObjectID (1 byte): El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la curva. El valor DEBE ser de 0 a 63, inclusive.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawCurve`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getTension()](#getTension--) | Obtiene o establece la tensión, un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. |
| [setTension(float value)](#setTension-float-) | Obtiene o establece la tensión, un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline al pasar por los puntos. |
| [getNumSegments()](#getNumSegments--) | Obtiene o establece el recuento de segmentos Un entero sin signo de 32 bits que especifica el número de segmentos de línea que forman la spline. |
| [setNumSegments(int value)](#setNumSegments-int-) | Obtiene o establece el recuento de segmentos Un entero sin signo de 32 bits que especifica el número de segmentos de línea que forman la spline. |
| [getPointData()](#getPointData--) | Obtiene o establece una matriz de enteros con signo de 32 bits o de números de punto flotante de 32 bits de longitud Count que define los valores de coordenadas de los puntos finales de las líneas a trazar. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtiene o establece una matriz de enteros con signo de 32 bits o de números de punto flotante de 32 bits de longitud Count que define los valores de coordenadas de los puntos finales de las líneas a trazar. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawCurve`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la curva. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la curva. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

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

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Obtiene o establece el recuento de segmentos Un entero sin signo de 32 bits que especifica el número de segmentos de línea que forman la spline.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Obtiene o establece el recuento de segmentos Un entero sin signo de 32 bits que especifica el número de segmentos de línea que forman la spline.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtiene o establece una matriz de enteros con signo de 32 bits o de números de punto flotante de 32 bits de longitud Count que define los valores de coordenadas de los puntos finales de las líneas a trazar.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtiene o establece una matriz de enteros con signo de 32 bits o de números de punto flotante de 32 bits de longitud Count que define los valores de coordenadas de los puntos finales de las líneas a trazar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

