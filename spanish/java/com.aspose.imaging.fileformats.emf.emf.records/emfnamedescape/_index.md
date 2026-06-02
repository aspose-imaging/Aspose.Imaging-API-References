---
title: "EmfNamedEscape"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro MR_NAMEDESCAPE pasa información arbitraria a un controlador de impresora especificado."
type: docs
weight: 75
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

El registro MR\_NAMEDESCAPE pasa información arbitraria a un controlador de impresora especificado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfNamedEscape`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el campo DriverName. |
| [setCjDriver(int value)](#setCjDriver-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el campo DriverName. |
| [getCjIn()](#getCjIn--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora. |
| [setCjIn(int value)](#setCjIn-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora. |
| [getDriverName()](#getDriverName--) | Obtiene o establece una cadena de caracteres Unicode de 16 bits que especifica el nombre del controlador de impresora que recibirá los datos. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Obtiene o establece una cadena de caracteres Unicode de 16 bits que especifica el nombre del controlador de impresora que recibirá los datos. |
| [getData()](#getData--) | Obtiene o establece los datos a pasar al controlador de impresora. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece los datos a pasar al controlador de impresora. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfNamedEscape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el campo DriverName. Este valor DEBE ser un número par.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el campo DriverName. Este valor DEBE ser un número par.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes a pasar al controlador de impresora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Obtiene o establece una cadena de caracteres Unicode de 16 bits que especifica el nombre del controlador de impresora que recibirá los datos. Este valor DEBE tener una longitud de cjDriver bytes y DEBE terminar con un carácter nulo.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Obtiene o establece una cadena de caracteres Unicode de 16 bits que especifica el nombre del controlador de impresora que recibirá los datos. Este valor DEBE tener una longitud de cjDriver bytes y DEBE terminar con un carácter nulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtiene o establece los datos a pasar al controlador de impresora. DEBE haber cjIn bytes disponibles.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtiene o establece los datos a pasar al controlador de impresora. DEBE haber cjIn bytes disponibles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

