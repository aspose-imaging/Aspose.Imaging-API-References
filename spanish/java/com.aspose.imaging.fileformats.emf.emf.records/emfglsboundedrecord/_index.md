---
title: "EmfGlsBoundedRecord"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_GLSBOUNDEDRECORD especifica una función OpenGL con un rectángulo delimitador para la salida."
type: docs
weight: 63
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

El registro EMR\_GLSBOUNDEDRECORD especifica una función OpenGL con un rectángulo delimitador para la salida.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfGlsBoundedRecord`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define un rectángulo delimitador, en unidades de dispositivo, para la salida producida al ejecutar la función OpenGL. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define un rectángulo delimitador, en unidades de dispositivo, para la salida producida al ejecutar la función OpenGL. |
| [getCbData()](#getCbData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. |
| [setCbData(int value)](#setCbData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño, en bytes, del campo Data. |
| [getData()](#getData--) | Obtiene o establece una matriz opcional de bytes de longitud cbData que especifica los datos para la función OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece una matriz opcional de bytes de longitud cbData que especifica los datos para la función OpenGL. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfGlsBoundedRecord`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define un rectángulo delimitador, en unidades de dispositivo, para la salida producida al ejecutar la función OpenGL.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define un rectángulo delimitador, en unidades de dispositivo, para la salida producida al ejecutar la función OpenGL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

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

