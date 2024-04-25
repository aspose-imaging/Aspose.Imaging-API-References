---
title: EmfPolyPolygon16
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYPOLYGON16 record specifies a series of closed polygons.
type: docs
weight: 91
url: /com.aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyPolygon16 extends EmfDrawingRecordType
```

The EMR\_POLYPOLYGON16 record specifies a series of closed polygons. Each polygon is outlined using the current pen, and filled using the current brush and polygon fill mode. The polygons drawn by this record can overlap.

Each polygon SHOULD be outlined using the current pen, and filled using the current brush and polygon fill mode that are defined in the playback device context. The polygons defined by this record can overlap.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyPolygon16(EmfRecord source)](#EmfPolyPolygon16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyPolygon16` class. |
| [EmfPolyPolygon16()](#EmfPolyPolygon16--) | Initializes a new instance of the `EmfPolyPolygon16` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [setAPoints(Point[][] value)](#setAPoints-com.aspose.imaging.Point-----) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
### EmfPolyPolygon16(EmfRecord source) {#EmfPolyPolygon16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyPolygon16(EmfRecord source)
```


Initializes a new instance of the `EmfPolyPolygon16` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyPolygon16() {#EmfPolyPolygon16--}
```
public EmfPolyPolygon16()
```


Initializes a new instance of the `EmfPolyPolygon16` class.

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
public Point[][] getAPoints()
```


Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points.

**Returns:**
com.aspose.imaging.Point[][]
### setAPoints(Point[][] value) {#setAPoints-com.aspose.imaging.Point-----}
```
public void setAPoints(Point[][] value)
```


Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

