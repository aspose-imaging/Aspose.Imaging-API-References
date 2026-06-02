---
title: "EmfPlusHeader.DualMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusHeader 属性。获取或设置指示是否为双模式的值。如果设置，此标志表示该元文件为 dualmode，意味着它包含两套记录，每套记录完整指定图形内容。如果未设置，图形内容由 EMF 记录指定，且可能包含前置 EmfPlusGetDC 记录的 EMF 记录。如果此标志被设置，仅 EMF 记录就应足以定义图形内容。请注意，无论 dualmode 标志是否设置，某些 EMF 记录始终存在，即 EMF 控制记录以及包含 EMF 记录的 EMF 记录。EMF 控制记录在 MSEMF 第 2.3.4 节中指定。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode/
---
## EmfPlusHeader.DualMode property

获取或设置一个值，指示是否 [dual mode]。如果设置，则此标志表示该元文件为"dual-mode"，即它包含两套记录，每套记录完整地指定图形内容。如果未设置，则图形内容由 EMF+ 记录指定，且可能还有在 EmfPlusGetDC 记录之前的 EMF 记录。如果此标志被设置，仅 EMF 记录就应足以定义图形内容。请注意，无论"dual-mode"标志是否设置，某些 EMF 记录始终存在，即 EMF 控制记录和包含 EMF+ 记录的 EMF 记录。EMF 控制记录在 [MS-EMF] 第 2.3.4 节中有说明。

```csharp
public bool DualMode { get; set; }
```

### Property Value

`true` 如果是 [dual mode]；否则为 `false`.

### 另请参见

* class [EmfPlusHeader](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusheader/)
* assembly [Aspose.Imaging](../../../)


