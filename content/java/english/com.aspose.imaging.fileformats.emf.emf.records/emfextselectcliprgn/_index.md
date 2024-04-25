---
title: EmfExtSelectClipRgn
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region using the specified mode.
type: docs
weight: 54
url: /com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

The EMR\_EXTSELECTCLIPRGN record combines the specified region with the current clip region using the specified mode. Note Fields that are not described in this section are specified in section 2.3.2.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfExtSelectClipRgn` class. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Initializes a new instance of the `EmfExtSelectClipRgn` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Gets or sets a 32-bit unsigned integer that specifies the size of region data in bytes. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Gets or sets a 32-bit unsigned integer that specifies the size of region data in bytes. |
| [getRegionMode()](#getRegionMode--) | Gets or sets a 32-bit unsigned integer that specifies the way to use the region. |
| [setRegionMode(int value)](#setRegionMode-int-) | Gets or sets a 32-bit unsigned integer that specifies the way to use the region. |
| [getRgnData()](#getRgnData--) | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object in logical units. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object in logical units. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Initializes a new instance of the `EmfExtSelectClipRgn` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Initializes a new instance of the `EmfExtSelectClipRgn` class.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Gets or sets a 32-bit unsigned integer that specifies the size of region data in bytes.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size of region data in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Gets or sets a 32-bit unsigned integer that specifies the way to use the region. The value MUST be in the RegionMode (section 2.1.29) enumeration.

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the way to use the region. The value MUST be in the RegionMode (section 2.1.29) enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object in logical units. If RegionMode is RGN\_COPY, this data can be omitted and the clip region SHOULD be set to the default (NULL) clip region.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object in logical units. If RegionMode is RGN\_COPY, this data can be omitted and the clip region SHOULD be set to the default (NULL) clip region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

