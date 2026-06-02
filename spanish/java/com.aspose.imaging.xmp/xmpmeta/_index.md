---
title: "XmpMeta"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa los metadatos XMP."
type: docs
weight: 18
url: /es/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Representa metadatos xmp. Opcional. El propósito de este elemento es identificar los metadatos XMP dentro de texto XML general que podría contener otros usos no XMP de RDF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Inicializa una nueva instancia de la clase `XmpMeta`. |
| [XmpMeta()](#XmpMeta--) | Inicializa una nueva instancia de la clase `XmpMeta`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Obtiene o establece la versión del kit de herramientas Adobe Xmp. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Obtiene o establece la versión del kit de herramientas Adobe Xmp. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Agrega el atributo. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [equals(Object other)](#equals-java.lang.Object-) | Determina si el `System.Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Inicializa una nueva instancia de la clase `XmpMeta`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Versión del kit de herramientas Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Inicializa una nueva instancia de la clase `XmpMeta`.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Obtiene o establece la versión del kit de herramientas Adobe Xmp.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Obtiene o establece la versión del kit de herramientas Adobe Xmp.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a la representación XML.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Un objeto para comparar con este objeto. |

**Returns:**
boolean - verdadero si el objeto actual es igual al parámetro `other`; de lo contrario, falso.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determina si el `System.Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | java.lang.Object | El `System.Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `System.Object` especificado es igual a esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
