---
title: EmfArc
second_title: Aspose.Imaging for Java API Reference
description: The EMR_ARC record specifies an elliptical arc.
type: docs
weight: 13
url: /com.aspose.imaging.fileformats.emf.emf.records/emfarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArc extends EmfDrawingRecordType
```

The EMR\_ARC record specifies an elliptical arc.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfArc(EmfRecord source)](#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfArc` class. |
| [EmfArc()](#EmfArc--) | Initializes a new instance of the `EmfArc` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBox()](#getBox--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [getStart()](#getStart--) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the ending point of the radial line defining the starting point of the arc. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the ending point of the radial line defining the starting point of the arc. |
| [getEnd()](#getEnd--) | Gets or sets a 64-bit WMF PointL object that specifies the coordinates, in logical units, of the ending point of the radial line defining the ending point of the arc. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object that specifies the coordinates, in logical units, of the ending point of the radial line defining the ending point of the arc. |
### EmfArc(EmfRecord source) {#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArc(EmfRecord source)
```


Initializes a new instance of the `EmfArc` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfArc() {#EmfArc--}
```
public EmfArc()
```


Initializes a new instance of the `EmfArc` class.

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


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the ending point of the radial line defining the starting point of the arc.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the ending point of the radial line defining the starting point of the arc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Gets or sets a 64-bit WMF PointL object that specifies the coordinates, in logical units, of the ending point of the radial line defining the ending point of the arc.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Gets or sets a 64-bit WMF PointL object that specifies the coordinates, in logical units, of the ending point of the radial line defining the ending point of the arc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

