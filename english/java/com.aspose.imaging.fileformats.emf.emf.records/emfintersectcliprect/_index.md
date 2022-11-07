---
title: EmfIntersectClipRect
second_title: Aspose.Imaging for Java API Reference
description: The EMR_INTERSECTCLIPRECT record specifies a new clipping region from the intersection of the current clipping region and the specified rectangle.
type: docs
weight: 65
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

The EMR\_INTERSECTCLIPRECT record specifies a new clipping region from the intersection of the current clipping region and the specified rectangle. Note Fields that are not described in this section are specified in section 2.3.2.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfIntersectClipRect` class. |
## Methods

| Method | Description |
| --- | --- |
| [getClip()](#getClip--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangle in logical units. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangle in logical units. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


Initializes a new instance of the `EmfIntersectClipRect` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangle in logical units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangle in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

