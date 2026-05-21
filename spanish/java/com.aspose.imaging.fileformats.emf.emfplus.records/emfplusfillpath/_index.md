---
title: "EmfPlusFillPath"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Registro de ruta de relleno FLAGS entero sin signo de 16 bits que proporciona información sobre cómo se debe ejecutar la operación y sobre la estructura del registro."
type: docs
weight: 34
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Registro de ruta de relleno FLAGS: entero sin signo de 16 bits que proporciona información sobre cómo se debe ejecutar la operación y sobre la estructura del registro. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 bit): Este bit indica el tipo de datos en el campo BrushId. Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). Si no está establecido, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+. X (1 bit): Reservado y DEBE ser ignorado. ObjectId (1 byte): El índice del objeto EmfPlusPath (sección 2.2.1.6) a rellenar, en la tabla de objetos EMF+. El valor DEBE estar entre 0 y 63, inclusive.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusFillPath`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isColor()](#isColor--) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [setColor(boolean value)](#setColor-boolean-) | Obtiene o establece un valor que indica si esta instancia es de color. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getBrushId()](#getBrushId--) | Obtiene o establece el ID del pincel. Un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Obtiene o establece el ID del pincel. Un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusFillPath`.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice del objeto EmfPlusPath (sección 2.2.1.6) a rellenar, en la tabla de objetos EMF+. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice del objeto EmfPlusPath (sección 2.2.1.6) a rellenar, en la tabla de objetos EMF+. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Obtiene o establece el ID del pincel. Un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Obtiene o establece el ID del pincel. Un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

