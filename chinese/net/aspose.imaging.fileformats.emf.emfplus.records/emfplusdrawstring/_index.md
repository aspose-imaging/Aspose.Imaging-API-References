---
title: "类 EmfPlusDrawString"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawString 类。EmfPlusDrawString 记录指定带有字符串格式的文本输出。"
type: docs
weight: 6140
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
## EmfPlusDrawString class

EmfPlusDrawString 记录指定带有字符串格式化的文本输出。

```csharp
public sealed class EmfPlusDrawString : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawString](emfplusdrawstring/)(EmfPlusRecord) | 初始化 `EmfPlusDrawString` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/brushid/) { get; set; } | 获取或设置画笔标识符，一个 32 位无符号整数，用于指定画笔，其内容由 Flags 字段中的 S 位决定。此定义用于绘制前景文本颜色；即仅绘制字形本身。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [FormatId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/formatid/) { get; set; } | 获取或设置格式标识符，一个 32 位无符号整数，用于指定 EMF+ 对象表中可选的 EmfPlusStringFormat 对象（第 2.2.1.9 节）的索引。该对象指定要应用于字符串的文本布局信息和显示操作。 |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/iscolor/) { get; set; } | 获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 以 EmfPlusARGB 对象（第 2.2.2.1 节）指定颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 |
| [LayoutRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/layoutrect/) { get; set; } | 获取或设置布局矩形，一个 EmfPlusRectF 对象（第 2.2.2.39 节），定义将接收字符串的目标的边界区域。 |
| [Length](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/length/) { get; set; } | 获取或设置长度，一个 32 位无符号整数，指定字符串中的字符数。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/objectid/) { get; set; } | 获取或设置对象标识符。EMF+ 对象表中用于渲染文本的 EmfPlusFont 对象（第 2.2.1.3 节）的索引。该值必须在 0 到 63（含）之间。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [StringData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/stringdata/) { get; set; } | 获取或设置字符串数据，一个由 16 位 Unicode 字符组成的数组，指定要绘制的字符串。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


