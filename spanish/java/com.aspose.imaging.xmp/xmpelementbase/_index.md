---
title: "XmpElementBase"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el elemento base XMP que contiene atributos."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Representa el elemento base XMP que contiene atributos.
## Métodos

| Método | Descripción |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Agrega el atributo. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Obtiene el atributo. |
| [clearAttributes()](#clearAttributes--) | Elimina todos los atributos. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Agrega el atributo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| atributo | java.lang.String | El atributo. |
| valor | java.lang.String | El valor. |

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Obtiene el atributo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| atributo | java.lang.String | El atributo. |

**Returns:**
java.lang.String - Devuelve el atributo para el nombre de atributo especificado.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Elimina todos los atributos.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | Un objeto para comparar con este objeto. |

**Returns:**
boolean - verdadero si el objeto actual es igual al parámetro `other`; de lo contrario, falso.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `Object` especificado es igual a esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
