---
title: EmfSelectObject
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device context.
type: docs
weight: 113
url: /com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

The EMR\_SELECTOBJECT record adds a graphics object to the current metafile playback device context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its value from the StockObject enumeration(section 2.1.31).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSelectObject` class. |
| [EmfSelectObject()](#EmfSelectObject--) | Initializes a new instance of the `EmfSelectObject` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the `Consts.EmfStockObject` enumeration. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the `Consts.EmfStockObject` enumeration. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Initializes a new instance of the `EmfSelectObject` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Initializes a new instance of the `EmfSelectObject` class.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the `Consts.EmfStockObject` enumeration.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object in the EMF Object Table or the index of a stock object from the `Consts.EmfStockObject` enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

