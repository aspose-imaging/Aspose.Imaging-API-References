---
title: "XmpHeaderPi"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la instrucción de procesamiento del encabezado XMP."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Representa la instrucción de procesamiento del encabezado XMP.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Inicializa una nueva instancia de la clase `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Inicializa una nueva instancia de la clase `XmpHeaderPi`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getGuid()](#getGuid--) | Representa el GUID del encabezado. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Representa el GUID del encabezado. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `System.Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Inicializa una nueva instancia de la clase `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Inicializa una nueva instancia de la clase `XmpHeaderPi`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| guid | java.lang.String | El identificador único. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Representa el GUID del encabezado.

El texto del PI de encabezado contiene un GUID, lo que hace que sea poco probable que aparezca accidentalmente en el flujo de datos.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Representa el GUID del encabezado.

El texto del PI de encabezado contiene un GUID, lo que hace que sea poco probable que aparezca accidentalmente en el flujo de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a la representación XML.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indica si el objeto actual es igual a otro objeto del mismo tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Un objeto para comparar con este objeto. |

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
