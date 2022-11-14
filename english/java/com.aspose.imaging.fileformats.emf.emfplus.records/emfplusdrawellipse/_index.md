---
title: EmfPlusDrawEllipse
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawEllipse record specifies drawing an ellipse.
type: docs
weight: 21
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawEllipse extends EmfPlusDrawingRecordType
```

The EmfPlusDrawEllipse record specifies drawing an ellipse.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawEllipse(EmfPlusRecord source)](#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawEllipse` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether the PointData is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether the PointData is compressed. |
| [getRectData()](#getRectData--) | Gets or sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Gets or sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse. |
### EmfPlusDrawEllipse(EmfPlusRecord source) {#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawEllipse(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawEllipse` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusPen (section 2.2.1.7) object in the EMF+ Object Table to draw the ellipse. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusPen (section 2.2.1.7) object in the EMF+ Object Table to draw the ellipse. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Gets or sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Gets or sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

