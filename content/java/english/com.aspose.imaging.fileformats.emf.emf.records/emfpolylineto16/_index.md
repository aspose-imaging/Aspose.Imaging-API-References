---
title: EmfPolylineTo16
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position.
type: docs
weight: 101
url: /com.aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolylineTo16 extends EmfDrawingRecordType
```

The EMR\_POLYLINETO16 record specifies one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the aPoints field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by aPoints.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolylineTo16(EmfRecord source)](#EmfPolylineTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolylineTo16` class. |
| [EmfPolylineTo16()](#EmfPolylineTo16--) | Initializes a new instance of the `EmfPolylineTo16` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [setAPoints(Point[] value)](#setAPoints-com.aspose.imaging.Point---) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
### EmfPolylineTo16(EmfRecord source) {#EmfPolylineTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolylineTo16(EmfRecord source)
```


Initializes a new instance of the `EmfPolylineTo16` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolylineTo16() {#EmfPolylineTo16--}
```
public EmfPolylineTo16()
```


Initializes a new instance of the `EmfPolylineTo16` class.

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

