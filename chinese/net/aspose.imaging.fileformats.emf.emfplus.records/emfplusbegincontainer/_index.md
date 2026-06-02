---
title: "类 EmfPlusBeginContainer"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusBeginContainer 类。EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定变换。"
type: docs
weight: 5960
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
## EmfPlusBeginContainer class

EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定变换。

```csharp
public sealed class EmfPlusBeginContainer : EmfPlusStateRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusBeginContainer](emfplusbegincontainer/)(EmfPlusRecord) | 初始化 `EmfPlusBeginContainer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| [DestRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/destrect/) { get; set; } | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象与 SrcRect 一起指定容器的变换。当该变换应用于 DestRect 时会产生 SrcRect。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/pageunit/) { get; } | 获取页面单位。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/srcrect/) { get; set; } | 获取或设置一个 EmfPlusRectF 矩形，该矩形与 DestRect 一起指定容器的变换。当该变换应用于 DestRect 时会产生 SrcRect。 |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/stackindex/) { get; set; } | 获取或设置一个 32 位无符号整数，指定与图形状态容器关联的索引。该索引必须在后续的 EmfPlusEndContainer 记录（第 2.3.7.3 节）中被引用，以关闭图形状态容器。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


