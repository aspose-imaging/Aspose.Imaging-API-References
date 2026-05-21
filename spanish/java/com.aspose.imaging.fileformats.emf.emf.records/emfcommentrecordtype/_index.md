---
title: "EmfCommentRecordType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los tipos de registro de comentarios definen formatos para especificar registros de inserción de datos privados arbitrarios en otros formatos de metarchivo y agregar comandos nuevos o de propósito especial."
type: docs
weight: 32
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

Los tipos de registro de comentario definen formatos para especificar datos privados arbitrarios, incrustar registros en otros formatos de metafile y agregar comandos nuevos o de propósito especial.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDataSize()](#getDataSize--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que sigue. |
| [setDataSize(int value)](#setDataSize-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que sigue. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtiene o establece el identificador del comentario. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtiene o establece el identificador del comentario. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que sigue. NO DEBE incluir el tamaño de sí mismo ni el tamaño del campo AlignmentPadding, si está presente.

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, de los campos CommentIdentifier y CommentRecordParm en el campo RecordBuffer que sigue. NO DEBE incluir el tamaño de sí mismo ni el tamaño del campo AlignmentPadding, si está presente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtiene o establece el identificador del comentario.

Valor: El identificador del comentario.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtiene o establece el identificador del comentario.

Valor: El identificador del comentario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

