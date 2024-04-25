---
title: EmfPlusDrawRects
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawRects record specifies drawing a series of rectangles
type: docs
weight: 27
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawRects extends EmfPlusDrawingRecordType
```

The EmfPlusDrawRects record specifies drawing a series of rectangles
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawRects(EmfPlusRecord source)](#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawRects` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether the PointData is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether the PointData is compressed. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getRectData()](#getRectData--) | Gets or sets the rect data An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Gets or sets the rect data An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data. |
### EmfPlusDrawRects(EmfPlusRecord source) {#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawRects(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawRects` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

Value: `true` if compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the rectangles. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the rectangles. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Gets or sets the rect data An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Gets or sets the rect data An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

