---
title: XmpCollection
second_title: Aspose.Imaging for Java API Reference
description: An XMP element collection.
type: docs
weight: 15
url: /java/com.aspose.imaging.xmp/xmpcollection/
---
**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.types.IXmpType](../../com.aspose.imaging.xmp.types/ixmptype)
```
public class XmpCollection extends ArrayList<IXmpType> implements IXmpType
```

An XMP element collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpCollection()](#XmpCollection--) | Initializes a new instance of the [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection) class. |
## Methods

| Method | Description |
| --- | --- |
| [addItem(Object item)](#addItem-java.lang.Object-) | Adds new item. |
| [addObject(Object item)](#addObject-java.lang.Object-) | Adds an XMP data item. |
| [removeAt(int index)](#removeAt-int-) | Removes the item at the specified index. |
| [add(IXmpType item)](#add-com.aspose.imaging.xmp.types.IXmpType-) | Adds an item to the collection. |
| [copyTo(IXmpType[] array, int arrayIndex)](#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-) | Copies the elements of the collection to an array, starting at a particular array index. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the XMP string value of this. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [toString()](#toString--) | Returns an XML String that represents this instance. |
### XmpCollection() {#XmpCollection--}
```
public XmpCollection()
```


Initializes a new instance of the [XmpCollection](../../com.aspose.imaging.xmp/xmpcollection) class.

### addItem(Object item) {#addItem-java.lang.Object-}
```
public final void addItem(Object item)
```


Adds new item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | java.lang.Object | The item to be added to list of items. |

### addObject(Object item) {#addObject-java.lang.Object-}
```
public final void addObject(Object item)
```


Adds an XMP data item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | java.lang.Object | An XMP item. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the item at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to remove. |

### add(IXmpType item) {#add-com.aspose.imaging.xmp.types.IXmpType-}
```
public final boolean add(IXmpType item)
```


Adds an item to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | The object to add to the collection. |

**Returns:**
boolean
### copyTo(IXmpType[] array, int arrayIndex) {#copyTo-com.aspose.imaging.xmp.types.IXmpType---int-}
```
public final void copyTo(IXmpType[] array, int arrayIndex)
```


Copies the elements of the collection to an array, starting at a particular array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IXmpType\[\]](../../com.aspose.imaging.xmp.types/ixmptype) | The one-dimensional array that is the destination of the elements copied from the collection. The array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Gets the XMP string value of this.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
### getXmlValue() {#getXmlValue--}
```
public final String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
### toString() {#toString--}
```
public String toString()
```


Returns an XML String that represents this instance.

**Returns:**
java.lang.String - An XML String that represents this instance.
