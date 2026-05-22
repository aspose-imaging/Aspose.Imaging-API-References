---
title: "类 EmfPlusDrawPath"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawPath 类。EmfPlusDrawPath 记录指定绘制图形路径。"
type: docs
weight: 6110
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
## EmfPlusDrawPath class

EmfPlusDrawPath 记录指定绘制图形路径。

```csharp
public sealed class EmfPlusDrawPath : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawPath](emfplusdrawpath/)(EmfPlusRecord) | 初始化 `EmfPlusDrawPath` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/objectid/) { get; set; } | 获取或设置对象标识符。该标识符是 EMF+ 对象表中用于绘制的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。 |
| [PenId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/penid/) { get; set; } | 获取或设置笔标识符，一个 32 位无符号整数，指定 EMF+ 对象表中用于绘制 EmfPlusPath 的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


