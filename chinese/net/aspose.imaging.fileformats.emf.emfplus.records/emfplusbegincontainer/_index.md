---
title: EmfPlusBeginContainer
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定一个变换
type: docs
weight: 5840
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
## EmfPlusBeginContainer class

EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定一个变换。

```csharp
public sealed class EmfPlusBeginContainer : EmfPlusStateRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusBeginContainer](emfplusbegincontainer)(EmfPlusRecord) | 初始化[`EmfPlusBeginContainer`](../emfplusbegincontainer)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在 RecordData 字段中定义 32 位对齐的 数据字节数跟随。这个数字不包括 12 字节的记录头。 |
| [DestRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/destrect) { get; set; } | 获取或设置 EmfPlusRectF 对象（第 2.2.2.39 节），该对象与 SrcRect 一起指定 容器的转换。此转换在应用于 DestRect 时会产生 SrcRect。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | 获取或设置一个 16 位无符号整数，该整数包含有关如何执行 操作和结构的一些记录的信息记录。 |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/pageunit) { get; } | 获取页面单位。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整条记录中的 32 位对齐字节数 ，包括 12 -byte 记录头和特定于记录的数据。 |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/srcrect) { get; set; } | 获取或设置一个 EmfPlusRectF 矩形，该矩形与 DestRect 一起为容器指定变换 。此转换在应用于 DestRect 时会产生 SrcRect。 |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/stackindex) { get; set; } | 获取或设置一个 32 位无符号整数，该整数指定与 图形状态容器相关联的索引。该索引必须被后续的 EmfPlusEndContainer 记录（第 2.3.7.3 节）引用以关闭图形状态容器。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |

### 也可以看看

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->