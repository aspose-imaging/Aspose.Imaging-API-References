---
title: XmpMeta
second_title: Aspose.Imaging for Java API Reference
description: Represents xmp meta.
type: docs
weight: 17
url: /com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Represents xmp meta. Optional. The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initializes a new instance of the `XmpMeta` class. |
| [XmpMeta()](#XmpMeta--) | Initializes a new instance of the `XmpMeta` class. |
## Methods

| Method | Description |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Gets or set Adobe Xmp toolkit version. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Gets or set Adobe Xmp toolkit version. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Adds the attribute. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified `System.Object`, is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initializes a new instance of the `XmpMeta` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP toolkit version. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initializes a new instance of the `XmpMeta` class.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Gets or set Adobe Xmp toolkit version.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Gets or set Adobe Xmp toolkit version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Adds the attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | The attribute. |
| value | java.lang.String | The value. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the `other` parameter; otherwise, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determines whether the specified `System.Object`, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | The `System.Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `System.Object` is equal to this instance; otherwise, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
