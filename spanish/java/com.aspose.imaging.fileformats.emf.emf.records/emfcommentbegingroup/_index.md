---
title: "EmfCommentBeginGroup"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COMMENT_BEGINGROUP especifica el comienzo de un grupo de registros de dibujo."
type: docs
weight: 26
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

El registro EMR\_COMMENT\_BEGINGROUP especifica el comienzo de un grupo de registros de dibujo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfCommentBeginGroup`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRectangle()](#getRectangle--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida en coordenadas lógicas. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida en coordenadas lógicas. |
| [getNDescription()](#getNDescription--) | Obtiene o establece el número de caracteres Unicode en la cadena de descripción opcional que sigue. |
| [setNDescription(int value)](#setNDescription-int-) | Obtiene o establece el número de caracteres Unicode en la cadena de descripción opcional que sigue. |
| [getDescription()](#getDescription--) | Obtiene o establece una cadena Unicode opcional, terminada en nulo, que describe este grupo de registros. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Obtiene o establece una cadena Unicode opcional, terminada en nulo, que describe este grupo de registros. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfCommentBeginGroup`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida en coordenadas lógicas.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica el rectángulo de salida en coordenadas lógicas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


Obtiene o establece el número de caracteres Unicode en la cadena de descripción opcional que sigue.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


Obtiene o establece el número de caracteres Unicode en la cadena de descripción opcional que sigue.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtiene o establece una cadena Unicode opcional, terminada en nulo, que describe este grupo de registros.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Obtiene o establece una cadena Unicode opcional, terminada en nulo, que describe este grupo de registros.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

