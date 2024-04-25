---
title: EmfSetViewportExtEx
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETVIEWPORTEXTEX record defines the viewport extent.
type: docs
weight: 139
url: /com.aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetViewportExtEx extends EmfStateRecordType
```

The EMR\_SETVIEWPORTEXTEX record defines the viewport extent.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetViewportExtEx(EmfRecord source)](#EmfSetViewportExtEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetViewportExtEx` class. |
| [EmfSetViewportExtEx()](#EmfSetViewportExtEx--) | Initializes a new instance of the `EmfSetViewportExtEx` class. |
## Methods

| Method | Description |
| --- | --- |
| [getExtent()](#getExtent--) | Gets or sets a 64-bit WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the horizontal and vertical extents in device units. |
| [setExtent(Size value)](#setExtent-com.aspose.imaging.Size-) | Gets or sets a 64-bit WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the horizontal and vertical extents in device units. |
### EmfSetViewportExtEx(EmfRecord source) {#EmfSetViewportExtEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetViewportExtEx(EmfRecord source)
```


Initializes a new instance of the `EmfSetViewportExtEx` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetViewportExtEx() {#EmfSetViewportExtEx--}
```
public EmfSetViewportExtEx()
```


Initializes a new instance of the `EmfSetViewportExtEx` class.

### getExtent() {#getExtent--}
```
public Size getExtent()
```


Gets or sets a 64-bit WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the horizontal and vertical extents in device units.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setExtent(Size value) {#setExtent-com.aspose.imaging.Size-}
```
public void setExtent(Size value)
```


Gets or sets a 64-bit WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the horizontal and vertical extents in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

