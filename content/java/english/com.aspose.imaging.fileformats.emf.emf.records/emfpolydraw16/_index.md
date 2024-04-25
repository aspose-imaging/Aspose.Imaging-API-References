---
title: EmfPolyDraw16
second_title: Aspose.Imaging for Java API Reference
description: The EMR_POLYDRAW16 record specifies a set of line segments and Bezier curves.
type: docs
weight: 89
url: /com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyDraw16 extends EmfDrawingRecordType
```

The EMR\_POLYDRAW16 record specifies a set of line segments and Bezier curves.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPolyDraw16` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [getAPoints()](#getAPoints--) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [setAPoints(Point[] value)](#setAPoints-com.aspose.imaging.Point---) | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [getAbTypes()](#getAbTypes--) | Gets or sets a Count length array of bytes that specifies the point types. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Gets or sets a Count length array of bytes that specifies the point types. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Initializes a new instance of the `EmfPolyDraw16` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

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

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Gets or sets a Count length array of bytes that specifies the point types. This value MUST be in the Point (section 2.1.26) enumeration.

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Gets or sets a Count length array of bytes that specifies the point types. This value MUST be in the Point (section 2.1.26) enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

