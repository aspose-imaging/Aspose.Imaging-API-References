---
title: "类 EmfPlusFillPath"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPath 类。Fill path 记录 FLAGS 为 16 位无符号整数，提供有关如何执行操作以及记录结构的信息。0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X  ObjectId  S 1 位 此位指示 BrushId 字段中数据的类型。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）中的颜色。如果未设置，BrushId 包含 EMF 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。X 1 位 保留，必须忽略。ObjectId 1 字节 用于在 EMF 对象表中填充的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。"
type: docs
weight: 6200
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
## EmfPlusFillPath class

填充路径记录 标志：16 位无符号整数，提供有关如何执行操作以及记录结构的信息。 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X &#x7C; ObjectId &#x7C; S (1 位)：此位指示 BrushId 字段中的数据类型。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果清除，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。X (1 位)：保留，必须忽略。ObjectId (1 字节)：EMF+ 对象表中用于填充的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。

```csharp
public sealed class EmfPlusFillPath : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusFillPath](emfplusfillpath/)(EmfPlusRecord) | 初始化 `EmfPlusFillPath` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/brushid/) { get; set; } | 获取或设置 Brush ID，一个 32 位无符号整数，定义画刷，其内容由 Flags 字段中的 S 位决定。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/iscolor/) { get; set; } | 获取或设置一个值，指示此实例是否为颜色。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）中的颜色。如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/objectid/) { get; set; } | 获取或设置对象标识符。EMF+ 对象表中用于填充的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


