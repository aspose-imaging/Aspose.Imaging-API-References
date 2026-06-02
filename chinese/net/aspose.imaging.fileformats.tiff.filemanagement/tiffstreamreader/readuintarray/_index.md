---
title: "TiffStreamReader.ReadUIntArray"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffStreamReader 方法。从流中读取无符号整数值数组"
type: docs
weight: 220
url: /zh/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readuintarray/
---
## TiffStreamReader.ReadUIntArray method

从流中读取 unsigned integer 值数组。

```csharp
public uint[] ReadUIntArray(long position, long count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | Int64 | 读取位置。 |
| count | Int64 | 元素计数。 |

### 返回值

无符号整数值数组。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | count;总字节计数为负。 + count + x4= + totalBytes |

### 另请参见

* class [TiffStreamReader](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assembly [Aspose.Imaging](../../../)


