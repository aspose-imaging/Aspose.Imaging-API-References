---
title: EmfPolyPolyline
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYPOLYLINE record specifies multiple series of connected line segments.
type: docs
weight: 92
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyPolyline extends EmfDrawingRecordType
```

The EMR\_POLYPOLYLINE record specifies multiple series of connected line segments.

The line segments SHOULD be drawn using the current pen. The figures formed by the segments SHOULD NOT filled. The current position SHOULD neither be used nor updated by this record.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyPolyline(EmfRecord source)](#EmfPolyPolyline-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyPolyline` class. |
| [EmfPolyPolyline()](#EmfPolyPolyline--) | Initializes a new instance of the `EmfPolyPolyline` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count-length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specify the point data, in logical units. |
| [setAPoints(Point[][] value)](#setAPoints-com.aspose.imaging.Point-----) | Gets or sets a Count-length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specify the point data, in logical units. |
### EmfPolyPolyline(EmfRecord source) {#EmfPolyPolyline-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyPolyline(EmfRecord source)
```


Initializes a new instance of the `EmfPolyPolyline` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyPolyline() {#EmfPolyPolyline--}
```
public EmfPolyPolyline()
```


Initializes a new instance of the `EmfPolyPolyline` class.

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
public Point[][] getAPoints()
```


Gets or sets a Count-length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specify the point data, in logical units.

**Returns:**
com.aspose.imaging.Point[][]
### setAPoints(Point[][] value) {#setAPoints-com.aspose.imaging.Point-----}
```
public void setAPoints(Point[][] value)
```


Gets or sets a Count-length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specify the point data, in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

