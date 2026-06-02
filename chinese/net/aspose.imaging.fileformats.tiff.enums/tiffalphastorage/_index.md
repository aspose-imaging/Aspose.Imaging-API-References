---
title: "枚举 TiffAlphaStorage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Tiff.Enums.TiffAlphaStorage 枚举。指定 TIFF 文档的 alpha 存储方式"
type: docs
weight: 7710
url: /zh/net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
## TiffAlphaStorage enumeration

指定 tiff 文档的 alpha 存储。

```csharp
public enum TiffAlphaStorage : ushort
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Unspecified | `0` | alpha 未指定并存储在 TIFF 文件中。 |
| Associated | `1` | alpha 值以预乘形式存储。恢复 alpha 时可能出现一些四舍五入效应，恢复后的值可能与原始值不同。 |
| Unassociated | `2` | alpha 值以非关联形式存储。这意味着恢复的 alpha 与存储到 TIFF 中的完全相同。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums/)
* assembly [Aspose.Imaging](../../)


