---
title: "Timecode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el valor del código de tiempo en video."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Representa el valor del código de tiempo en video.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Inicializa una nueva instancia de la clase `Timecode`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) | Obtiene o establece el formato usado en `TimeValue`. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | Obtiene o establece el formato usado en `TimeValue`. |
| [getTimeValue()](#getTimeValue--) | Obtiene o establece el valor de tiempo en el formato especificado. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Obtiene o establece el valor de tiempo en el formato especificado. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Devuelve el valor de cadena contenido en formato XMP. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `System.Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Inicializa una nueva instancia de la clase `Timecode`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | El formato de tiempo. |
| timeValue | java.lang.String | El valor de tiempo. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Obtiene o establece el formato usado en `TimeValue`.

Valor: El formato usado en `TimeValue`.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Obtiene o establece el formato usado en `TimeValue`.

Valor: El formato usado en `TimeValue`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Obtiene o establece el valor de tiempo en el formato especificado.

Valor: El valor de tiempo en el formato especificado.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Obtiene o establece el valor de tiempo en el formato especificado.

Valor: El valor de tiempo en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Devuelve el valor de cadena contenido en formato XMP.

**Returns:**
java.lang.String - Devuelve la cadena que contiene la representación xmp.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | Un objeto para comparar con este objeto. |

**Returns:**
boolean - verdadero si el objeto actual es igual al parámetro `other`; de lo contrario, falso.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `System.Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `System.Object` especificado es igual a esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
