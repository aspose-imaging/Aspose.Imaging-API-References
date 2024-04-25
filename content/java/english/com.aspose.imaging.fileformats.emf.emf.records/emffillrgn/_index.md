---
title: EmfFillRgn
second_title: Aspose.Imaging for Java API Reference
description: The EMR_FILLRGN record fills the specified region by using the specified brush.
type: docs
weight: 58
url: /com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

The EMR\_FILLRGN record fills the specified region by using the specified brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfFillRgn` class. |
| [EmfFillRgn()](#EmfFillRgn--) | Initializes a new instance of the `EmfFillRgn` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [getRgnDataSize()](#getRgnDataSize--) | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [getIhBrush()](#getIhBrush--) | Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index to fill the region. |
| [setIhBrush(int value)](#setIhBrush-int-) | Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index to fill the region. |
| [getRgnData()](#getRgnData--) | Gets or sets a RgnDataSize length array of bytes that contains a RegionData (section 2.2.24) object. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Gets or sets a RgnDataSize length array of bytes that contains a RegionData (section 2.2.24) object. |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


Initializes a new instance of the `EmfFillRgn` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


Initializes a new instance of the `EmfFillRgn` class.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index to fill the region.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index to fill the region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Gets or sets a RgnDataSize length array of bytes that contains a RegionData (section 2.2.24) object.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Gets or sets a RgnDataSize length array of bytes that contains a RegionData (section 2.2.24) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

