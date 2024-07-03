---
title: EmfOffsetClipRgn
second_title: Aspose.Imaging for Java API Reference
description: The EMR_OFFSETCLIPRGN record moves the current clipping region in the playback device context by the specified offsets.
type: docs
weight: 78
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfOffsetClipRgn extends EmfClippingRecordType
```

The EMR\_OFFSETCLIPRGN record moves the current clipping region in the playback device context by the specified offsets.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfOffsetClipRgn(EmfRecord source)](#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfOffsetClipRgn` class. |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn--) | Initializes a new instance of the `EmfOffsetClipRgn` class. |
## Methods

| Method | Description |
| --- | --- |
| [getOffset()](#getOffset--) | Gets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the horizontal and vertical offsets in logical units. |
| [setOffset(Point value)](#setOffset-com.aspose.imaging.Point-) | Sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the horizontal and vertical offsets in logical units. |
### EmfOffsetClipRgn(EmfRecord source) {#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfOffsetClipRgn(EmfRecord source)
```


Initializes a new instance of the `EmfOffsetClipRgn` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfOffsetClipRgn() {#EmfOffsetClipRgn--}
```
public EmfOffsetClipRgn()
```


Initializes a new instance of the `EmfOffsetClipRgn` class.

### getOffset() {#getOffset--}
```
public Point getOffset()
```


Gets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the horizontal and vertical offsets in logical units.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOffset(Point value) {#setOffset-com.aspose.imaging.Point-}
```
public void setOffset(Point value)
```


Sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the horizontal and vertical offsets in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

