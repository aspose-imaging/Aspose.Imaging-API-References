---
title: XmpPackage
second_title: Aspose.Imaging for Java API Reference
description: Represents base abstraction for XMP package.
type: docs
weight: 19
url: /java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class XmpPackage implements Iterable<Map.Entry<String,XmpValue>>
```

Represents base abstraction for XMP package.
## Methods

| Method | Description |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Gets the XML namespace. |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the namespace URI. |
| [getKeys()](#getKeys--) | Gets the keys in XMP package. |
| [getCount()](#getCount--) | Gets the XMP key count. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Gets the first XMP attribute or element value with by specified `key`. |
| [set_Item(String key, XmpValue value)](#set-Item-java.lang.String-com.aspose.imaging.xmp.types.XmpValue-) | Sets the first XMP attribute or element value with by specified `key`. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines whether this collection specified key. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Adds the value to the specified key. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Adds the value to the specified key. |
| [tryGetValue(String key, XmpValue[] value)](#tryGetValue-java.lang.String-com.aspose.imaging.xmp.types.XmpValue---) | Gets the value by the `key`. |
| [remove(String key)](#remove-java.lang.String-) | Removes the first element or attribute value with the specified key. |
| [clear()](#clear--) | Clears this instance. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Sets the value. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | Sets the value. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Sets the XMP type value. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
### getXmlNamespace() {#getXmlNamespace--}
```
public final String getXmlNamespace()
```


Gets the XML namespace.

Value: The XML namespace.

**Returns:**
java.lang.String - the XML namespace.
### getPrefix() {#getPrefix--}
```
public final String getPrefix()
```


Gets the prefix.

Value: The prefix.

**Returns:**
java.lang.String - the prefix.
### getNamespaceUri() {#getNamespaceUri--}
```
public final String getNamespaceUri()
```


Gets the namespace URI.

Value: The namespace URI.

**Returns:**
java.lang.String - the namespace URI.
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


Gets the keys in XMP package.

Value: The keys in XMP package.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> - the keys in XMP package.
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the XMP key count.

**Returns:**
int - the XMP key count.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XmpValue get_Item(String key)
```


Gets the first XMP attribute or element value with by specified `key`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key that identifies value. Value: The [XmpValue](../../com.aspose.imaging.xmp.types/xmpvalue). |

**Returns:**
[XmpValue](../../com.aspose.imaging.xmp.types/xmpvalue) - Returns the [XmpValue](../../com.aspose.imaging.xmp.types/xmpvalue) by the specified key.
### set_Item(String key, XmpValue value) {#set-Item-java.lang.String-com.aspose.imaging.xmp.types.XmpValue-}
```
public void set_Item(String key, XmpValue value)
```


Sets the first XMP attribute or element value with by specified `key`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key that identifies value. Value: The [XmpValue](../../com.aspose.imaging.xmp.types/xmpvalue). |
| value | [XmpValue](../../com.aspose.imaging.xmp.types/xmpvalue) | the first XMP attribute or element value with by specified `key`. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determines whether this collection specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key to be checked. |

**Returns:**
boolean - `` if the `IDictionary\{TKey, TValue\}` contains the specified key; otherwise, ``.
### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Adds the value to the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.String | The value to add to. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Adds the value to the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.Object | The value to add to. |

### tryGetValue(String key, XmpValue[] value) {#tryGetValue-java.lang.String-com.aspose.imaging.xmp.types.XmpValue---}
```
public final boolean tryGetValue(String key, XmpValue[] value)
```


Gets the value by the `key`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The XMP element key. |
| value | [XmpValue\[\]](../../com.aspose.imaging.xmp.types/xmpvalue) | The XMP value. |

**Returns:**
boolean - ``, if the `IDictionary\{TKey, TValue\}` contains the `key`; otherwise, ``.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Removes the first element or attribute value with the specified key.

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

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


Sets the value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | The value to add to. |

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

### iterator() {#iterator--}
```
public final Iterator<Map.Entry<String,XmpValue>> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
java.util.Iterator<java.util.Map.Entry<java.lang.String,com.aspose.imaging.xmp.types.XmpValue>> - A `System.Collections.Generic.IEnumerator\`1` that can be used to iterate through the collection.
