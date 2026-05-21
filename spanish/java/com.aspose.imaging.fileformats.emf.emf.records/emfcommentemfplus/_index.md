---
title: "EmfCommentEmfPlus"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COMMENT_EMFPLUS contiene registros EMF incrustados."
type: docs
weight: 27
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

El registro EMR\\_COMMENT\\_EMFPLUS contiene registros EMF+ incrustados. Nota: los campos que no se describen en esta sección se especifican en la sección 2.3.3.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCommentEmfPlus`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMF+. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMF+. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Obtiene o establece una matriz de bytes que contiene uno o más registros EMF+ ([MS-EMFPLUS] sección 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Obtiene o establece una matriz de bytes que contiene uno o más registros EMF+ ([MS-EMFPLUS] sección 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCommentEmfPlus`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMF+ . El valor 0x2B464D45, que es la cadena ASCII \"+FME\", identifica esto como un registro EMR\\_COMMENT\\_EMFPLUS.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMF+ . El valor 0x2B464D45, que es la cadena ASCII \"+FME\", identifica esto como un registro EMR\\_COMMENT\\_EMFPLUS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Obtiene o establece una matriz de bytes que contiene uno o más registros EMF+ ([MS-EMFPLUS] sección 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Obtiene o establece una matriz de bytes que contiene uno o más registros EMF+ ([MS-EMFPLUS] sección 2.3.1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

