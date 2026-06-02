---
title: "TiffStreamReader.ReadSIntArray"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffStreamReader 方法。读取来自流的有符号整数数组"
type: docs
weight: 160
url: /zh/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readsintarray/
---
## TiffStreamReader.ReadSIntArray method

从流中读取 signed integer 值数组。

```csharp
public int[] ReadSIntArray(long position, long count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | Int64 | 读取位置。 |
| count | Int64 | 元素计数。 |

### 返回值

有符号整数数组。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | count;总字节计数为负。 + count + x4= + totalBytes |

### 另请参见

* class [TiffStreamReader](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assembly [Aspose.Imaging](../../../)


