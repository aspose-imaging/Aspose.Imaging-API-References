---
title: XmpPackage
second_title: Aspose.Imaging for Java API Reference
description: Represents base abstraction for XMP package.
type: docs
weight: 18
url: /com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Represents base abstraction for XMP package.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Initializes a new instance of the `XmpPackage` class. |
## Methods

| Method | Description |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Gets the XML namespace. |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the namespace URI. |
| [getKeys()](#getKeys--) | Gets the keys in XMP package. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines whether the specified key contains key. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Gets or sets the `Object` with the specified key. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Sets the `Object` with the specified key. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Adds the value. |
| [remove(String key)](#remove-java.lang.String-) | Remove the value with the specified key. |
| [clear()](#clear--) | Clears this instance. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Sets the value. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Sets the XMP type value. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Initializes a new instance of the `XmpPackage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |
| namespaceUri | java.lang.String | The namespace URI. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Gets the XML namespace.

Value: The XML namespace.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets the prefix.

Value: The prefix.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gets the namespace URI.

Value: The namespace URI.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Gets the keys in XMP package.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determines whether the specified key contains key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key to be checked. |

**Returns:**
boolean - Returns true if the specified key contains key.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Gets or sets the `Object` with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key that identifies value. |

**Returns:**
java.lang.Object - Returns the `Object` with the specified key.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Sets the `Object` with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key that identifies value. |
| value | java.lang.Object | The `Object` value. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Adds the value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.String | The value to add to. |

### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Remove the value with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with removed value. |

**Returns:**
boolean - Returns true if the value with the specified key was removed.
### clear() {#clear--}
```
public void clear()
```


Clears this instance.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Sets the value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | The value to add to. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Sets the XMP type value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | The value to set to. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - A `T:System.Collections.Generic.IEnumerator\`1` that can be used to iterate through the collection.
