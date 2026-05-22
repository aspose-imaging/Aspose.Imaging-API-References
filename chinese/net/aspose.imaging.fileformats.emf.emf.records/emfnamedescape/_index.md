---
title: "类 EmfNamedEscape"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfNamedEscape 类。MR_NAMEDESCAPE 记录将任意信息传递给指定的打印机驱动程序。"
type: docs
weight: 3960
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
## EmfNamedEscape class

MR_NAMEDESCAPE 记录将任意信息传递给指定的打印机驱动程序。

```csharp
public sealed class EmfNamedEscape : EmfEscapeRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfNamedEscape](emfnamedescape/)(EmfRecord) | 初始化 `EmfNamedEscape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CjDriver](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjdriver/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 DriverName 字段的字节数。该值必须为偶数。 |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjin/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/data/) { get; set; } | 获取或设置要传递给打印机驱动程序的数据。必须有 cjIn 字节可用。 |
| [DriverName](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/drivername/) { get; set; } | 获取或设置一个由 16 位 Unicode 字符组成的字符串，指定将接收数据的打印机驱动程序的名称。此值必须是 cjDriver 字节长，并且必须以空字符终止。 |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要执行的打印机驱动程序转义。该值必须是 WMF MetafileEscapes 枚举中的一个值（[MSWMF] 第 2.1.1.17 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfEscapeRecordType](../emfescaperecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


