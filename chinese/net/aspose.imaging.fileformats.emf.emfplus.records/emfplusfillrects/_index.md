---
title: "类 EmfPlusFillRects"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillRects 类。EmfPlusFillRects 记录指定填充一系列矩形的内部。"
type: docs
weight: 6230
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
## EmfPlusFillRects class

此 EmfPlusFillRects 记录指定填充一系列矩形的内部。

```csharp
public sealed class EmfPlusFillRects : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusFillRects](emfplusfillrects/)(EmfPlusRecord) | 初始化 `EmfPlusFillRects` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/brushid/) { get; set; } | 获取或设置画笔标识符：一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。 |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/compressed/) { get; set; } | 获取或设置一个值，指示此 `EmfPlusFillRects` 是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（章节 2.2.2.38）。如果清除，则 RectData 包含 EmfPlusRectF 对象（章节 2.2.2.39）对象。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/iscolor/) { get; set; } | 获取或设置一个值，指示此实例是否为颜色。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）中的颜色。如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/rectdata/) { get; set; } | 获取或设置矩形数据。一个由 Count 长度的 EmfPlusRect 或 EmfPlusRectF 对象组成的数组，定义矩形数据。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


