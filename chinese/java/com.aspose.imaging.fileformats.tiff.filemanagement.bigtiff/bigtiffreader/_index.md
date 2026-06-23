---
title: "BigTiffReader"
second_title: "Aspose.Imaging for Java API 参考"
description: "小端序 BigTiff 读取器。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging/fileformats/tiff/filemanagement/tiffstreamreader)
```
public class BigTiffReader extends TiffStreamReader
```

小端序 BigTiff 读取器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BigTiffReader(byte[] data)](#BigTiffReader-byte---) | 初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。 |
| [BigTiffReader(StreamContainer streamContainer)](#BigTiffReader-com.aspose.imaging.StreamContainer-) | 初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。 |
| [BigTiffReader(byte[] data, int startIndex)](#BigTiffReader-byte---int-) | 初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。 |
| [BigTiffReader(byte[] data, int startIndex, int dataLength)](#BigTiffReader-byte---int-int-) | 初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | 获取标签值长度的大小。 |
### BigTiffReader(byte[] data) {#BigTiffReader-byte---}
```
public BigTiffReader(byte[] data)
```


初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 字节数组数据。 |

### BigTiffReader(StreamContainer streamContainer) {#BigTiffReader-com.aspose.imaging.StreamContainer-}
```
public BigTiffReader(StreamContainer streamContainer)
```


初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | 流容器。 |

### BigTiffReader(byte[] data, int startIndex) {#BigTiffReader-byte---int-}
```
public BigTiffReader(byte[] data, int startIndex)
```


初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 字节数组数据。 |
| startIndex | int | `data` 的起始索引。 |

### BigTiffReader(byte[] data, int startIndex, int dataLength) {#BigTiffReader-byte---int-int-}
```
public BigTiffReader(byte[] data, int startIndex, int dataLength)
```


初始化一个新的 [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 字节数组数据。 |
| startIndex | int | `data` 的起始索引。 |
| dataLength | int | 数据的长度。 |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


获取标签值长度的大小。

**Returns:**
byte - 标签值长度的大小。
