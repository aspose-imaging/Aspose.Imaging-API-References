---
title: "EmfPlusDrawImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawImage especifica dibujar una imagen escalada."
type: docs
weight: 22
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawImage especifica dibujar una imagen escalada.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawImage`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Obtiene o establece un valor que indica si el PointData está comprimido. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getImageAttributesId()](#getImageAttributesId--) | Obtiene o establece el identificador de los atributos de imagen Un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Obtiene o establece el identificador de los atributos de imagen Un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+. |
| [getRectData()](#getRectData--) | Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la imagen. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la imagen. |
| [getSrcRect()](#getSrcRect--) | Obtiene o establece el rectángulo de origen Un objeto EmfPlusRectF que especifica una porción de la imagen a renderizar. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Obtiene o establece el rectángulo de origen Un objeto EmfPlusRectF que especifica una porción de la imagen a renderizar. |
| [getSrcUnit()](#getSrcUnit--) | Obtiene o establece la unidad de origen entero con signo de 32 bits que especifica las unidades del campo SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Obtiene o establece la unidad de origen entero con signo de 32 bits que especifica las unidades del campo SrcRect. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawImage`.

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


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusImage (sección 2.2.1.4) en la tabla de objetos EMF+, que especifica la imagen a renderizar. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice de un objeto EmfPlusImage (sección 2.2.1.4) en la tabla de objetos EMF+, que especifica la imagen a renderizar. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Obtiene o establece el identificador de los atributos de imagen Un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Obtiene o establece el identificador de los atributos de imagen Un entero sin signo de 32 bits que especifica el índice de un objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la imagen. La porción de la imagen especificada por el campo SrcRect se escala para ajustarse a este rectángulo.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Obtiene o establece los datos del rectángulo Ya sea un objeto EmfPlusRect o EmfPlusRectF que define el cuadro delimitador de la imagen. La porción de la imagen especificada por el campo SrcRect se escala para ajustarse a este rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Obtiene o establece el rectángulo de origen Un objeto EmfPlusRectF que especifica una porción de la imagen a renderizar. La porción de la imagen especificada por este rectángulo se escala para ajustarse al rectángulo de destino especificado por el campo RectData.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Obtiene o establece el rectángulo de origen Un objeto EmfPlusRectF que especifica una porción de la imagen a renderizar. La porción de la imagen especificada por este rectángulo se escala para ajustarse al rectángulo de destino especificado por el campo RectData.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Obtiene o establece la unidad de origen entero con signo de 32 bits que especifica las unidades del campo SrcRect. DEBE ser el miembro UnitTypePixel de la enumeración UnitType (sección 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Obtiene o establece la unidad de origen entero con signo de 32 bits que especifica las unidades del campo SrcRect. DEBE ser el miembro UnitTypePixel de la enumeración UnitType (sección 2.1.1.33).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

