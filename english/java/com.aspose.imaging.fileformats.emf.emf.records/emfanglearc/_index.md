---
title: EmfAngleArc
second_title: Aspose.Imaging for Java API Reference
description: The EMR_ANGLEARC record specifies a line segment of an arc.
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

The EMR\_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the given radius and center. The length of the arc is defined by the given start and sweep angles
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfAngleArc` class. |
| [EmfAngleArc()](#EmfAngleArc--) | Initializes a new instance of the `EmfAngleArc` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCenter()](#getCenter--) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the circle's center. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the circle's center. |
| [getRadius()](#getRadius--) | Gets or sets a 32-bit unsigned integer that specifies the circle's radius, in logical units. |
| [setRadius(int value)](#setRadius-int-) | Gets or sets a 32-bit unsigned integer that specifies the circle's radius, in logical units. |
| [getStartAngle()](#getStartAngle--) | Gets or sets a 32-bit float that specifies the arc's start angle, in degrees. |
| [setStartAngle(float value)](#setStartAngle-float-) | Gets or sets a 32-bit float that specifies the arc's start angle, in degrees. |
| [getSweepAngle()](#getSweepAngle--) | Gets or sets a 32-bit float that specifies the arc's sweep angle, in degrees. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Gets or sets a 32-bit float that specifies the arc's sweep angle, in degrees. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Initializes a new instance of the `EmfAngleArc` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Initializes a new instance of the `EmfAngleArc` class.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the circle's center.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the circle's center.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Gets or sets a 32-bit unsigned integer that specifies the circle's radius, in logical units.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the circle's radius, in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Gets or sets a 32-bit float that specifies the arc's start angle, in degrees.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Gets or sets a 32-bit float that specifies the arc's start angle, in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Gets or sets a 32-bit float that specifies the arc's sweep angle, in degrees.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Gets or sets a 32-bit float that specifies the arc's sweep angle, in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

