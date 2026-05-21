---
title: "EmfPlusDrawBeziers"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawBeziers especifica dibujar una secuencia de curvas de Bézier conectadas."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawBeziers especifica el dibujo de una secuencia de curvas Bézier conectadas. El orden de los puntos de datos Bézier es el punto de inicio, punto de control 1, punto de control 2 y punto final. Para más información, consulte [MSDN-DrawBeziers].
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawBeziers`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [getRelative()](#getRelative--) | Obtiene o establece un valor que indica si PointData es relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtiene o establece un valor que indica si PointData es relativo. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getPointData()](#getPointData--) | Obtiene o establece los datos del punto, una matriz de Count puntos que especifican los puntos de inicio, fin y control de las curvas Bézier. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtiene o establece los datos del punto, una matriz de Count puntos que especifican los puntos de inicio, fin y control de las curvas Bézier. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawBeziers`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtiene o establece un valor que indica si PointData está comprimido. Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está desactivado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota: Si la bandera Relative (abajo) está establecida, esta bandera es indefinida y DEBE ser ignorada.

Valor: `true` si está comprimido; de lo contrario, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si PointData está comprimido. Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está desactivado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota: Si la bandera Relative (abajo) está establecida, esta bandera es indefinida y DEBE ser ignorada.

Valor: `true` si está comprimido; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Obtiene o establece un valor que indica si PointData es relativo. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está desactivado, PointData especifica ubicaciones absolutas según la bandera C. Nota: Si esta bandera está establecida, la bandera C (arriba) es indefinida y DEBE ser ignorada.

Valor: `true` si es relativo; de lo contrario, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Obtiene o establece un valor que indica si PointData es relativo. Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está desactivado, PointData especifica ubicaciones absolutas según la bandera C. Nota: Si esta bandera está establecida, la bandera C (arriba) es indefinida y DEBE ser ignorada.

Valor: `true` si es relativo; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar las curvas Bézier. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar las curvas Bézier. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtiene o establece los datos del punto, una matriz de Count puntos que especifican los puntos de inicio, fin y control de las curvas Bézier. La coordenada final de una curva Bézier es la coordenada inicial de la siguiente. Los puntos de control se utilizan para producir el efecto Bézier. El tipo de datos en esta matriz se especifica mediante el campo Flags, como sigue: Tipo de datos Significado EmfPlusPointR object (section 2.2.2.37) Si la bandera P está establecida en Flags, los puntos especifican ubicaciones relativas. EmfPlusPointF object (section 2.2.2.36) Si los bits P y C están despejados en el campo Flags, los puntos especifican ubicaciones absolutas. EmfPlusPoint object (section 2.2.2.35) Si el bit P está despejado y el bit C está establecido en Flags, los puntos especifican ubicaciones relativas. Una curva Bézier no pasa por sus puntos de control. Los puntos de control actúan como

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtiene o establece los datos del punto, una matriz de Count puntos que especifican los puntos de inicio, fin y control de las curvas Bézier. La coordenada final de una curva Bézier es la coordenada inicial de la siguiente. Los puntos de control se utilizan para producir el efecto Bézier. El tipo de datos en esta matriz se especifica mediante el campo Flags, como sigue: Tipo de datos Significado EmfPlusPointR object (section 2.2.2.37) Si la bandera P está establecida en Flags, los puntos especifican ubicaciones relativas. EmfPlusPointF object (section 2.2.2.36) Si los bits P y C están despejados en el campo Flags, los puntos especifican ubicaciones absolutas. EmfPlusPoint object (section 2.2.2.35) Si el bit P está despejado y el bit C está establecido en Flags, los puntos especifican ubicaciones relativas. Una curva Bézier no pasa por sus puntos de control. Los puntos de control actúan como

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

