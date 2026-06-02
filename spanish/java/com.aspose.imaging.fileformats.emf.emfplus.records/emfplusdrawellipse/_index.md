---
title: "EmfPlusDrawEllipse"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawEllipse especifica dibujar una elipse."
type: docs
weight: 21
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawEllipse extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawEllipse especifica dibujar una elipse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawEllipse(EmfPlusRecord source)](#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawEllipse`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [getRectData()](#getRectData--) | Obtiene o establece los datos del rectángulo, ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtiene o establece los datos del rectángulo, ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse. |
### EmfPlusDrawEllipse(EmfPlusRecord source) {#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawEllipse(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawEllipse`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la elipse. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+ para dibujar la elipse. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

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

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Obtiene o establece los datos del rectángulo, ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Obtiene o establece los datos del rectángulo, ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

