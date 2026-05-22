---
title: "类 EmfPlusSetClipRegion"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetClipRegion 类。EmfPlusSetClipRegion 记录将当前裁剪区域与另一个图形区域合并。新的当前裁剪区域设置为对先前的当前裁剪区域和指定的 EmfPlusRegion 对象执行 CombineMode 操作后的结果。"
type: docs
weight: 6430
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
## EmfPlusSetClipRegion class

此 EmfPlusSetClipRegion 记录将当前剪裁区域与另一个图形区域合并。新的当前剪裁区域被设置为对先前的当前剪裁区域和指定的 EmfPlusRegion 对象执行 CombineMode 操作的结果。

```csharp
public sealed class EmfPlusSetClipRegion : EmfPlusClippingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetClipRegion](emfplussetclipregion/)(EmfPlusRecord) | 初始化 `EmfPlusSetClipRegion` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/cm/) { get; set; } | 获取或设置 CM（4 位）：指定合并两个区域的逻辑操作。有关取值含义，请参阅 CombineMode 枚举（第 2.1.1.4 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/objectid/) { get; set; } | 获取或设置 EMF+ 对象表中 EmfPlusRegion 对象（第 2.2.1.8 节）的索引。该值必须在 0 到 63（含）之间。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


