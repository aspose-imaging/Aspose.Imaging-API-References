---
title: "XmpDate"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la fecha en un paquete XMP."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Representa la fecha en un paquete XMP.

Un valor de fecha y hora se representa usando un subconjunto de los formatos definidos en Formatos de fecha y hora: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Inicializa una nueva instancia de la clase `XmpDate`. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Inicializa una nueva instancia de la clase `XmpDate`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | La cadena de formato ISO 8601 (ida y vuelta). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValue()](#getValue--) | Obtiene o establece el valor de la fecha. |
| [setValue(Date value)](#setValue-java.util.Date-) | Obtiene o establece el valor de la fecha. |
| [getFormat()](#getFormat--) | Obtiene la cadena de formato para el valor actual. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Devuelve el valor contenido en cadena en formato XMP. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Inicializa una nueva instancia de la clase `XmpDate`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dateTime | java.util.Date | Un valor de fecha y hora que se representa usando un subconjunto del formato ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Inicializa una nueva instancia de la clase `XmpDate`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dateString | java.lang.String | La representación en cadena de la fecha. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


La cadena de formato ISO 8601 (ida y vuelta).

Ver más: [ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Obtiene o establece el valor de la fecha.

Valor: El valor de la fecha.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Obtiene o establece el valor de la fecha.

Valor: El valor de la fecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Obtiene la cadena de formato para el valor actual.

Valor: La cadena de formato para el valor actual.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Devuelve el valor contenido en cadena en formato XMP.

**Returns:**
java.lang.String - Devuelve una cadena que contiene la representación xmp
