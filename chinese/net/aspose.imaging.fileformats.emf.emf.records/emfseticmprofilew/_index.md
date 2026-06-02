---
title: "类 EmfSetIcmProfileW"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmProfileW 类。EMR_SETICMPROFILEW 记录指定一个颜色配置文件，该文件的名称由用于图形输出的 Unicode 字符组成。"
type: docs
weight: 4480
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
## EmfSetIcmProfileW class

EMR_SETICMPROFILEW 记录指定在文件中使用由 Unicode 字符组成的名称的颜色配置文件，用于图形输出。

```csharp
public sealed class EmfSetIcmProfileW : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetIcmProfileW](emfseticmprofilew/)(EmfRecord) | 初始化 `EmfSetIcmProfileW` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbdata/) { get; set; } | 获取或设置一个 32 位无符号整数，指定颜色配置文件数据的大小（如果已附加）。 |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbname/) { get; set; } | 获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 Unicode UTF16-LE 名称的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/data/) { get; set; } | 获取或设置一个大小为 (cbName + cbData) 字节的数组，指定所需颜色配置文件的 UTF16-LE 名称和原始数据。 |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/dwflags/) { get; set; } | 获取或设置一个包含颜色配置文件标志的 32 位无符号整数。 |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/name/) { get; } | 获取名称 |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/rawdata/) { get; } | 获取原始数据 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


