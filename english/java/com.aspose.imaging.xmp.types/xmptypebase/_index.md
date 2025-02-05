---
title: XmpTypeBase
second_title: Aspose.Imaging for Java API Reference
description: Represents base class for basic XMP type.
type: docs
weight: 10
url: /java/com.aspose.imaging.xmp.types/xmptypebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype), com.aspose.ms.System.ICloneable, java.lang.Cloneable
```
public abstract class XmpTypeBase implements IXmpType, System.ICloneable, Cloneable
```

Represents base class for basic XMP type.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpTypeBase()](#XmpTypeBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
| [toString()](#toString--) | Gets this XMP data as string. |
| [deepClone()](#deepClone--) | Clones this instance. |
### XmpTypeBase() {#XmpTypeBase--}
```
public XmpTypeBase()
```


### getXmpRepresentation() {#getXmpRepresentation--}
```
public abstract String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string containing xmp representation.
### toString() {#toString--}
```
public String toString()
```


Gets this XMP data as string.

**Returns:**
java.lang.String - XMP data as string.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones this instance.

**Returns:**
java.lang.Object - A memberwise clone.
