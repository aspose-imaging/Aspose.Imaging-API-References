---
title: EmfPlusDrawCurve
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawCurve record specifies drawing a cardinal spline NOTE ObjectID 1 byte The index of an EmfPlusPen object section 2.2.1.7  in the EMF Object Table to draw the curve.
type: docs
weight: 19
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

The EmfPlusDrawCurve record specifies drawing a cardinal spline NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawCurve` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getTension()](#getTension--) | Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. |
| [setTension(float value)](#setTension-float-) | Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. |
| [getNumSegments()](#getNumSegments--) | Gets or sets the segments count A 32-bit unsigned integer that specifies the number of line segments making up the spline. |
| [setNumSegments(int value)](#setNumSegments-int-) | Gets or sets the segments count A 32-bit unsigned integer that specifies the number of line segments making up the spline. |
| [getPointData()](#getPointData--) | Gets or sets an array of either 32-bit signed integers or 32-bit floating-point numbers of Count length that defines coordinate values of the endpoints of the lines to be stroked. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Gets or sets an array of either 32-bit signed integers or 32-bit floating-point numbers of Count length that defines coordinate values of the endpoints of the lines to be stroked. |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawCurve` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


Gets or sets the segments count A 32-bit unsigned integer that specifies the number of line segments making up the spline.

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


Gets or sets the segments count A 32-bit unsigned integer that specifies the number of line segments making up the spline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Gets or sets an array of either 32-bit signed integers or 32-bit floating-point numbers of Count length that defines coordinate values of the endpoints of the lines to be stroked.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Gets or sets an array of either 32-bit signed integers or 32-bit floating-point numbers of Count length that defines coordinate values of the endpoints of the lines to be stroked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

