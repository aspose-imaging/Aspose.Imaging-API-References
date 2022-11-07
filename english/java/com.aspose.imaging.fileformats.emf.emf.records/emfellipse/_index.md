---
title: EmfEllipse
second_title: Aspose.Imaging for Java API Reference
description: The EMR_ELLIPSE record specifies an ellipse.
type: docs
weight: 45
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfEllipse extends EmfDrawingRecordType
```

The EMR\_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfEllipse(EmfRecord source)](#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfEllipse` class. |
| [EmfEllipse()](#EmfEllipse--) | Initializes a new instance of the `EmfEllipse` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBox()](#getBox--) | Gets or sets a 128-bit (WMF) RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit (WMF) RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
### EmfEllipse(EmfRecord source) {#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEllipse(EmfRecord source)
```


Initializes a new instance of the `EmfEllipse` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfEllipse() {#EmfEllipse--}
```
public EmfEllipse()
```


Initializes a new instance of the `EmfEllipse` class.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Gets or sets a 128-bit (WMF) RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Gets or sets a 128-bit (WMF) RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

