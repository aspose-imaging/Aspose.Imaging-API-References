---
title: EmfPie
second_title: Aspose.Imaging for Java API Reference
description: The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two radials.
type: docs
weight: 82
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

The EMR\_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two radials. The pie is outlined by using the current pen and filled by using the current brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPie` class. |
| [EmfPie()](#EmfPie--) | Initializes a new instance of the `EmfPie` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBox()](#getBox--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [getStart()](#getStart--) | Gets or sets a 64-bit WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the endpoint of the first radial. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the endpoint of the first radial. |
| [getEnd()](#getEnd--) | Gets or sets a 64-bit PointL object that specifies the coordinates, in logical units, of the endpoint of the second radial. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | Gets or sets a 64-bit PointL object that specifies the coordinates, in logical units, of the endpoint of the second radial. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


Initializes a new instance of the `EmfPie` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


Initializes a new instance of the `EmfPie` class.

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


Gets or sets a 64-bit WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the endpoint of the first radial.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


Gets or sets a 64-bit WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates, in logical units, of the endpoint of the first radial.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


Gets or sets a 64-bit PointL object that specifies the coordinates, in logical units, of the endpoint of the second radial.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


Gets or sets a 64-bit PointL object that specifies the coordinates, in logical units, of the endpoint of the second radial.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

