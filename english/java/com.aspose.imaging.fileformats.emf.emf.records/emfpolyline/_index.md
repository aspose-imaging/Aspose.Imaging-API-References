---
title: EmfPolyline
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYLINE record specifies a series of line segments by connecting the points in the specified array.
type: docs
weight: 98
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolyline/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyline extends EmfDrawingRecordType
```

The EMR\_POLYLINE record specifies a series of line segments by connecting the points in the specified array.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyline(EmfRecord source)](#EmfPolyline-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyline` class. |
| [EmfPolyline()](#EmfPolyline--) | Initializes a new instance of the `EmfPolyline` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the point data, in logical units. |
| [setAPoints(Point[] value)](#setAPoints-com.aspose.imaging.Point---) | Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the point data, in logical units. |
### EmfPolyline(EmfRecord source) {#EmfPolyline-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyline(EmfRecord source)
```


Initializes a new instance of the `EmfPolyline` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyline() {#EmfPolyline--}
```
public EmfPolyline()
```


Initializes a new instance of the `EmfPolyline` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAPoints() {#getAPoints--}
```
public Point[] getAPoints()
```


Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the point data, in logical units.

**Returns:**
com.aspose.imaging.Point[]
### setAPoints(Point[] value) {#setAPoints-com.aspose.imaging.Point---}
```
public void setAPoints(Point[] value)
```


Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the point data, in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

