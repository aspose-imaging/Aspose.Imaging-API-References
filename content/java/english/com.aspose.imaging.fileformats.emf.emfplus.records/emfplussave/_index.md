---
title: EmfPlusSave
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSave record saves the graphics state identified by a specified index on a stack of saved graphics states.
type: docs
weight: 51
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

The EmfPlusSave record saves the graphics state, identified by a specified index, on a stack of saved graphics states.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSave` class. |
## Methods

| Method | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Gets or sets a 32-bit unsigned integer that specifies a level to associate with the graphics state. |
| [setStackIndex(int value)](#setStackIndex-int-) | Gets or sets a 32-bit unsigned integer that specifies a level to associate with the graphics state. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSave` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Gets or sets a 32-bit unsigned integer that specifies a level to associate with the graphics state. The level value can be used by a subsequent EmfPlusRestore record (section 2.3.7.4) operation to retrieve the graphics state.

Value: The index of the stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Gets or sets a 32-bit unsigned integer that specifies a level to associate with the graphics state. The level value can be used by a subsequent EmfPlusRestore record (section 2.3.7.4) operation to retrieve the graphics state.

Value: The index of the stack.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

