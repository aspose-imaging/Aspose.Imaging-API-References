---
title: "EmfPlusDrawLines"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawlLines especifica dibujar una serie de líneas conectadas."
type: docs
weight: 24
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawlLines especifica dibujar una serie de líneas conectadas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawLines`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` está comprimido. |
| [getRelative()](#getRelative--) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` es relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusDrawClosedCurve` es relativo. |
| [getClosedShape()](#getClosedShape--) | Obtiene o establece un valor que indica si [closed shape]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | Obtiene o establece un valor que indica si [closed shape]. |
| [getPointData()](#getPointData--) | Obtiene o establece los datos del punto, una matriz de puntos Count que especifica los puntos de inicio y fin de las líneas a dibujar. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Obtiene o establece los datos del punto, una matriz de puntos Count que especifica los puntos de inicio y fin de las líneas a dibujar. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawLines`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar las líneas. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar las líneas. El valor DEBE estar entre 0 y 63, inclusive.

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

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


Obtiene o establece un valor que indica si [closed shape].

Valor: `true` si [closed shape]; de lo contrario, `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


Obtiene o establece un valor que indica si [closed shape].

Valor: `true` si [closed shape]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Obtiene o establece los datos del punto, una matriz de puntos Count que especifica los puntos de inicio y fin de las líneas a dibujar.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Obtiene o establece los datos del punto, una matriz de puntos Count que especifica los puntos de inicio y fin de las líneas a dibujar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

