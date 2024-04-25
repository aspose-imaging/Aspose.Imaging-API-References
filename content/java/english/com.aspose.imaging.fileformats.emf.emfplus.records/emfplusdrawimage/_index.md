---
title: EmfPlusDrawImage
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawImage record specifies drawing a scaled image.
type: docs
weight: 22
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

The EmfPlusDrawImage record specifies drawing a scaled image.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawImage` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether the PointData is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether the PointData is compressed. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getImageAttributesId()](#getImageAttributesId--) | Gets or sets the image attributes identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Gets or sets the image attributes identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| [getRectData()](#getRectData--) | Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the image. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the image. |
| [getSrcRect()](#getSrcRect--) | Gets or sets the source rect An EmfPlusRectF object that specifies a portion of the image to be rendered. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Gets or sets the source rect An EmfPlusRectF object that specifies a portion of the image to be rendered. |
| [getSrcUnit()](#getSrcUnit--) | Gets or sets the source unit 32-bit signed integer that specifies the units of the SrcRect field. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Gets or sets the source unit 32-bit signed integer that specifies the units of the SrcRect field. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawImage` class.

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


Gets or sets the object identifier. The index of an EmfPlusImage object (section 2.2.1.4) in the EMF+ Object Table, which specifies the image to render. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusImage object (section 2.2.1.4) in the EMF+ Object Table, which specifies the image to render. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Gets or sets the image attributes identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Gets or sets the image attributes identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the image. The portion of the image specified by the SrcRect field is scaled to fit this rectangle.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the image. The portion of the image specified by the SrcRect field is scaled to fit this rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Gets or sets the source rect An EmfPlusRectF object that specifies a portion of the image to be rendered. The portion of the image specified by this rectangle is scaled to fit the destination rectangle specified by the RectData field.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Gets or sets the source rect An EmfPlusRectF object that specifies a portion of the image to be rendered. The portion of the image specified by this rectangle is scaled to fit the destination rectangle specified by the RectData field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Gets or sets the source unit 32-bit signed integer that specifies the units of the SrcRect field. It MUST be the UnitTypePixel member of the UnitType enumeration (section 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Gets or sets the source unit 32-bit signed integer that specifies the units of the SrcRect field. It MUST be the UnitTypePixel member of the UnitType enumeration (section 2.1.1.33).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

