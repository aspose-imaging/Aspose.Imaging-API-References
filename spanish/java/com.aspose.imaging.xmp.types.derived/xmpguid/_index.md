---
title: "XmpGuid"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el identificador único global XMP."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

Representa el identificador único global XMP.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Inicializa una nueva instancia de la clase `XmpGuid`. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | Inicializa una nueva instancia de la clase `XmpGuid`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPrefix()](#getPrefix--) | Obtiene o establece el prefijo como uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Obtiene o establece el prefijo como uuid. |
| [getValue()](#getValue--) | Obtiene o establece el valor. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Obtiene o establece el valor. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Obtiene el valor de cadena contenido en formato XMP. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Inicializa una nueva instancia de la clase `XmpGuid`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El valor. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


Inicializa una nueva instancia de la clase `XmpGuid`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| guid | java.util.UUID | El identificador único. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtiene o establece el prefijo como uuid.

Valor: El prefijo como uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


Obtiene o establece el prefijo como uuid.

Valor: El prefijo como uuid.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Obtiene o establece el valor.

Valor: El valor.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Obtiene o establece el valor.

Valor: El valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Obtiene el valor de cadena contenido en formato XMP.

**Returns:**
java.lang.String - Devuelve el valor de cadena contenido en formato XMP.
