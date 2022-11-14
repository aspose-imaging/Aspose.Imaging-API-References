---
title: EmfPlusFillClosedCurve
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline
type: docs
weight: 32
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusFillClosedCurve` class. |
## Methods

| Method | Description |
| --- | --- |
| [isColor()](#isColor--) | Gets or sets a value indicating whether this instance is color. |
| [setColor(boolean value)](#setColor-boolean-) | Gets or sets a value indicating whether this instance is color. |
| [getCompressed()](#getCompressed--) | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is compressed. |
| [getWinding()](#getWinding--) | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is winding. |
| [setWinding(boolean value)](#setWinding-boolean-) | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is winding. |
| [getRelative()](#getRelative--) | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is relative. |
| [setRelative(boolean value)](#setRelative-boolean-) | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is relative. |
| [getBrushId()](#getBrushId--) | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the EmfPlusBrush, the content of which is determined by the S bit in the Flags field. |
| [setBrushId(int value)](#setBrushId-int-) | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the EmfPlusBrush, the content of which is determined by the S bit in the Flags field. |
| [getTension()](#getTension--) | Gets or sets the tension A 32-bit floating point value that specifies how tightly the spline bends as it passes through the points. |
| [setTension(float value)](#setTension-float-) | Gets or sets the tension A 32-bit floating point value that specifies how tightly the spline bends as it passes through the points. |
| [getPointData()](#getPointData--) | Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusFillClosedCurve` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.

Value: `true` if this instance is color; otherwise, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.

Value: `true` if this instance is color; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. ---------------------- A "winding" fill operation fills areas according to the "even-odd parity" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from the test point to a point that is distant from the curve. If that line crosses the curve an odd number of times, the test point is inside the curve; otherwise, the test point is outside the curve. --------------------- An "alternate" fill operation fills areas according to the "non-zero" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from a test point to a point that is distant from the curve. Count the number of times the curve crosses the test line from left to right, and count the number of times the curve crosses the test line from right to left. If those two numbers are the same, the test point is outside the curve; otherwise, the test point is inside the curve.

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. ---------------------- A "winding" fill operation fills areas according to the "even-odd parity" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from the test point to a point that is distant from the curve. If that line crosses the curve an odd number of times, the test point is inside the curve; otherwise, the test point is outside the curve. --------------------- An "alternate" fill operation fills areas according to the "non-zero" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from a test point to a point that is distant from the curve. Count the number of times the curve crosses the test line from left to right, and count the number of times the curve crosses the test line from right to left. If those two numbers are the same, the test point is outside the curve; otherwise, the test point is inside the curve.

Value: `true` if compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is winding. This bit indicates how to perform the fill operation. If set, the fill is a "winding" fill. If clear, the fill is an "alternate" fill.

Value: `true` if winding; otherwise, `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is winding. This bit indicates how to perform the fill operation. If set, the fill is a "winding" fill. If clear, the fill is an "alternate" fill.

Value: `true` if winding; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored.

Value: `true` if relative; otherwise, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored.

Value: `true` if relative; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Gets or sets the brush identifier A 32-bit unsigned integer that specifies the EmfPlusBrush, the content of which is determined by the S bit in the Flags field. This brush is used to fill the interior of the closed cardinal spline.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Gets or sets the brush identifier A 32-bit unsigned integer that specifies the EmfPlusBrush, the content of which is determined by the S bit in the Flags field. This brush is used to fill the interior of the closed cardinal spline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


Gets or sets the tension A 32-bit floating point value that specifies how tightly the spline bends as it passes through the points. A value of 0.0 specifies that the spline is a sequence of straight lines. As the value increases, the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Gets or sets the tension A 32-bit floating point value that specifies how tightly the spline bends as it passes through the points. A value of 0.0 specifies that the spline is a sequence of straight lines. As the value increases, the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, the curve continues through the last point in the PointData array and connects with the first point in the array

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, the curve continues through the last point in the PointData array and connects with the first point in the array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

