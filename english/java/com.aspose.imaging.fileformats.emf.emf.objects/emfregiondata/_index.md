---
title: EmfRegionData
second_title: Aspose.Imaging for Java API Reference
description: The RegionData object specifies data that defines a region which is made of non-overlapping rectangles.
type: docs
weight: 33
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

The RegionData object specifies data that defines a region, which is made of non-overlapping rectangles.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Initializes a new instance of the `EmfRegionData` class. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Initializes a new instance of the `EmfRegionData` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Gets a 256-bit RegionDataHeader object that describes the following data. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Sets a 256-bit RegionDataHeader object that describes the following data. |
| [getData()](#getData--) | Gets an array of WMF RectL objects ([MS-WMF] section 2.2.2.19); the objects are merged to create the region |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | Sets an array of WMF RectL objects ([MS-WMF] section 2.2.2.19); the objects are merged to create the region |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Initializes a new instance of the `EmfRegionData` class.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Initializes a new instance of the `EmfRegionData` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Gets a 256-bit RegionDataHeader object that describes the following data.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Sets a 256-bit RegionDataHeader object that describes the following data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


Gets an array of WMF RectL objects ([MS-WMF] section 2.2.2.19); the objects are merged to create the region

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


Sets an array of WMF RectL objects ([MS-WMF] section 2.2.2.19); the objects are merged to create the region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

