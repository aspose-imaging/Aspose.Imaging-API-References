---
title: WmfEscapeEnhancedMetafile
second_title: Aspose.Imaging for Java API Reference
description: The Escape Enhanced Meta file record.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

The Escape Enhanced Meta file record.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Gets or sets the comment identifier. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Gets or sets the comment identifier. |
| [getCommentType()](#getCommentType--) | Gets or sets the type of the comment. |
| [setCommentType(int value)](#setCommentType-int-) | Gets or sets the type of the comment. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets the version. |
| [getChecksum()](#getChecksum--) | Gets or sets the checksum. |
| [setChecksum(int value)](#setChecksum-int-) | Gets or sets the checksum. |
| [getFlags()](#getFlags--) | Gets or sets the flags. |
| [setFlags(int value)](#setFlags-int-) | Gets or sets the flags. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Gets or sets the comment record count. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Gets or sets the comment record count. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Gets or sets the size of the current record. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Gets or sets the size of the current record. |
| [getRemainingBytes()](#getRemainingBytes--) | Gets or sets the remaining bytes. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Gets or sets the remaining bytes. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Gets or sets the size of the enhanced metafile data. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Gets or sets the size of the enhanced metafile data. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Gets or sets the enhanced metafile data. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Gets or sets the enhanced metafile data. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Gets or sets the comment identifier.

Value: A 32-bit unsigned integer that defines this record as a WMF Comment record. This value MUST be 0x43464D57.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Gets or sets the comment identifier.

Value: A 32-bit unsigned integer that defines this record as a WMF Comment record. This value MUST be 0x43464D57.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Gets or sets the type of the comment.

Value: A 32-bit unsigned integer that identifies the type of comment in this record. This value MUST be 0x00000001.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Gets or sets the type of the comment.

Value: A 32-bit unsigned integer that identifies the type of comment in this record. This value MUST be 0x00000001.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Gets or sets the version.

Value: A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Gets or sets the version.

Value: A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Gets or sets the checksum.

Value: A 16-bit unsigned integer used to validate the correctness of the embedded EMF stream. This value MUST be the one's-complement of the result of applying an XOR operation to all WORDs in the EMF stream.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Gets or sets the checksum.

Value: A 16-bit unsigned integer used to validate the correctness of the embedded EMF stream. This value MUST be the one's-complement of the result of applying an XOR operation to all WORDs in the EMF stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Gets or sets the flags.

Value: This 32-bit unsigned integer is unused and MUST be set to zero.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Gets or sets the flags.

Value: This 32-bit unsigned integer is unused and MUST be set to zero.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Gets or sets the comment record count.

Value: A 32-bit unsigned integer that specifies the total number of consecutive META\_ESCAPE\_ENHANCED\_METAFILE records that contain the embedded EMF metafile.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Gets or sets the comment record count.

Value: A 32-bit unsigned integer that specifies the total number of consecutive META\_ESCAPE\_ENHANCED\_METAFILE records that contain the embedded EMF metafile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Gets or sets the size of the current record.

Value: A 32-bit unsigned integer that specifies the size, in bytes, of the EnhancedMetafileData field. This value MUST be less than or equal to 8,192.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Gets or sets the size of the current record.

Value: A 32-bit unsigned integer that specifies the size, in bytes, of the EnhancedMetafileData field. This value MUST be less than or equal to 8,192.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Gets or sets the remaining bytes.

Value: A 32-bit unsigned integer that specifies the number of bytes in the EMF stream that remain to be processed after this record. Those additional EMF bytes MUST follow in the EnhancedMetafileData fields of subsequent META\_ESCAPE\_ENHANDED\_METAFILE escape records.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Gets or sets the remaining bytes.

Value: A 32-bit unsigned integer that specifies the number of bytes in the EMF stream that remain to be processed after this record. Those additional EMF bytes MUST follow in the EnhancedMetafileData fields of subsequent META\_ESCAPE\_ENHANDED\_METAFILE escape records.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Gets or sets the size of the enhanced metafile data.

Value: A 32-bit unsigned integer that specifies the total size of the EMF stream embedded in this sequence of META\_ESCAPE\_ENHANCED\_METAFILE records.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Gets or sets the size of the enhanced metafile data.

Value: A 32-bit unsigned integer that specifies the total size of the EMF stream embedded in this sequence of META\_ESCAPE\_ENHANCED\_METAFILE records.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Gets or sets the enhanced metafile data.

Value: A segment of an EMF file. The bytes in consecutive META\_ESCAPE\_ENHANCED\_METAFILE records MUST be concatenated to represent the entire embedded EMF file.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Gets or sets the enhanced metafile data.

Value: A segment of an EMF file. The bytes in consecutive META\_ESCAPE\_ENHANCED\_METAFILE records MUST be concatenated to represent the entire embedded EMF file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

