---
title: EmfDeleteObject
second_title: Aspose.Imaging for Java API Reference
description: The EMR_DELETEOBJECT record deletes a graphics object which is specified by its index in the EMF Object Tablesection 3.1.1.1.
type: docs
weight: 43
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfDeleteObject extends EmfRecord
```

The EMR\_DELETEOBJECT record deletes a graphics object, which is specified by its index in the EMF Object Table(section 3.1.1.1).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfDeleteObject(EmfRecord record)](#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfDeleteObject` class. |
| [EmfDeleteObject()](#EmfDeleteObject--) | Initializes a new instance of the `EmfDeleteObject` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the StockObject enumeration. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the StockObject enumeration. |
### EmfDeleteObject(EmfRecord record) {#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteObject(EmfRecord record)
```


Initializes a new instance of the `EmfDeleteObject` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfDeleteObject() {#EmfDeleteObject--}
```
public EmfDeleteObject()
```


Initializes a new instance of the `EmfDeleteObject` class.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the StockObject enumeration.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the StockObject enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

