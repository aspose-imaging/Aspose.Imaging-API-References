---
title: EmfCommentWindowsMetaFile
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.
type: docs
weight: 32
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

The EMR\_COMMENT\_WINDOWS\_METAFILE record specifies an image in an embedded WMF metafile.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCommentWindowsMetaFile` class. |
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets or sets a 16-bit unsigned integer that specifies the WMF metafile version in terms of support for device-independent bitmaps (DIBs), from the WMF MetafileVersion enumeration ([MS-WMF] section 2.1.1.19). |
| [setVersion(short value)](#setVersion-short-) | Gets or sets a 16-bit unsigned integer that specifies the WMF metafile version in terms of support for device-independent bitmaps (DIBs), from the WMF MetafileVersion enumeration ([MS-WMF] section 2.1.1.19). |
| [getChecksum()](#getChecksum--) | Gets or sets a 32-bit unsigned integer that specifies the checksum for this record. |
| [setChecksum(int value)](#setChecksum-int-) | Gets or sets a 32-bit unsigned integer that specifies the checksum for this record. |
| [getFlags()](#getFlags--) | Gets or sets a 32-bit value that MUST be 0x00000000 and MUST be ignored. |
| [setFlags(int value)](#setFlags-int-) | Gets or sets a 32-bit value that MUST be 0x00000000 and MUST be ignored. |
| [getWinMetafileSize()](#getWinMetafileSize--) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the WMF metafile in the WinMetafile field. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the WMF metafile in the WinMetafile field. |
| [getWinMetafile()](#getWinMetafile--) | Gets or sets a buffer that contains the WMF metafile. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | Gets or sets a buffer that contains the WMF metafile. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


Initializes a new instance of the `EmfCommentWindowsMetaFile` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


Gets or sets a 16-bit unsigned integer that specifies the WMF metafile version in terms of support for device-independent bitmaps (DIBs), from the WMF MetafileVersion enumeration ([MS-WMF] section 2.1.1.19).

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Gets or sets a 16-bit unsigned integer that specifies the WMF metafile version in terms of support for device-independent bitmaps (DIBs), from the WMF MetafileVersion enumeration ([MS-WMF] section 2.1.1.19).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Gets or sets a 32-bit unsigned integer that specifies the checksum for this record.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the checksum for this record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Gets or sets a 32-bit value that MUST be 0x00000000 and MUST be ignored.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Gets or sets a 32-bit value that MUST be 0x00000000 and MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the WMF metafile in the WinMetafile field.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the WMF metafile in the WinMetafile field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


Gets or sets a buffer that contains the WMF metafile.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


Gets or sets a buffer that contains the WMF metafile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

