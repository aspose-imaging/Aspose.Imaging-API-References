---
title: "EmfGlsRecord"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_GLSRECORD especifica una función OpenGL."
type: docs
weight: 64
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

El registro EMR\_GLSRECORD especifica una función OpenGL.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfGlsRecord`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCbData()](#getCbData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. |
| [setCbData(int value)](#setCbData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. |
| [getData()](#getData--) | Obtiene o establece una matriz opcional de bytes de longitud cbData que especifica los datos para la función OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece una matriz opcional de bytes de longitud cbData que especifica los datos para la función OpenGL. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfGlsRecord`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. Si este valor es cero, no se adjuntan datos a este registro.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. Si este valor es cero, no se adjuntan datos a este registro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtiene o establece una matriz opcional de bytes de longitud cbData que especifica los datos para la función OpenGL.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtiene o establece una matriz opcional de bytes de longitud cbData que especifica los datos para la función OpenGL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

