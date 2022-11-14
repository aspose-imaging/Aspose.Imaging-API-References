---
title: EmfPolygon16
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYGON16 record specifies a polygon consisting of two or more vertexes connected by straight lines.
type: docs
weight: 97
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolygon16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolygon16 extends EmfDrawingRecordType
```

The EMR\_POLYGON16 record specifies a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

The polygon SHOULD be outlined using the current pen and filled using the current brush and polygon fill mode. The polygon SHOULD be closed automatically by drawing a line from the last vertex to the first
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolygon16(EmfRecord source)](#EmfPolygon16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolygon16` class. |
| [EmfPolygon16()](#EmfPolygon16--) | Initializes a new instance of the `EmfPolygon16` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [setAPoints(Point[] value)](#setAPoints-com.aspose.imaging.Point---) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
### EmfPolygon16(EmfRecord source) {#EmfPolygon16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolygon16(EmfRecord source)
```


Initializes a new instance of the `EmfPolygon16` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolygon16() {#EmfPolygon16--}
```
public EmfPolygon16()
```


Initializes a new instance of the `EmfPolygon16` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAPoints() {#getAPoints--}
```
public Point[] getAPoints()
```


Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points.

**Returns:**
com.aspose.imaging.Point[]
### setAPoints(Point[] value) {#setAPoints-com.aspose.imaging.Point---}
```
public void setAPoints(Point[] value)
```


Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

