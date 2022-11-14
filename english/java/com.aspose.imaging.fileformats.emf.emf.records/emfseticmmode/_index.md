---
title: EmfSetIcmMode
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETICMMODE record specifies the mode of Image Color Management ICM for graphics operations.
type: docs
weight: 122
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

The EMR\_SETICMMODE record specifies the mode of Image Color Management (ICM) for graphics operations.

When ICM mode is enabled, colors specified in EMF records SHOULD be color matched, whereas the default color profile in the playback device context SHOULD be used when a bit-block transfer is performed. If the default color profile is not desired, ICM mode SHOULD be turned off before performing the bit-block transfer.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetIcmMode` class. |
## Methods

| Method | Description |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | Gets or sets a 32-bit unsigned integer that specifies whether to enable or disable ICM, from the ICMMode enumeration (section 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | Gets or sets a 32-bit unsigned integer that specifies whether to enable or disable ICM, from the ICMMode enumeration (section 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


Initializes a new instance of the `EmfSetIcmMode` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


Gets or sets a 32-bit unsigned integer that specifies whether to enable or disable ICM, from the ICMMode enumeration (section 2.1.18). This value is part of the state of the playback device context.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


Gets or sets a 32-bit unsigned integer that specifies whether to enable or disable ICM, from the ICMMode enumeration (section 2.1.18). This value is part of the state of the playback device context.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

