---
title: "EmfComment"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COMMENT contiene datos privados arbitrarios."
type: docs
weight: 25
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

El registro EMR\_COMMENT contiene datos privados arbitrarios. Nota: los campos que no se describen en esta sección se especifican en la sección 2.3.3.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfComment`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Obtiene o establece una matriz de bytes opcional que especifica los datos privados. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Obtiene o establece una matriz de bytes opcional que especifica los datos privados. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtiene o establece el identificador del comentario. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtiene o establece el identificador del comentario. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfComment`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Obtiene o establece una matriz de bytes opcional que especifica los datos privados. El primer DWORD de estos datos NO DEBE ser uno de los valores de identificador de comentario predefinidos especificados en la sección 2.3.3. Los datos privados son desconocidos para EMF; solo son significativos para las aplicaciones que conocen el formato de los datos y cómo utilizarlos. Los registros de datos privados EMR\_COMMENT PUEDEN ser ignorados.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Obtiene o establece una matriz de bytes opcional que especifica los datos privados. El primer DWORD de estos datos NO DEBE ser uno de los valores de identificador de comentario predefinidos especificados en la sección 2.3.3. Los datos privados son desconocidos para EMF; solo son significativos para las aplicaciones que conocen el formato de los datos y cómo utilizarlos. Los registros de datos privados EMR\_COMMENT PUEDEN ser ignorados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

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

