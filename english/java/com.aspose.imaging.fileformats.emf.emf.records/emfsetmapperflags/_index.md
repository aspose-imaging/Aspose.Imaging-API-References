---
title: EmfSetMapperFlags
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETMAPPERFLAGS record specifies parameters of the process of matching logical fonts to physical fonts which is performed by the font mapper.
type: docs
weight: 128
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

The EMR\_SETMAPPERFLAGS record specifies parameters of the process of matching logical fonts to physical fonts, which is performed by the font mapper.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetMapperFlags` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Gets or sets a 32-bit unsigned integer that specifies parameters of the font matching process. |
| [setFlags(int value)](#setFlags-int-) | Gets or sets a 32-bit unsigned integer that specifies parameters of the font matching process. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


Initializes a new instance of the `EmfSetMapperFlags` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Gets or sets a 32-bit unsigned integer that specifies parameters of the font matching process.

0x00000001 The font mapper SHOULD select only fonts that match the aspect ratio of the output device, as it is currently defined in the playback device context.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Gets or sets a 32-bit unsigned integer that specifies parameters of the font matching process.

0x00000001 The font mapper SHOULD select only fonts that match the aspect ratio of the output device, as it is currently defined in the playback device context.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

