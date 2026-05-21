---
title: "XmpTrailerPi"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la instrucción de procesamiento del pie XMP."
type: docs
weight: 23
url: /es/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Representa la instrucción de procesamiento del pie XMP.

La parte end=\"w\" o end=\"r\" deberá ser usada por los procesadores de escaneo de paquetes para determinar si el XMP puede modificarse in situ.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Inicializa una nueva instancia de la clase `XmpTrailerPi`. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Inicializa una nueva instancia de la clase `XmpTrailerPi`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isWritable()](#isWritable--) | Obtiene o establece un valor que indica si esta instancia es editable. |
| [setWritable(boolean value)](#setWritable-boolean-) | Obtiene o establece un valor que indica si esta instancia es editable. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor xmp a la representación xml. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `System.Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Inicializa una nueva instancia de la clase `XmpTrailerPi`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isWritable | boolean | Indica si el trailer es escribible. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Inicializa una nueva instancia de la clase `XmpTrailerPi`.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Obtiene o establece un valor que indica si esta instancia es editable.

Valor: `true` si esta instancia es escribible; de lo contrario, `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es editable.

Valor: `true` si esta instancia es escribible; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor xmp a la representación xml.

**Returns:**
java.lang.String - Devuelve la representación XML de XMP.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Un objeto para comparar con este objeto. |

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
