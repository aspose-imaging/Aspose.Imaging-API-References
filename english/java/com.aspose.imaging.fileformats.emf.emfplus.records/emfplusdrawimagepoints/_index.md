---
title: EmfPlusDrawImagePoints
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.
type: docs
weight: 23
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

An EmfPlusImage can specify either a bitmap or metafile. Colors in an image can be manipulated during rendering. They can be corrected, darkened, lightened, and removed.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawImagePoints` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether the PointData is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether the PointData is compressed. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Gets or sets a value indicating whether [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Gets or sets a value indicating whether [applying an effect]. |
| [getRelative()](#getRelative--) | Gets or sets a value indicating whether this `EmfPlusDrawImagePoints` is relative. |
| [setRelative(boolean value)](#setRelative-boolean-) | Gets or sets a value indicating whether this `EmfPlusDrawImagePoints` is relative. |
| [getImageAttributesId()](#getImageAttributesId--) | Gets or sets a 32-bit unsigned integer that contains the index of the optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Gets or sets a 32-bit unsigned integer that contains the index of the optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| [getSrcUnit()](#getSrcUnit--) | Gets or sets a 32-bit signed integer that defines the units of the SrcRect field. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Gets or sets a 32-bit signed integer that defines the units of the SrcRect field. |
| [getSrcRect()](#getSrcRect--) | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines a portion of the image to be rendered. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines a portion of the image to be rendered. |
| [getPointData()](#getPointData--) | Gets or sets an array of Count points that specify three points of a parallelogram. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Gets or sets an array of Count points that specify three points of a parallelogram. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawImagePoints` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets or sets a value indicating whether the PointData is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the P flag (below) is set, this flag is undefined and MUST be ignored.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether the PointData is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the P flag (below) is set, this flag is undefined and MUST be ignored.

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

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Gets or sets a value indicating whether [applying an effect]. This bit indicates that the rendering of the image includes applying an effect. If set, an object of the Effect class MUST have been specified in an earlier EmfPlusSerializableObject record (section 2.3.5.2).

Value: `true` if [applying an effect]; otherwise, `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Gets or sets a value indicating whether [applying an effect]. This bit indicates that the rendering of the image includes applying an effect. If set, an object of the Effect class MUST have been specified in an earlier EmfPlusSerializableObject record (section 2.3.5.2).

Value: `true` if [applying an effect]; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Gets or sets a value indicating whether this `EmfPlusDrawImagePoints` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored.

Value: `true` if relative; otherwise, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusDrawImagePoints` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored.

Value: `true` if relative; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Gets or sets a 32-bit unsigned integer that contains the index of the optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table.

Value: The image attributes identifier.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Gets or sets a 32-bit unsigned integer that contains the index of the optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table.

Value: The image attributes identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Gets or sets a 32-bit signed integer that defines the units of the SrcRect field. It MUST be the UnitPixel value of the UnitType enumeration (section 2.1.1.33).

Value: The source unit.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Gets or sets a 32-bit signed integer that defines the units of the SrcRect field. It MUST be the UnitPixel value of the UnitType enumeration (section 2.1.1.33).

Value: The source unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines a portion of the image to be rendered.

Value: The source rect.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines a portion of the image to be rendered.

Value: The source rect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Gets or sets an array of Count points that specify three points of a parallelogram. The three points represent the upper-left, upper-right, and lower-left corners of the parallelogram. The fourth point of the parallelogram is extrapolated from the first three. The portion of the image specified by the SrcRect field SHOULD have scaling and shearing transforms applied if necessary to fit inside the parallelogram.

Value: The point data.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Gets or sets an array of Count points that specify three points of a parallelogram. The three points represent the upper-left, upper-right, and lower-left corners of the parallelogram. The fourth point of the parallelogram is extrapolated from the first three. The portion of the image specified by the SrcRect field SHOULD have scaling and shearing transforms applied if necessary to fit inside the parallelogram.

Value: The point data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

