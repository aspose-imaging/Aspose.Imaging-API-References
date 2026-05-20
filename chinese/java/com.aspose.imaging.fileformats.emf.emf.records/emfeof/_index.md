---
title: "EmfEof"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_EOF 记录指示元文件的结束并指定调色板。"
type: docs
weight: 48
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

该 EMR\_EOF 记录指示元文件的结束并指定调色板。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfEof` 类的新实例。 |
| [EmfEof()](#EmfEof--) | 初始化 `EmfEof` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | 获取一个可选缓冲区，其中包含调色板数据，该缓冲区不需要与 EMR\_EOF 记录的固定部分连续。 |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | 设置一个可选缓冲区，其中包含调色板数据，该缓冲区不需要与 EMR\_EOF 记录的固定部分连续。 |
| [getSizeLast()](#getSizeLast--) | 获取一个 32 位无符号整数，该整数必须与 Size 相同，并且必须是记录的最后一个字段，从而也是元文件的最后一个字段。 |
| [setSizeLast(int value)](#setSizeLast-int-) | 设置一个 32 位无符号整数，该整数必须与 Size 相同，并且必须是记录的最后一个字段，从而也是元文件的最后一个字段。 |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


初始化 `EmfEof` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 记录。 |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


初始化 `EmfEof` 类的新实例。

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


获取一个可选缓冲区，其中包含调色板数据，该缓冲区不需要与 EMR\_EOF 记录的固定部分连续。因此，缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。此字段的大小必须是 4 字节的整数倍。

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


设置一个可选缓冲区，其中包含调色板数据，该缓冲区不需要与 EMR\_EOF 记录的固定部分连续。因此，缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。此字段的大小必须是 4 字节的整数倍。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


获取一个 32 位无符号整数，该整数必须与 Size 相同，并且必须是记录的最后一个字段，从而也是元文件的最后一个字段。如果存在 LogPaletteEntry 对象，则它们必须位于此字段之前。

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


设置一个 32 位无符号整数，该整数必须与 Size 相同，并且必须是记录的最后一个字段，从而也是元文件的最后一个字段。如果存在 LogPaletteEntry 对象，则它们必须位于此字段之前。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

