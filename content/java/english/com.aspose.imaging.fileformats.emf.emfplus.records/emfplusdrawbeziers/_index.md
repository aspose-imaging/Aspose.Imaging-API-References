---
title: EmfPlusDrawBeziers
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves.
type: docs
weight: 17
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. The order for Bezier data points is the start point, control point 1, control point 2 and end point. For more information see [MSDN-DrawBeziers].
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawBeziers` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether the PointData is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether the PointData is compressed. |
| [getRelative()](#getRelative--) | Gets or sets a value indicating whether the PointData is relative. |
| [setRelative(boolean value)](#setRelative-boolean-) | Gets or sets a value indicating whether the PointData is relative. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getPointData()](#getPointData--) | Gets or sets the point data An array of Count points that specify the starting, ending, and control points of the Bezier curves. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Gets or sets the point data An array of Count points that specify the starting, ending, and control points of the Bezier curves. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawBeziers` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets or sets a value indicating whether the PointData is compressed. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored.

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether the PointData is compressed. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored.

Value: `true` if compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Gets or sets a value indicating whether the PointData is relative. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored.

Value: `true` if relative; otherwise, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Gets or sets a value indicating whether the PointData is relative. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored.

Value: `true` if relative; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the Bezier curves. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the Bezier curves. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Gets or sets the point data An array of Count points that specify the starting, ending, and control points of the Bezier curves. The ending coordinate of one Bezier curve is the starting coordinate of the next. The control points are used for producing the Bezier effect. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are clear in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations. A Bezier curve does not pass through its control points. The control points act as

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Gets or sets the point data An array of Count points that specify the starting, ending, and control points of the Bezier curves. The ending coordinate of one Bezier curve is the starting coordinate of the next. The control points are used for producing the Bezier effect. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are clear in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations. A Bezier curve does not pass through its control points. The control points act as

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

