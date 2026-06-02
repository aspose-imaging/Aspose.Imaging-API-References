---
title: "类 EmfSetIcmProfileA"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmProfileA 类。EMR_SETICMPROFILEA 记录指定了文件中使用 ASCII 字符名称的颜色配置文件，用于图形输出"
type: docs
weight: 4470
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
## EmfSetIcmProfileA class

EMR_SETICMPROFILEA 记录指定在文件中使用由 ASCII 字符组成的名称的颜色配置文件，用于图形输出。

```csharp
public sealed class EmfSetIcmProfileA : EmfStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfSetIcmProfileA](emfseticmprofilea/)(EmfRecord) | 初始化 `EmfSetIcmProfileA` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbdata/) { get; set; } | 获取或设置一个 32 位无符号整数，指定颜色配置文件数据的大小（如果它包含在 Data 字段中）。 |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbname/) { get; set; } | 获取或设置一个 32 位无符号整数，指定所需颜色配置文件的 ASCII 名称的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/data/) { get; set; } | 获取或设置一个大小为 (cbName + cbData) 字节的数组，指定所需颜色配置文件的 ASCII 名称和原始数据。 |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/dwflags/) { get; set; } | 获取或设置一个包含颜色配置文件标志的 32 位无符号整数。 |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/name/) { get; } | 获取名称 |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/rawdata/) { get; } | 获取原始数据 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


