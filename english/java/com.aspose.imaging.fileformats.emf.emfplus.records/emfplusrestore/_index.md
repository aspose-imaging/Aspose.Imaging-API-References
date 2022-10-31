---
title: EmfPlusRestore
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusRestore record restores the graphics state identified by a specified index from a stack of saved graphics states.
type: docs
weight: 49
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusRestore` class. |
## Methods

| Method | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Gets or sets a 32-bit unsigned integer that specifies the level associated with a graphics state. |
| [setStackIndex(int value)](#setStackIndex-int-) | Gets or sets a 32-bit unsigned integer that specifies the level associated with a graphics state. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusRestore` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Gets or sets a 32-bit unsigned integer that specifies the level associated with a graphics state. The level value was assigned to the graphics state by a previous EmfPlusSave record (section 2.3.7.5).

Value: The index of the stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the level associated with a graphics state. The level value was assigned to the graphics state by a previous EmfPlusSave record (section 2.3.7.5).

Value: The index of the stack.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

