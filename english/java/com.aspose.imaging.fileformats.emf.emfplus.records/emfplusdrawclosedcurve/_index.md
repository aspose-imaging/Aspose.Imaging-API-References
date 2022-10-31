---
title: EmfPlusDrawClosedCurve
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline
type: docs
weight: 18
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawClosedCurve` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. |
| [getRelative()](#getRelative--) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. |
| [setRelative(boolean value)](#setRelative-boolean-) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. |
| [getTension()](#getTension--) | Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. |
| [setTension(float value)](#setTension-float-) | Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. |
| [getPointData()](#getPointData--) | Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawClosedCurve` class. RecordType - A 16-bit unsigned integer that identifies this record type as EmfPlusDrawClosedCurve from the RecordType enumeration (section 2.1.1.1). The value MUST be 0x4017.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the closed curve. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the closed curve. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored

Value: `true` if compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored

Value: `true` if relative; otherwise, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored

Value: `true` if relative; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTension() {#getTension--}
```
public float getTension()
```


Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. A value of 0 specifies that the spline is a sequence of straight lines. As the value increases, the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. A value of 0 specifies that the spline is a sequence of straight lines. As the value increases, the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, the curve continues through the last point in the PointData array and connects with the first point in the array. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are set in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, the curve continues through the last point in the PointData array and connects with the first point in the array. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are set in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

