---
title: EmfPlusDrawRects
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusDrawRects 记录指定绘制一系列矩形
type: docs
weight: 6010
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
## EmfPlusDrawRects class

EmfPlusDrawRects 记录指定绘制一系列矩形

```csharp
public sealed class EmfPlusDrawRects : EmfPlusDrawingRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusDrawRects](emfplusdrawrects)(EmfPlusRecord) | 初始化[`EmfPlusDrawRects`](../emfplusdrawrects)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/compressed) { get; set; } | 获取或设置一个指示PointData是否被压缩的值。 如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。 如果清除，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在 RecordData 字段中定义 32 位对齐的 数据字节数跟随。这个数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | 获取或设置一个 16 位无符号整数，该整数包含有关如何执行 操作和结构的一些记录的信息记录。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/objectid) { get; set; } | 获取或设置对象标识符。 用于绘制矩形的 EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须是 0 到 63（含）。 |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/rectdata) { get; set; } | 获取或设置矩形数据 定义矩形数据的 Count 长度的 EmfPlusRect 或 EmfPlusRectF 对象的数组。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整条记录中的 32 位对齐字节数 ，包括 12 -byte 记录头和特定于记录的数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |

### 也可以看看

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->