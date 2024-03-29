---
title: EmfRegionMode
second_title: Aspose.Imaging for .NET API 参考
description: RegionMode 枚举定义与 EMR_SELECTCLIPPATH 和 EMR_EXTSELECTCLIPRGN 一起使用的值 指定当前路径或与当前剪辑区域组合的新区域
type: docs
weight: 2830
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
## EmfRegionMode enumeration

RegionMode 枚举定义与 EMR_SELECTCLIPPATH 和 EMR_EXTSELECTCLIPRGN 一起使用的值， 指定当前路径或与当前剪辑区域组合的新区域。

```csharp
public enum EmfRegionMode
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| RGN_AND | `1` | 新剪裁区域包括当前剪裁区域与当前路径（或新区域）的交集（重叠区域）。 |
| RGN_OR | `2` | 新剪裁区域包括当前剪裁区域和当前路径（或新区域）的并集（合并区域）。 |
| RGN_XOR | `3` | 新剪裁区域包括当前剪裁区域和当前路径（或新区域）的并集，但没有重叠区域 |
| RGN_DIFF | `4` | 新剪切区域包括当前剪切区域的区域，当前路径（或新区域）的区域除外。 |
| RGN_COPY | `5` | 新的剪辑区域是当前路径（或新的区域）。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
