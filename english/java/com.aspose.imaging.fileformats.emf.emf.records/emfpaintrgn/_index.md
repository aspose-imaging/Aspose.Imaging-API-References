---
title: EmfPaintRgn
second_title: Aspose.Imaging for Java API Reference
description: The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the playback device context.
type: docs
weight: 79
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

The EMR\_PAINTRGN record paints the specified region by using the brush currently selected into the playback device context.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfPaintRgn` class. |
| [EmfPaintRgn()](#EmfPaintRgn--) | Initializes a new instance of the `EmfPaintRgn` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [getRgnDataSize()](#getRgnDataSize--) | Gets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [getRgnData()](#getRgnData--) | Gets a RgnDataSize length array of bytes that specifies a RegionData (section 2.2.24) object, in logical units. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Sets a RgnDataSize length array of bytes that specifies a RegionData (section 2.2.24) object, in logical units. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


Initializes a new instance of the `EmfPaintRgn` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


Initializes a new instance of the `EmfPaintRgn` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Gets a 32-bit unsigned integer that specifies the size of region data, in bytes.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Sets a 32-bit unsigned integer that specifies the size of region data, in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Gets a RgnDataSize length array of bytes that specifies a RegionData (section 2.2.24) object, in logical units.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Sets a RgnDataSize length array of bytes that specifies a RegionData (section 2.2.24) object, in logical units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

