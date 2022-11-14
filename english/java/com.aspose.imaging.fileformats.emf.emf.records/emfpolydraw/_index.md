---
title: EmfPolyDraw
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYDRAW record specifies a set of line segments and Bezier curves.
type: docs
weight: 88
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyDraw extends EmfDrawingRecordType
```

The EMR\_POLYDRAW record specifies a set of line segments and Bezier curves.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyDraw` class. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Initializes a new instance of the [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the array of points, in logical units. |
| [setAPoints(Point[] value)](#setAPoints-com.aspose.imaging.Point---) | Gets or sets a Count length array of WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the array of points, in logical units. |
| [getAbTypes()](#getAbTypes--) | Gets or sets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Gets or sets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Initializes a new instance of the `EmfPolyDraw` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Initializes a new instance of the [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) class.

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


Gets or sets a Count length array of WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the array of points, in logical units.

**Returns:**
com.aspose.imaging.Point[]
### setAPoints(Point[] value) {#setAPoints-com.aspose.imaging.Point---}
```
public void setAPoints(Point[] value)
```


Gets or sets a Count length array of WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the array of points, in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Gets or sets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. This value MUST be in the Point (section 2.1.26) enumeration.

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Gets or sets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. This value MUST be in the Point (section 2.1.26) enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

