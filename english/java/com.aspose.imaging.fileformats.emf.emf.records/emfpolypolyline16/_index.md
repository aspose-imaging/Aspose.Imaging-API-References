---
title: EmfPolyPolyline16
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYPOLYLINE16 record specifies multiple series of connected line segments.
type: docs
weight: 93
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyPolyline16 extends EmfDrawingRecordType
```

The EMR\_POLYPOLYLINE16 record specifies multiple series of connected line segments.

The line segments SHOULD be drawn using the current pen. The figures formed by the segments SHOULD NOT filled. The current position SHOULD neither be used nor updated by this record.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyPolyline16(EmfRecord source)](#EmfPolyPolyline16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyPolyline16` class. |
| [EmfPolyPolyline16()](#EmfPolyPolyline16--) | Initializes a new instance of the `EmfPolyPolyline16` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [setAPoints(Point[][] value)](#setAPoints-com.aspose.imaging.Point-----) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
### EmfPolyPolyline16(EmfRecord source) {#EmfPolyPolyline16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyPolyline16(EmfRecord source)
```


Initializes a new instance of the `EmfPolyPolyline16` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyPolyline16() {#EmfPolyPolyline16--}
```
public EmfPolyPolyline16()
```


Initializes a new instance of the `EmfPolyPolyline16` class.

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

