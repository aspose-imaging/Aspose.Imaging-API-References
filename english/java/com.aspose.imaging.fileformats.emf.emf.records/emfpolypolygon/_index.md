---
title: EmfPolyPolygon
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYPOLYGON record specifies a series of closed polygons.
type: docs
weight: 90
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyPolygon extends EmfDrawingRecordType
```

The EMR\_POLYPOLYGON record specifies a series of closed polygons.

Each polygon SHOULD be outlined using the current pen, and filled using the current brush and polygon fill mode that are defined in the playback device context. The polygons defined by this record can overlap.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyPolygon(EmfRecord source)](#EmfPolyPolygon-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyPolygon` class. |
| [EmfPolyPolygon()](#EmfPolyPolygon--) | Initializes a new instance of the `EmfPolyPolygon` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the points for all polygons in logical units. |
| [setAPoints(Point[][] value)](#setAPoints-com.aspose.imaging.Point-----) | Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the points for all polygons in logical units. |
### EmfPolyPolygon(EmfRecord source) {#EmfPolyPolygon-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyPolygon(EmfRecord source)
```


Initializes a new instance of the `EmfPolyPolygon` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyPolygon() {#EmfPolyPolygon--}
```
public EmfPolyPolygon()
```


Initializes a new instance of the `EmfPolyPolygon` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAPoints() {#getAPoints--}
```
public Point[][] getAPoints()
```


Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the points for all polygons in logical units. The number of points is specified by the Count field value.

**Returns:**
com.aspose.imaging.Point[][]
### setAPoints(Point[][] value) {#setAPoints-com.aspose.imaging.Point-----}
```
public void setAPoints(Point[][] value)
```


Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the points for all polygons in logical units. The number of points is specified by the Count field value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

