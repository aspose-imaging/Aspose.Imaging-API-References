---
title: EmfSetBrushOrgEx
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETBRUSHORGEX record specifies the origin of the current brush.
type: docs
weight: 121
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBrushOrgEx extends EmfStateRecordType
```

The EMR\_SETBRUSHORGEX record specifies the origin of the current brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetBrushOrgEx(EmfRecord source)](#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetBrushOrgEx` class. |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx--) | Initializes a new instance of the `EmfSetBrushOrgEx` class. |
## Methods

| Method | Description |
| --- | --- |
| [getOrigin()](#getOrigin--) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the brush's horizontal and vertical origin in device units. |
| [setOrigin(Point value)](#setOrigin-com.aspose.imaging.Point-) | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the brush's horizontal and vertical origin in device units. |
### EmfSetBrushOrgEx(EmfRecord source) {#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBrushOrgEx(EmfRecord source)
```


Initializes a new instance of the `EmfSetBrushOrgEx` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetBrushOrgEx() {#EmfSetBrushOrgEx--}
```
public EmfSetBrushOrgEx()
```


Initializes a new instance of the `EmfSetBrushOrgEx` class.

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the brush's horizontal and vertical origin in device units.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOrigin(Point value) {#setOrigin-com.aspose.imaging.Point-}
```
public void setOrigin(Point value)
```


Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the brush's horizontal and vertical origin in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

