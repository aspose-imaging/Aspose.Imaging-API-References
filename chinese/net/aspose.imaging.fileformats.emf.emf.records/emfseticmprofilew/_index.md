---
title: EmfSetIcmProfileW
second_title: Aspose.Imaging for .NET API 参考
description: EMR_SETICMPROFILEW 记录指定文件中的颜色配置文件其名称由 Unicode 字符组成用于图形输出
type: docs
weight: 4360
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
## EmfSetIcmProfileW class

EMR_SETICMPROFILEW 记录指定文件中的颜色配置文件，其名称由 Unicode 字符组成，用于图形输出。

```csharp
public sealed class EmfSetIcmProfileW : EmfStateRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfSetIcmProfileW](emfseticmprofilew)(EmfRecord) | 初始化[`EmfSetIcmProfileW`](../emfseticmprofilew)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbdata) { get; set; } | 获取或设置一个 32 位无符号整数，指定颜色配置文件数据的大小（如果附加）。 |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbname) { get; set; } | 获取或设置一个 32 位无符号整数，它指定所需颜色配置文件的 Unicode UTF16-LE 名称中的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/data) { get; set; } | 获取或设置大小为 (cbName + cbData) 的数组，以字节为单位，指定所需颜色配置文件的 UTF16-LE 名称和原始数据。 |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/dwflags) { get; set; } | 获取或设置一个包含颜色配置文件标志的 32 位无符号整数。 |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/name) { get; } | 获取名称 |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/rawdata) { get; } | 获取原始数据 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 也可以看看

* class [EmfStateRecordType](../emfstaterecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
