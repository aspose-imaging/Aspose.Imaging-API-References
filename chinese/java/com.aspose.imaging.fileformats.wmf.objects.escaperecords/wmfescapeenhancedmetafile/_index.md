---
title: "WmfEscapeEnhancedMetafile"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 Escape Enhanced Meta 文件记录。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

该 Escape Enhanced Meta 文件记录。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | 获取或设置注释标识符。 |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | 获取或设置注释标识符。 |
| [getCommentType()](#getCommentType--) | 获取或设置注释的类型。 |
| [setCommentType(int value)](#setCommentType-int-) | 获取或设置注释的类型。 |
| [getVersion()](#getVersion--) | 获取或设置版本。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置版本。 |
| [getChecksum()](#getChecksum--) | 获取或设置校验和。 |
| [setChecksum(int value)](#setChecksum-int-) | 获取或设置校验和。 |
| [getFlags()](#getFlags--) | 获取或设置标志。 |
| [setFlags(int value)](#setFlags-int-) | 获取或设置标志。 |
| [getCommentRecordCount()](#getCommentRecordCount--) | 获取或设置注释记录计数。 |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | 获取或设置注释记录计数。 |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | 获取或设置当前记录的大小。 |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | 获取或设置当前记录的大小。 |
| [getRemainingBytes()](#getRemainingBytes--) | 获取或设置剩余字节。 |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | 获取或设置剩余字节。 |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | 获取或设置增强元文件数据的大小。 |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | 获取或设置增强元文件数据的大小。 |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | 获取或设置增强元文件数据。 |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | 获取或设置增强元文件数据。 |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


获取或设置注释标识符。

值：一个 32 位无符号整数，用于将此记录定义为 WMF Comment record。此值必须为 0x43464D57。

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


获取或设置注释标识符。

值：一个 32 位无符号整数，用于将此记录定义为 WMF Comment record。此值必须为 0x43464D57。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


获取或设置注释的类型。

值：一个 32 位无符号整数，用于标识此记录中注释的类型。此值必须为 0x00000001。

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


获取或设置注释的类型。

值：一个 32 位无符号整数，用于标识此记录中注释的类型。此值必须为 0x00000001。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置版本。

值：一个 32 位无符号整数，指定 EMF 元文件的互操作性。此值应为 0x00010000。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置版本。

值：一个 32 位无符号整数，指定 EMF 元文件的互操作性。此值应为 0x00010000。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


获取或设置校验和。

值：一个 16 位无符号整数，用于验证嵌入的 EMF 流的正确性。此值必须是对 EMF 流中所有 WORD 进行 XOR 操作后结果的反码。

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


获取或设置校验和。

值：一个 16 位无符号整数，用于验证嵌入的 EMF 流的正确性。此值必须是对 EMF 流中所有 WORD 进行 XOR 操作后结果的反码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


获取或设置标志。

值：此 32 位无符号整数未使用，必须设置为零。

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


获取或设置标志。

值：此 32 位无符号整数未使用，必须设置为零。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


获取或设置注释记录计数。

值：一个 32 位无符号整数，指定包含嵌入 EMF 元文件的连续 META\_ESCAPE\_ENHANCED\_METAFILE 记录的总数。

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


获取或设置注释记录计数。

值：一个 32 位无符号整数，指定包含嵌入 EMF 元文件的连续 META\_ESCAPE\_ENHANCED\_METAFILE 记录的总数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


获取或设置当前记录的大小。

值：一个 32 位无符号整数，指定 EnhancedMetafileData 字段的大小（字节）。此值必须小于或等于 8,192。

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


获取或设置当前记录的大小。

值：一个 32 位无符号整数，指定 EnhancedMetafileData 字段的大小（字节）。此值必须小于或等于 8,192。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


获取或设置剩余字节。

值：一个 32 位无符号整数，指定在此记录之后仍需处理的 EMF 流字节数。那些额外的 EMF 字节必须在后续 META\_ESCAPE\_ENHANDED\_METAFILE 转义记录的 EnhancedMetafileData 字段中出现。

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


获取或设置剩余字节。

值：一个 32 位无符号整数，指定在此记录之后仍需处理的 EMF 流字节数。那些额外的 EMF 字节必须在后续 META\_ESCAPE\_ENHANDED\_METAFILE 转义记录的 EnhancedMetafileData 字段中出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


获取或设置增强元文件数据的大小。

值：一个 32 位无符号整数，指定嵌入在此序列的 META\_ESCAPE\_ENHANCED\_METAFILE 记录中的 EMF 流的总大小。

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


获取或设置增强元文件数据的大小。

值：一个 32 位无符号整数，指定嵌入在此序列的 META\_ESCAPE\_ENHANCED\_METAFILE 记录中的 EMF 流的总大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


获取或设置增强元文件数据。

值：EMF 文件的一个片段。连续的 META\_ESCAPE\_ENHANCED\_METAFILE 记录中的字节必须串联起来，以表示整个嵌入的 EMF 文件。

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


获取或设置增强元文件数据。

值：EMF 文件的一个片段。连续的 META\_ESCAPE\_ENHANCED\_METAFILE 记录中的字节必须串联起来，以表示整个嵌入的 EMF 文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

