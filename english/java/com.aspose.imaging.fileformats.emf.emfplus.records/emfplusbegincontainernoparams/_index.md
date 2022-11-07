---
title: EmfPlusBeginContainerNoParams
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusBeginContainerNoParams record opens a new graphics state container.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

The EmfPlusBeginContainerNoParams record opens a new graphics state container.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusBeginContainerNoParams` class. |
## Methods

| Method | Description |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. |
| [setStackIndex(int value)](#setStackIndex-int-) | Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusBeginContainerNoParams` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. The index MUST be referenced by a subsequent EmfPlusEndContainer record (section 2.3.7.3) to close the graphics state container.

Value: The index of the stack.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. The index MUST be referenced by a subsequent EmfPlusEndContainer record (section 2.3.7.3) to close the graphics state container.

Value: The index of the stack.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

