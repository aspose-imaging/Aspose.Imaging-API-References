---
title: "EmfMetafileHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los tipos de registro EMR_HEADER definen los puntos de inicio de los metarchivos EMF y especifican las propiedades del dispositivo en el que se creó la imagen del metarchivo."
type: docs
weight: 70
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

Los tipos de registro EMR\\_HEADER definen los puntos de inicio de los metarchivos EMF y especifican las propiedades del dispositivo en el que se creó la imagen del metarchivo. La información en el registro de encabezado permite que los metarchivos EMF sean independientes de cualquier dispositivo de salida específico. El valor del campo Size puede usarse para distinguir entre los diferentes tipos de registro EMR\\_HEADER enumerados anteriormente en esta sección. Existen tres encabezados posibles: el encabezado base, que es el registro EmfMetafileHeader. La parte de tamaño fijo de este encabezado tiene 88 bytes y contiene un objeto Header. El primer encabezado de extensión, que es el registro EmfMetafileHeaderExtension1. La parte de tamaño fijo de este encabezado tiene 100 bytes y contiene un objeto Header y un objeto HeaderExtension1 (sección 2.2.10). El segundo encabezado de extensión, que es el registro EmfMetafileHeaderExtension2. La parte de tamaño fijo de este encabezado tiene 108 bytes y contiene un objeto Header, un objeto HeaderExtension1 y un objeto HeaderExtension2 (sección 2.2.11).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfMetafileHeader`. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Inicializa una nueva instancia de la clase `EmfMetafileHeader`. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Inicializa una nueva instancia de la clase `EmfMetafileHeader`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Obtiene un objeto Header (sección 2.2.9), que contiene información sobre el contenido y la estructura del metafile |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Establece un objeto Header (sección 2.2.9), que contiene información sobre el contenido y la estructura del metafile |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | Obtiene una matriz opcional de bytes que contiene el resto del registro de encabezado EMF. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | Establece una matriz opcional de bytes que contiene el resto del registro de encabezado EMF. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | Obtiene el búfer de descripción EMF Una matriz opcional de bytes que contiene la cadena de descripción EMF, que no necesita ser contigua con la parte fija del registro EmfMetafileHeader. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | Establece el búfer de descripción EMF Una matriz opcional de bytes que contiene la cadena de descripción EMF, que no necesita ser contigua con la parte fija del registro EmfMetafileHeader. |
| [getEmfDescription()](#getEmfDescription--) | Obtiene la descripción EMF Una cadena Unicode UTF16-LE opcional, terminada en nulo, de longitud y contenido arbitrarios. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | Establece la descripción EMF Una cadena Unicode UTF16-LE opcional, terminada en nulo, de longitud y contenido arbitrarios. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Inicializa una nueva instancia de la clase `EmfMetafileHeader`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El registro. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Inicializa una nueva instancia de la clase `EmfMetafileHeader`.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Inicializa una nueva instancia de la clase `EmfMetafileHeader`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | El encabezado. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Obtiene un objeto Header (sección 2.2.9), que contiene información sobre el contenido y la estructura del metafile

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Establece un objeto Header (sección 2.2.9), que contiene información sobre el contenido y la estructura del metafile

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


Obtiene una matriz opcional de bytes que contiene el resto del registro de encabezado EMF. El tamaño de este campo DEBE ser múltiplo de 4 bytes.

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


Establece una matriz opcional de bytes que contiene el resto del registro de encabezado EMF. El tamaño de este campo DEBE ser múltiplo de 4 bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


Obtiene el búfer de descripción EMF Una matriz opcional de bytes que contiene la cadena de descripción EMF, que no necesita ser contigua con la parte fija del registro EmfMetafileHeader. En consecuencia, el campo en este búfer etiquetado como "UndefinedSpace" es opcional y DEBE ser ignorado.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


Establece el búfer de descripción EMF Una matriz opcional de bytes que contiene la cadena de descripción EMF, que no necesita ser contigua con la parte fija del registro EmfMetafileHeader. En consecuencia, el campo en este búfer etiquetado como "UndefinedSpace" es opcional y DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


Obtiene la descripción EMF Una cadena Unicode UTF16-LE opcional, terminada en nulo, de longitud y contenido arbitrarios. Su ubicación en el registro y el número de caracteres se especifican mediante los campos offDescription y nDescription, respectivamente, en EmfHeader. Si el valor de cualquiera de los campos es cero, no hay cadena de descripción presente.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


Establece la descripción EMF Una cadena Unicode UTF16-LE opcional, terminada en nulo, de longitud y contenido arbitrarios. Su ubicación en el registro y el número de caracteres se especifican mediante los campos offDescription y nDescription, respectivamente, en EmfHeader. Si el valor de cualquiera de los campos es cero, no hay cadena de descripción presente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

