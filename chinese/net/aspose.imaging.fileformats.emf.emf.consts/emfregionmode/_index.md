---
title: "枚举 EmfRegionMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfRegionMode 枚举。RegionMode 枚举定义了与 EMR_SELECTCLIPPATH 和 EMR_EXTSELECTCLIPRGN 一起使用的值，用于指定当前路径或与当前剪裁区域合并的新区域"
type: docs
weight: 2920
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
## EmfRegionMode enumeration

该 RegionMode 枚举定义了与 EMR_SELECTCLIPPATH 和 EMR_EXTSELECTCLIPRGN 一起使用的取值，用于指定当前路径或与当前剪裁区域合并的新区域。

```csharp
public enum EmfRegionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| RGN_AND | `1` | 新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的交集（重叠区域）。 |
| RGN_OR | `2` | 新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的并集（组合区域）。 |
| RGN_XOR | `3` | 新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的并集，但不包括重叠区域 |
| RGN_DIFF | `4` | 新的裁剪区域包括当前裁剪区域的区域，同时排除当前路径（或新区域）的区域。 |
| RGN_COPY | `5` | 新的裁剪区域是当前路径（或新区域）。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


