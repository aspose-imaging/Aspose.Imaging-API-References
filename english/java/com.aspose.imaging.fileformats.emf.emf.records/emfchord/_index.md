---
title: EmfChord
second_title: Aspose.Imaging for Java API Reference
description: The EMR_CHORD record specifies a chord which is a region bounded by the intersection of an ellipse and a line segment called a secant.
type: docs
weight: 20
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

The EMR\_CHORD record specifies a chord, which is a region bounded by the intersection of an ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled by using the current brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfChord` class. |
| [EmfChord()](#EmfChord--) | Initializes a new instance of the `EmfChord` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBox()](#getBox--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [getStart()](#getStart--) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the endpoint of the radial defining the beginning of the chord. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the endpoint of the radial defining the beginning of the chord. |
| [getEnd()](#getEnd--) | Gets or sets a 64-bit WMF PointL object that specifies the logical coordinates of the endpoint of the radial defining the end of the chord. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object that specifies the logical coordinates of the endpoint of the radial defining the end of the chord. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


Initializes a new instance of the `EmfChord` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


Initializes a new instance of the `EmfChord` class.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the endpoint of the radial defining the beginning of the chord.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the endpoint of the radial defining the beginning of the chord.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Gets or sets a 64-bit WMF PointL object that specifies the logical coordinates of the endpoint of the radial defining the end of the chord.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Gets or sets a 64-bit WMF PointL object that specifies the logical coordinates of the endpoint of the radial defining the end of the chord.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

