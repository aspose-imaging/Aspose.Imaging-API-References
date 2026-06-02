---
title: "EmfPlusFillRects"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusFillRects especifica el relleno de los interiores de una serie de rectángulos"
type: docs
weight: 37
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

El registro EmfPlusFillRects especifica el relleno de los interiores de una serie de rectángulos
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusFillRects`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si este `EmfPlusFillRects` está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si este `EmfPlusFillRects` está comprimido. |
| [getBrushId()](#getBrushId--) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [getRectData()](#getRectData--) | Obtiene o establece los datos del rectángulo. Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Obtiene o establece los datos del rectángulo. Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo. |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusFillRects`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtiene o establece un valor que indica si esta instancia es de color. Si está establecida, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si no está establecida, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+.

Valor: `true` si esta instancia es de color; de lo contrario, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es de color. Si está establecida, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si no está establecida, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+.

Valor: `true` si esta instancia es de color; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtiene o establece un valor que indica si este `EmfPlusFillRects` está comprimido. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39) objeto

Valor: `true` si está comprimido; de lo contrario, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si este `EmfPlusFillRects` está comprimido. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está despejado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39) objeto

Valor: `true` si está comprimido; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Obtiene o establece los datos del rectángulo. Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Obtiene o establece los datos del rectángulo. Una matriz de objetos EmfPlusRect o EmfPlusRectF de longitud Count que define los datos del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

