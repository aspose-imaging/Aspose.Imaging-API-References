---
title: "EmfPlusDrawRects"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawRects especifica dibujar una serie de rectángulos."
type: docs
weight: 27
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawRects extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawRects especifica dibujar una serie de rectángulos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawRects(EmfPlusRecord source)](#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawRects`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getRectData()](#getRectData--) | Obtiene o establece los datos del rectángulo Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Obtiene o establece los datos del rectángulo Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo. |
### EmfPlusDrawRects(EmfPlusRecord source) {#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawRects(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawRects`.

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


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar los rectángulos. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar los rectángulos. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Obtiene o establece los datos del rectángulo Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Obtiene o establece los datos del rectángulo Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

