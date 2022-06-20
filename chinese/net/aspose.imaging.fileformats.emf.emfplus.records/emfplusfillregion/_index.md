---
title: EmfPlusFillRegion
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusFillRegion 记录指定填充图形区域的内部
type: docs
weight: 6120
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
## EmfPlusFillRegion class

EmfPlusFillRegion 记录指定填充图形区域的内部

```csharp
public sealed class EmfPlusFillRegion : EmfPlusDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusFillRegion](emfplusfillregion)(EmfPlusRecord) | 初始化[`EmfPlusFillRegion`](../emfplusfillregion)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/brushid) { get; set; } | 获取或设置画笔标识 定义画笔的32位无符号整数，其内容由中的S位决定标志字段。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在 RecordData 字段中定义 32 位对齐的 数据字节数跟随。这个数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | 获取或设置一个 16 位无符号整数，该整数包含有关如何执行 操作和结构的一些记录的信息记录。 |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/iscolor) { get; set; } | 获取或设置一个指示此实例是否为彩色的值。 如果设置，BrushId 将颜色指定为 EmfPlusARGB 对象（第 2.2.2.1 节）。 如果清除，BrushId 包含 EmfPlusBrush 对象（第 2.2.1.1 节）在 EMF+ 对象表中的索引。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/objectid) { get; set; } | 获取或设置对象标识符。 EmfPlusRegion 对象（第 2.2.1.8 节）的索引，在 EMF+ 对象表中填写。该值必须是 0 到 63（含）。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整条记录中的 32 位对齐字节数 ，包括 12 -byte 记录头和特定于记录的数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |

### 也可以看看

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->