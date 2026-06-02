---
title: "EmfCommentEmfSpool"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COMMENT_EMFSPOOL contiene registros EMFSPOOL incrustados."
type: docs
weight: 28
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

El registro EMR\_COMMENT\_EMFSPOOL contiene registros EMFSPOOL incrustados. Nota: los campos que no se describen en esta sección se especifican en la sección 2.3.3.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | Inicializa una nueva instancia de la clase `EmfCommentEmfSpool`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMFSPOOL. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMFSPOOL. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro EMR\_COMMENT\_EMFSPOOL. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro EMR\_COMMENT\_EMFSPOOL. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Obtiene o establece una matriz de bytes de longitud variable que contiene uno o más registros de definición de fuentes EMFSPOOL ([MS-EMFSPOOL] sección 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Obtiene o establece una matriz de bytes de longitud variable que contiene uno o más registros de definición de fuentes EMFSPOOL ([MS-EMFSPOOL] sección 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCommentEmfSpool`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


Inicializa una nueva instancia de la clase `EmfCommentEmfSpool`.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMFSPOOL. El valor 0x00000000 identifica esto como un registro EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Obtiene o establece un entero sin signo de 32 bits que identifica este registro de comentario como contenedor de registros EMFSPOOL. El valor 0x00000000 identifica esto como un registro EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


Obtiene o establece un entero sin signo de 32 bits que identifica el tipo de registro EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Obtiene o establece una matriz de bytes de longitud variable que contiene uno o más registros de definición de fuentes EMFSPOOL ([MS-EMFSPOOL] sección 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Obtiene o establece una matriz de bytes de longitud variable que contiene uno o más registros de definición de fuentes EMFSPOOL ([MS-EMFSPOOL] sección 2.2.3.3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

