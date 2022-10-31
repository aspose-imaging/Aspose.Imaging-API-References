---
title: EmfRoundRect
second_title: Aspose.Imaging for Java API Reference
description: The EMR_ROUNDRECT record specifies a rectangle with rounded corners.
type: docs
weight: 108
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

The EMR\_ROUNDRECT record specifies a rectangle with rounded corners. The rectangle is outlined by using the current pen and filled by using the current brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfRoundRect` class. |
| [EmfRoundRect()](#EmfRoundRect--) | Initializes a new instance of the [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBox()](#getBox--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive rectangle to draw. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive rectangle to draw. |
| [getCorner()](#getCorner--) | Gets or sets a 64-bit WMF SizeL object, specified in [MS-WMF] section 2.2.2.22, which specifies the width and height, in logical coordinates, of the ellipse used to draw the rounded corners. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Gets or sets a 64-bit WMF SizeL object, specified in [MS-WMF] section 2.2.2.22, which specifies the width and height, in logical coordinates, of the ellipse used to draw the rounded corners. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


Initializes a new instance of the `EmfRoundRect` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Initializes a new instance of the [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) class.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive rectangle to draw.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive rectangle to draw.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Gets or sets a 64-bit WMF SizeL object, specified in [MS-WMF] section 2.2.2.22, which specifies the width and height, in logical coordinates, of the ellipse used to draw the rounded corners.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Gets or sets a 64-bit WMF SizeL object, specified in [MS-WMF] section 2.2.2.22, which specifies the width and height, in logical coordinates, of the ellipse used to draw the rounded corners.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

