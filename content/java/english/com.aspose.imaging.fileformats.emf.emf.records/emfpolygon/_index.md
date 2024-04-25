---
title: EmfPolygon
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by straight lines.
type: docs
weight: 96
url: /com.aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolygon extends EmfDrawingRecordType
```

The EMR\_POLYGON record specifies a polygon consisting of two or more vertexes connected by straight lines.

The polygon SHOULD be outlined using the current pen and filled using the current brush and polygon fill mode. The polygon SHOULD be closed automatically by drawing a line from the last vertex to the first
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolygon(EmfRecord source)](#EmfPolygon-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolygon` class. |
| [EmfPolygon()](#EmfPolygon--) | Initializes a new instance of the `EmfPolygon` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the vertexes of the polygon in logical units. |
| [setAPoints(Point[] value)](#setAPoints-com.aspose.imaging.Point---) | Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the vertexes of the polygon in logical units. |
### EmfPolygon(EmfRecord source) {#EmfPolygon-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolygon(EmfRecord source)
```


Initializes a new instance of the `EmfPolygon` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolygon() {#EmfPolygon--}
```
public EmfPolygon()
```


Initializes a new instance of the `EmfPolygon` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAPoints() {#getAPoints--}
```
public Point[] getAPoints()
```


Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the vertexes of the polygon in logical units.

**Returns:**
com.aspose.imaging.Point[]
### setAPoints(Point[] value) {#setAPoints-com.aspose.imaging.Point---}
```
public void setAPoints(Point[] value)
```


Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the vertexes of the polygon in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

