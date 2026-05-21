---
title: "EmfPlusDrawPath"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusDrawPath especifica dibujar una ruta gráfica."
type: docs
weight: 25
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

El registro EmfPlusDrawPath especifica dibujar una ruta gráfica.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusDrawPath`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getPenId()](#getPenId--) | Obtiene o establece el identificador del bolígrafo Un entero sin signo de 32 bits que especifica un índice en la tabla de objetos EMF+ para un objeto EmfPlusPen (sección 2.2.1.7) que se usará para dibujar el EmfPlusPath. |
| [setPenId(int value)](#setPenId-int-) | Obtiene o establece el identificador del bolígrafo Un entero sin signo de 32 bits que especifica un índice en la tabla de objetos EMF+ para un objeto EmfPlusPen (sección 2.2.1.7) que se usará para dibujar el EmfPlusPath. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusDrawPath`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice del objeto EmfPlusPath (sección 2.2.1.6) que se dibujará, en la tabla de objetos EMF+. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice del objeto EmfPlusPath (sección 2.2.1.6) que se dibujará, en la tabla de objetos EMF+. El valor DEBE ser de 0 a 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Obtiene o establece el identificador del bolígrafo Un entero sin signo de 32 bits que especifica un índice en la tabla de objetos EMF+ para un objeto EmfPlusPen (sección 2.2.1.7) que se usará para dibujar el EmfPlusPath. El valor DEBE ser de 0 a 63, inclusive

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Obtiene o establece el identificador del bolígrafo Un entero sin signo de 32 bits que especifica un índice en la tabla de objetos EMF+ para un objeto EmfPlusPen (sección 2.2.1.7) que se usará para dibujar el EmfPlusPath. El valor DEBE ser de 0 a 63, inclusive

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

