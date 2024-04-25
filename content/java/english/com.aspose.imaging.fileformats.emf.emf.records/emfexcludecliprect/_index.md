---
title: EmfExcludeClipRect
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing clipping region minus the specified rectangle.
type: docs
weight: 49
url: /com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

The EMR\_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing clipping region minus the specified rectangle. Note Fields that are not described in this section are specified in section 2.3.2.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExcludeClipRect` class. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Initializes a new instance of the `EmfExcludeClipRect` class. |
## Methods

| Method | Description |
| --- | --- |
| [getClip()](#getClip--) | Gets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the clipping rectangle in logical units. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the clipping rectangle in logical units. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Initializes a new instance of the `EmfExcludeClipRect` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Initializes a new instance of the `EmfExcludeClipRect` class.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Gets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the clipping rectangle in logical units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the clipping rectangle in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

