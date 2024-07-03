---
title: EmfEof
second_title: Aspose.Imaging for Java API Reference
description: The EMR_EOF record indicates the end of the metafile and specifies a palette.
type: docs
weight: 48
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

The EMR\_EOF record indicates the end of the metafile and specifies a palette.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfEof` class. |
| [EmfEof()](#EmfEof--) | Initializes a new instance of the `EmfEof` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Gets an optional buffer that contains palette data, which is not required to be contiguous with the fixed portion of the EMR\_EOF record. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Sets an optional buffer that contains palette data, which is not required to be contiguous with the fixed portion of the EMR\_EOF record. |
| [getSizeLast()](#getSizeLast--) | Gets a 32-bit unsigned integer that MUST be the same as Size and MUST be the last field of the record and hence the metafile. |
| [setSizeLast(int value)](#setSizeLast-int-) | Sets a 32-bit unsigned integer that MUST be the same as Size and MUST be the last field of the record and hence the metafile. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


Initializes a new instance of the `EmfEof` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


Initializes a new instance of the `EmfEof` class.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Gets an optional buffer that contains palette data, which is not required to be contiguous with the fixed portion of the EMR\_EOF record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. The size of this field MUST be a multiple of 4 bytes

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Sets an optional buffer that contains palette data, which is not required to be contiguous with the fixed portion of the EMR\_EOF record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. The size of this field MUST be a multiple of 4 bytes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Gets a 32-bit unsigned integer that MUST be the same as Size and MUST be the last field of the record and hence the metafile. LogPaletteEntry objects, if they exist, MUST precede this field.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Sets a 32-bit unsigned integer that MUST be the same as Size and MUST be the last field of the record and hence the metafile. LogPaletteEntry objects, if they exist, MUST precede this field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

