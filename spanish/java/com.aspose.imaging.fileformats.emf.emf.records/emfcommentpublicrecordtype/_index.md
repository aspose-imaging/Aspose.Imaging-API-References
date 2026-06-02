---
title: "EmfCommentPublicRecordType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los tipos de registro EMR_COMMENT_PUBLIC especifican extensiones al procesamiento de EMF."
type: docs
weight: 31
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

Los tipos de registro EMR\_COMMENT\_PUBLIC especifican extensiones al procesamiento de EMF.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como especificador de datos públicos. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como especificador de datos públicos. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro de comentario público. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro de comentario público. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como especificador de datos públicos. El valor 0x43494447, que es la cadena ASCII \"CIDG\", identifica esto como un registro EMR\_COMMENT\_PUBLIC.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como especificador de datos públicos. El valor 0x43494447, que es la cadena ASCII \"CIDG\", identifica esto como un registro EMR\_COMMENT\_PUBLIC.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro de comentario público. Esto DEBERÍA ser uno de los valores listados en la tabla anterior, que están especificados en la enumeración EmrComment (sección 2.1.10), a menos que se hayan implementado tipos adicionales de registros de comentario público en el servidor de impresión.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro de comentario público. Esto DEBERÍA ser uno de los valores listados en la tabla anterior, que están especificados en la enumeración EmrComment (sección 2.1.10), a menos que se hayan implementado tipos adicionales de registros de comentario público en el servidor de impresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

