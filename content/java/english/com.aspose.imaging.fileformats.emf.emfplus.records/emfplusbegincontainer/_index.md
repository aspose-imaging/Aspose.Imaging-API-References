---
title: EmfPlusBeginContainer
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusBeginContainer` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Gets the page unit. |
| [getDestRect()](#getDestRect--) | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that, with SrcRect, specifies a transform for the container. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that, with SrcRect, specifies a transform for the container. |
| [getSrcRect()](#getSrcRect--) | Gets or sets an EmfPlusRectF rectangle that, with DestRect, specifies a transformation for the container. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Gets or sets an EmfPlusRectF rectangle that, with DestRect, specifies a transformation for the container. |
| [getStackIndex()](#getStackIndex--) | Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. |
| [setStackIndex(int value)](#setStackIndex-int-) | Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusBeginContainer` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Gets the page unit.

Value: The page unit.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


Gets or sets an EmfPlusRectF object (section 2.2.2.39) that, with SrcRect, specifies a transform for the container. This transformation results in SrcRect when applied to DestRect.

Value: The dest rect.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


Gets or sets an EmfPlusRectF object (section 2.2.2.39) that, with SrcRect, specifies a transform for the container. This transformation results in SrcRect when applied to DestRect.

Value: The dest rect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Gets or sets an EmfPlusRectF rectangle that, with DestRect, specifies a transformation for the container. This transformation results in SrcRect when applied to DestRect.

Value: The source rect.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Gets or sets an EmfPlusRectF rectangle that, with DestRect, specifies a transformation for the container. This transformation results in SrcRect when applied to DestRect.

Value: The source rect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

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

