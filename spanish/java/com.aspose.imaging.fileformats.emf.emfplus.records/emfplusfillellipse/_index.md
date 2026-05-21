---
title: "EmfPlusFillEllipse"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusFillEllipse especifica el relleno del interior de una elipse"
type: docs
weight: 33
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

El registro EmfPlusFillEllipse especifica el relleno del interior de una elipse
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusFillEllipse`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [isCompressed()](#isCompressed--) | Obtiene o establece un valor que indica si esta instancia está comprimida. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si esta instancia está comprimida. |
| [getBrushId()](#getBrushId--) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [getRectData()](#getRectData--) | Obtiene o establece los datos del rectángulo, ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtiene o establece los datos del rectángulo, ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la elipse. |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusFillEllipse`.

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

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Obtiene o establece un valor que indica si esta instancia está comprimida. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está desactivado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39).

Valor: `true` si esta instancia está comprimida; de lo contrario, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Obtiene o establece un valor que indica si esta instancia está comprimida. Si está establecido, RectData contiene un objeto EmfPlusRect (sección 2.2.2.38). Si está desactivado, RectData contiene un objeto EmfPlusRectF (sección 2.2.2.39).

Valor: `true` si esta instancia está comprimida; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. Esta definición se usa para rellenar el interior de la elipse.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtiene o establece el identificador del pincel, un entero sin signo de 32 bits que especifica el pincel, cuyo contenido está determinado por el bit S en el campo Flags. Esta definición se usa para rellenar el interior de la elipse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

