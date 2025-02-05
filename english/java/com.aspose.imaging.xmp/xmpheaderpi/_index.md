---
title: XmpHeaderPi
second_title: Aspose.Imaging for Java API Reference
description: Represents XMP header processing instruction.
type: docs
weight: 17
url: /java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Represents XMP header processing instruction.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initializes a new instance of the `XmpHeaderPi` class. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initializes a new instance of the `XmpHeaderPi` class. |
## Methods

| Method | Description |
| --- | --- |
| [getGuid()](#getGuid--) | Represents Header Guid. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Represents Header Guid. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `System.Object`, is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initializes a new instance of the `XmpHeaderPi` class.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initializes a new instance of the `XmpHeaderPi` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| guid | java.lang.String | The unique identifier. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Represents Header Guid.

The text of the header PI contains a GUID, making it unlikely to appear by accident in the data stream.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Represents Header Guid.

The text of the header PI contains a GUID, making it unlikely to appear by accident in the data stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | An object to compare with this object. |

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
