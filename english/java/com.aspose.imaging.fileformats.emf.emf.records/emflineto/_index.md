---
title: EmfLineTo
second_title: Aspose.Imaging for Java API Reference
description: The EMR_LINETO record specifies a line from the current position up to but not including the specified point.It resets the current position to the specified point.
type: docs
weight: 68
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emflineto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfLineTo extends EmfRecord
```

The EMR\_LINETO record specifies a line from the current position up to, but not including, the specified point.It resets the current position to the specified point.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLineTo(EmfRecord record)](#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfLineTo` class. |
| [EmfLineTo()](#EmfLineTo--) | Initializes a new instance of the `EmfLineTo` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPoint()](#getPoint--) | Gets or sets 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates of the line's ending point. |
| [setPoint(Point value)](#setPoint-com.aspose.imaging.Point-) | Gets or sets 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates of the line's ending point. |
### EmfLineTo(EmfRecord record) {#EmfLineTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfLineTo(EmfRecord record)
```


Initializes a new instance of the `EmfLineTo` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfLineTo() {#EmfLineTo--}
```
public EmfLineTo()
```


Initializes a new instance of the `EmfLineTo` class.

### getPoint() {#getPoint--}
```
public Point getPoint()
```


Gets or sets 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates of the line's ending point.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPoint(Point value) {#setPoint-com.aspose.imaging.Point-}
```
public void setPoint(Point value)
```


Gets or sets 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the coordinates of the line's ending point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

