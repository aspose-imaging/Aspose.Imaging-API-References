---
title: EmfPlusSetClipPath
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusSetClipPath 记录将当前剪辑区域与图形路径组合在一起 新的当前剪辑区域设置为 CombineMode 操作的结果
type: docs
weight: 6290
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
## EmfPlusSetClipPath class

EmfPlusSetClipPath 记录将当前剪辑区域与图形路径组合在一起。 新的当前剪辑区域设置为 CombineMode 操作的结果。

```csharp
public sealed class EmfPlusSetClipPath : EmfPlusClippingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusSetClipPath](emfplussetclippath)(EmfPlusRecord) | 初始化[`EmfPlusSetClipPath`](../emfplussetclippath)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/cm) { get; set; } | 获取或设置CM（4位）:指定合并两个区域的逻辑操作。有关值的含义，请参见 CombineMode 枚举（第 2.1.1.4 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在 RecordData 字段中定义 32 位对齐的 数据字节数跟随。这个数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | 获取或设置一个 16 位无符号整数，该整数包含有关如何执行 操作和结构的一些记录的信息记录。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/objectid) { get; set; } | 获取或设置 EMF+ 对象表中 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须是 0 到 63（含）。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整条记录中的 32 位对齐字节数 ，包括 12 -byte 记录头和特定于记录的数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |

### 也可以看看

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
