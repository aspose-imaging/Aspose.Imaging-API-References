---
title: EmfPlusEndContainer
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.
type: docs
weight: 30
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusEndContainer` class. |
## Methods

| Method | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Gets or sets a 32-bit unsigned integer that specifies the index of a graphics state container. |
| [setStackIndex(int value)](#setStackIndex-int-) | Gets or sets a 32-bit unsigned integer that specifies the index of a graphics state container. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusEndContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Gets or sets a 32-bit unsigned integer that specifies the index of a graphics state container. The index MUST must match the value associated with a graphics state container opened by a previous EmfPlusBeginContainer (section 2.3.7.1) or EmfPlusBeginContainerNoParams record (section 2.3.7.2).

Value: The index of the stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the index of a graphics state container. The index MUST must match the value associated with a graphics state container opened by a previous EmfPlusBeginContainer (section 2.3.7.1) or EmfPlusBeginContainerNoParams record (section 2.3.7.2).

Value: The index of the stack.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

