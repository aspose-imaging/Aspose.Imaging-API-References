---
title: EmfSetBkMode
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETBKMODE record specifies the background mix mode of the playback device context.
type: docs
weight: 120
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

The EMR\_SETBKMODE record specifies the background mix mode of the playback device context. The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetBkMode` class. |
| [EmfSetBkMode()](#EmfSetBkMode--) | Initializes a new instance of the `EmfSetBkMode` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Gets or sets a 32-bit unsigned integer that specifies the background mode and MUST be in the BackgroundMode (section 2.1.4) enumeration. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Gets or sets a 32-bit unsigned integer that specifies the background mode and MUST be in the BackgroundMode (section 2.1.4) enumeration. |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


Initializes a new instance of the `EmfSetBkMode` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


Initializes a new instance of the `EmfSetBkMode` class.

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Gets or sets a 32-bit unsigned integer that specifies the background mode and MUST be in the BackgroundMode (section 2.1.4) enumeration.

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the background mode and MUST be in the BackgroundMode (section 2.1.4) enumeration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

