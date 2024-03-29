---
title: EmfDrawEscape
second_title: Aspose.Imaging for .NET API 参考
description: EMR_DRAWESCAPE 记录将任意信息传递给打印机驱动程序意图是 信息将导致绘制完成
type: docs
weight: 3550
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
## EmfDrawEscape class

EMR_DRAWESCAPE 记录将任意信息传递给打印机驱动程序。意图是 信息将导致绘制完成。

```csharp
public sealed class EmfDrawEscape : EmfEscapeRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfDrawEscape](emfdrawescape)(EmfRecord) | 初始化[`EmfDrawEscape`](../emfdrawescape)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfdrawescape/cjin) { get; set; } | 获取或设置一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfdrawescape/data) { get; set; } | 获取或设置要传递给打印机驱动程序的数据。必须有 cjIn 字节可用。 |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape) { get; set; } | 获取或设置一个 32 位无符号整数，指定打印机驱动程序转义到 执行。这必须是 WMF MetafileEscapes 枚举（[MSWMF] 第 2.1.1.17 节）中的值之一。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 也可以看看

* class [EmfEscapeRecordType](../emfescaperecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
