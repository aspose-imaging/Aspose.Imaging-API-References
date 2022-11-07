---
title: EmfSelectClipPath
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback device context combining the new region with any existing clipping region using the specified mode.
type: docs
weight: 112
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

The EMR\_SELECTCLIPPATH record specifies the current path as a clipping region for a playback device context, combining the new region with any existing clipping region using the specified mode.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSelectClipPath` class. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | Initializes a new instance of the `EmfSelectClipPath` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Gets or sets a 32-bit unsigned integer that specifies the way to use the path. |
| [setRegionMode(int value)](#setRegionMode-int-) | Gets or sets a 32-bit unsigned integer that specifies the way to use the path. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


Initializes a new instance of the `EmfSelectClipPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


Initializes a new instance of the `EmfSelectClipPath` class.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Gets or sets a 32-bit unsigned integer that specifies the way to use the path. The value MUST be in the RegionMode enumeration (section 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the way to use the path. The value MUST be in the RegionMode enumeration (section 2.1.29).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

