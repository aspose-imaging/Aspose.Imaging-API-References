---
title: EmfSetViewportOrgEx
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETVIEWPORTORGEX record defines the viewport origin.
type: docs
weight: 143
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetViewportOrgEx extends EmfStateRecordType
```

The EMR\_SETVIEWPORTORGEX record defines the viewport origin.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetViewportOrgEx(EmfRecord source)](#EmfSetViewportOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetViewportOrgEx` class. |
| [EmfSetViewportOrgEx()](#EmfSetViewportOrgEx--) | Initializes a new instance of the `EmfSetViewportOrgEx` class. |
## Methods

| Method | Description |
| --- | --- |
| [getOrigin()](#getOrigin--) | Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the window horizontal and vertical origin in device units. |
| [setOrigin(Point value)](#setOrigin-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the window horizontal and vertical origin in device units. |
### EmfSetViewportOrgEx(EmfRecord source) {#EmfSetViewportOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetViewportOrgEx(EmfRecord source)
```


Initializes a new instance of the `EmfSetViewportOrgEx` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetViewportOrgEx() {#EmfSetViewportOrgEx--}
```
public EmfSetViewportOrgEx()
```


Initializes a new instance of the `EmfSetViewportOrgEx` class.

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the window horizontal and vertical origin in device units.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOrigin(Point value) {#setOrigin-com.aspose.imaging.Point-}
```
public void setOrigin(Point value)
```


Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the window horizontal and vertical origin in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

