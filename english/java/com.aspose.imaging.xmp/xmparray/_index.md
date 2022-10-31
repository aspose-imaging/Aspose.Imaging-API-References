---
title: XmpArray
second_title: Aspose.Imaging for Java API Reference
description: Represents Xmp Array in KKKCODEB XmpPackageKKKCODEE. todo Array may contain complex data.
type: docs
weight: 12
url: /java/com.aspose.imaging.xmp/xmparray/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Represents Xmp Array in `XmpPackage`. todo: Array may contain complex data.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Initializes a new instance of the `XmpArray` class. |
| [XmpArray(int type)](#XmpArray-int-) | Initializes a new instance of the `XmpArray` class. |
## Methods

| Method | Description |
| --- | --- |
| [addItem(String item)](#addItem-java.lang.String-) | Adds new item. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [toString()](#toString--) | Returns a `System.String` that represents this instance. |
| [getValues()](#getValues--) | Gets array of values inside `XmpArray`. |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Initializes a new instance of the `XmpArray` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of array. |
| items | java.lang.String[] | The items list. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Initializes a new instance of the `XmpArray` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of array. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Adds new item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | java.lang.String | The item to be added to list of items. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
### toString() {#toString--}
```
public String toString()
```


Returns a `System.String` that represents this instance.

**Returns:**
java.lang.String - A `System.String` that represents this instance.
### getValues() {#getValues--}
```
public String[] getValues()
```


Gets array of values inside `XmpArray`.

**Returns:**
java.lang.String[]
