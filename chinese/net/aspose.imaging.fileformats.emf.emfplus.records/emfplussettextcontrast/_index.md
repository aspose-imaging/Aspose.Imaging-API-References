---
title: "类 EmfPlusSetTextContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTextContrast 类。EmfPlusSetTextContrast 记录根据伽马校正值指定文本对比度"
type: docs
weight: 6500
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
## EmfPlusSetTextContrast class

EmfPlusSetTextContrast 记录根据伽马校正值指定文本对比度。

```csharp
public sealed class EmfPlusSetTextContrast : EmfPlusPropertyRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetTextContrast](emfplussettextcontrast/)(EmfPlusRecord) | 初始化 `EmfPlusSetTextContrast` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/textcontrast/) { get; set; } | 获取或设置伽马校正值（乘以 1000），该值将应用于后续的文本渲染操作。允许范围为 1000 到 2200，代表文本伽马值 1.0 到 2.2。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


