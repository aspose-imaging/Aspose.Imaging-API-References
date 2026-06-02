---
title: "类 EmfPlusDrawEllipse"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawEllipse 类。EmfPlusDrawEllipse 记录指定绘制椭圆。"
type: docs
weight: 6070
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
## EmfPlusDrawEllipse class

EmfPlusDrawEllipse 记录指定绘制椭圆。

```csharp
public sealed class EmfPlusDrawEllipse : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawEllipse](emfplusdrawellipse/)(EmfPlusRecord) | 初始化 `EmfPlusDrawEllipse` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/compressed/) { get; set; } | 获取或设置一个值，指示 PointData 是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果清除，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/objectid/) { get; set; } | 获取或设置对象标识符。EMF+ 对象表中用于绘制椭圆的 EmfPlusPen（第 2.2.1.7 节）对象的索引。该值必须在 0 到 63（含）之间。 |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/rectdata/) { get; set; } | 获取或设置矩形数据，可能是定义椭圆边界框的 EmfPlusRect 或 EmfPlusRectF 对象。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


