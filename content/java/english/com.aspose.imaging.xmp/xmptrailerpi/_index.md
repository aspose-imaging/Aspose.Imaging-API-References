---
title: XmpTrailerPi
second_title: Aspose.Imaging for Java API Reference
description: Represents XMP trailer processing instruction.
type: docs
weight: 22
url: /com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Represents XMP trailer processing instruction.

The end="w" or end="r" portion shall be used by packet scanning processors to determine whether the XMP may be modified in-place.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Initializes a new instance of the `XmpTrailerPi` class. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Initializes a new instance of the `XmpTrailerPi` class. |
## Methods

| Method | Description |
| --- | --- |
| [isWritable()](#isWritable--) | Gets or sets a value indicating whether this instance is writable. |
| [setWritable(boolean value)](#setWritable-boolean-) | Gets or sets a value indicating whether this instance is writable. |
| [getXmlValue()](#getXmlValue--) | Converts xmp value to the xml representation. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `System.Object`, is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Initializes a new instance of the `XmpTrailerPi` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isWritable | boolean | Inditacates whether trailer is writable. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Initializes a new instance of the `XmpTrailerPi` class.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Gets or sets a value indicating whether this instance is writable.

Value: `true` if this instance is writable; otherwise, `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Gets or sets a value indicating whether this instance is writable.

Value: `true` if this instance is writable; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts xmp value to the xml representation.

**Returns:**
java.lang.String - Returns XML representation of XMP.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the `other` parameter; otherwise, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified `System.Object`, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `System.Object` is equal to this instance; otherwise, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
