---
title: EmfRectangle
second_title: Aspose.Imaging for Java API Reference
description: The EMR_RECTANGLE record draws a rectangle.
type: docs
weight: 107
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

The EMR\_RECTANGLE record draws a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush.

The current position is neither used nor updated by Rectangle. If a PS\_NULL pen is used, the dimensions of the rectangle are 1 pixel less in height and 1 pixel less in width.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfRectangle` class. |
| [EmfRectangle()](#EmfRectangle--) | Initializes a new instance of the `EmfRectangle` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBox()](#getBox--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive rectangle to draw. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive rectangle to draw. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Initializes a new instance of the `EmfRectangle` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Initializes a new instance of the `EmfRectangle` class.

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

