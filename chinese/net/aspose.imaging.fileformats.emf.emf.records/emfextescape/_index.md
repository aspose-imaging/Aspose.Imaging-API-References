---
title: "类 EmfExtEscape"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtEscape 类。EMR_EXTESCAPE 记录向打印机驱动程序传递任意信息。其意图是这些信息不会导致绘图操作。"
type: docs
weight: 3740
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfextescape/
---
## EmfExtEscape class

EMR_EXTESCAPE 记录向打印机驱动程序传递任意信息。其意图是这些信息不会导致绘图操作。

```csharp
public sealed class EmfExtEscape : EmfEscapeRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfExtEscape](emfextescape/)(EmfRecord) | 初始化 `EmfExtEscape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfextescape/cjin/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要传递给打印机驱动程序的字节数。 |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfextescape/data/) { get; set; } | 获取或设置要传递给打印机驱动程序的数据。必须有 cjIn 字节可用。 |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape/) { get; set; } | 获取或设置一个 32 位无符号整数，指定要执行的打印机驱动程序转义。该值必须是 WMF MetafileEscapes 枚举中的一个值（[MSWMF] 第 2.1.1.17 节）。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfEscapeRecordType](../emfescaperecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


