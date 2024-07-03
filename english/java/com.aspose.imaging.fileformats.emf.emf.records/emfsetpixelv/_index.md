---
title: EmfSetPixelV
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETPIXELV record defines the color of the pixel at the specified logical coordinates.
type: docs
weight: 135
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSetPixelV extends EmfDrawingRecordType
```

The EMR\_SETPIXELV record defines the color of the pixel at the specified logical coordinates.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetPixelV(EmfRecord source)](#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetPixelV` class. |
| [EmfSetPixelV()](#EmfSetPixelV--) | Initializes a new instance of the [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPixel()](#getPixel--) | Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the logical coordinates for the pixel. |
| [setPixel(Point value)](#setPixel-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the logical coordinates for the pixel. |
| [getArgb32Color()](#getArgb32Color--) | Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pixel color. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pixel color. |
### EmfSetPixelV(EmfRecord source) {#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPixelV(EmfRecord source)
```


Initializes a new instance of the `EmfSetPixelV` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetPixelV() {#EmfSetPixelV--}
```
public EmfSetPixelV()
```


Initializes a new instance of the [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv) class.

### getPixel() {#getPixel--}
```
public Point getPixel()
```


Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the logical coordinates for the pixel.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPixel(Point value) {#setPixel-com.aspose.imaging.Point-}
```
public void setPixel(Point value)
```


Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the logical coordinates for the pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pixel color.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Gets or sets a 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pixel color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

