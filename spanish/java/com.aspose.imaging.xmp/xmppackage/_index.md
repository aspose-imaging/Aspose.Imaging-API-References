---
title: "XmpPackage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la abstracción base para el paquete XMP."
type: docs
weight: 19
url: /es/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Representa la abstracción base para el paquete XMP.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase `XmpPackage`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Obtiene el espacio de nombres XML. |
| [getPrefix()](#getPrefix--) | Obtiene el prefijo. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtiene el URI del espacio de nombres. |
| [getKeys()](#getKeys--) | Obtiene las claves en el paquete XMP. |
| [getCount()](#getCount--) | Obtiene el recuento de claves XMP. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determina si esta colección contiene la clave especificada. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Obtiene o establece el `Object` con la clave especificada. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Establece el `Object` con la clave especificada. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Agrega el valor a la clave especificada. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Agrega el valor a la clave especificada. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Obtiene el valor por la `key`. |
| [remove(String key)](#remove-java.lang.String-) | Elimina el valor con la clave especificada. |
| [clear()](#clear--) | Limpia esta instancia. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Establece el valor. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | Establece el valor. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Establece el valor del tipo XMP. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Inicializa una nueva instancia de la clase `XmpPackage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | java.lang.String | El prefijo. |
| namespaceUri | java.lang.String | El URI del espacio de nombres. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Obtiene el espacio de nombres XML.

Valor: El espacio de nombres XML.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtiene el prefijo.

Valor: El prefijo.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtiene el URI del espacio de nombres.

Valor: El URI del espacio de nombres.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Obtiene las claves en el paquete XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


Obtiene el recuento de claves XMP.

**Returns:**
int - el recuento de claves XMP.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determina si esta colección contiene la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La clave a comprobar. |

**Returns:**
boolean - `true` si la colección contiene la clave especificada; de lo contrario, `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Obtiene o establece el `Object` con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La clave que identifica el valor. |

**Returns:**
java.lang.Object - Devuelve el `Object` con la clave especificada.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Establece el `Object` con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La clave que identifica el valor. |
| valor | java.lang.Object | El valor del `Object`. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Agrega el valor a la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | java.lang.String | El valor al que agregar. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Agrega el valor a la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | java.lang.Object | El valor al que agregar. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


Obtiene el valor por la `key`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La clave del elemento XMP. |
| valor | java.lang.Object[] | El valor XMP. |

**Returns:**
boolean - `true`, si la colección contiene la `key`; de lo contrario, `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Elimina el valor con la clave especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La representación en cadena de la clave que está identificada con el valor eliminado. |

**Returns:**
boolean - Devuelve true si el valor con la clave especificada fue eliminado.
### clear() {#clear--}
```
public void clear()
```


Limpia esta instancia.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Establece el valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | El valor al que agregar. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


Establece el valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La representación en cadena de la clave que se identifica con el valor añadido. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | El valor al que agregar. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Establece el valor del tipo XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La representación en cadena de la clave que está identificada con el valor establecido. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | El valor al que establecer. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a la representación XML.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Devuelve un enumerador que recorre la colección.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Un `T:System.Collections.Generic.IEnumerator\`1` que puede usarse para iterar a través de la colección.
