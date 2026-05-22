---
title: "ReadSLongArray"
second_title: "Aspose.Imaging for .NET API 参考"
description: 
type: docs
weight: 140
url: /zh/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
## TiffStreamReader.ReadSLongArray method

从流中读取 signed integer 值数组。

```csharp
public int[] ReadSLongArray(long position, long count)
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

* class [TiffStreamReader](../../tiffstreamreader)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader)
* assembly [Aspose.Imaging](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.Imaging.dll 生成 -->
