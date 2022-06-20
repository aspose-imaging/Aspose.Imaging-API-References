---
title: DualMode
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置一个值表示是否双模 如果设置此标志表示此元文件是双模式这意味着 它包含两组记录每组完全指定 图形内容如果清除则图形内容由 EMF 记录指定并且可能由 EmfPlusGetDC 记录前面的 EMF 记录指定 如果设置了这个标志单独的 EMF 记录应该足以定义 图形内容请注意无论是否设置了双模式标志始终存在一些 EMF 记录即 EMF 控制记录和包含 EMF 记录的 EMF 记录  EMF 控制记录在 MS-EMF 2.3.4 节中指定
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode/
---
## EmfPlusHeader.DualMode property

获取或设置一个值，表示是否[双模]。 如果设置，此标志表示此元文件是“双模式”，这意味着 它包含两组记录，每组完全指定 图形内容。如果清除，则图形内容由 EMF+ 记录指定，并且可能由 EmfPlusGetDC 记录前面的 EMF 记录指定。 如果设置了这个标志，单独的 EMF 记录应该足以定义 图形内容。请注意，无论是否设置了“双模式”标志，始终存在一些 EMF 记录，即 EMF 控制记录和包含 EMF+ 记录的 EMF 记录 。 EMF 控制记录在 [MS-EMF] 2.3.4 节中指定。

```csharp
public bool DualMode { get; set; }
```

### 适当的价值

` true` if [dual mode];否则，` false` 。

### 也可以看看

* class [EmfPlusHeader](../../emfplusheader)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusheader)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->