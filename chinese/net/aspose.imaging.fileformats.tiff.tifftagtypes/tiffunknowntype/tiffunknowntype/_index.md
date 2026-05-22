---
title: "TiffUnknownType.TiffUnknownType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffUnknownType 构造函数。初始化 TiffUnknownType 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tiffunknowntype/
---
## TiffUnknownType constructor

初始化 [`TiffUnknownType`](../) 类的新实例。

```csharp
public TiffUnknownType(TiffStreamReader stream, ushort tagType, ushort tagId, ulong count, 
    ulong offsetOrValue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | TiffStreamReader | 要读取的流。 |
| tagType | UInt16 | 标签的类型。 |
| tagId | UInt16 | 标签 ID。 |
| count | UInt64 | 计数值。 |
| offsetOrValue | UInt64 | 偏移或值。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidDataException | Tiff 标签值超出数据长度。 |

### 另请参见

* class [TiffStreamReader](../../../aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/)
* class [TiffUnknownType](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../tiffunknowntype/)
* assembly [Aspose.Imaging](../../../)


