---
title: "类 EmfPlusDrawImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawImage 类。EmfPlusDrawImage 记录指定绘制缩放图像。"
type: docs
weight: 6080
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
## EmfPlusDrawImage class

EmfPlusDrawImage 记录指定绘制缩放图像。

```csharp
public sealed class EmfPlusDrawImage : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawImage](emfplusdrawimage/)(EmfPlusRecord) | 初始化 `EmfPlusDrawImage` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/compressed/) { get; set; } | 获取或设置一个值，指示 PointData 是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果清除，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/imageattributesid/) { get; set; } | 获取或设置图像属性标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选的 EmfPlusImageAttributes 对象（第 2.2.1.5 节）的索引。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/objectid/) { get; set; } | 获取或设置对象标识符。该标识符是 EMF+ 对象表中 EmfPlusImage 对象（第 2.2.1.4 节）的索引，指定要渲染的图像。该值必须在 0 到 63（含）之间。 |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/rectdata/) { get; set; } | 获取或设置矩形数据，可以是定义图像边界框的 EmfPlusRect 或 EmfPlusRectF 对象。由 SrcRect 字段指定的图像部分将被缩放以适应此矩形。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/srcrect/) { get; set; } | 获取或设置源矩形，一个指定要渲染的图像部分的 EmfPlusRectF 对象。该矩形指定的图像部分将被缩放以适应由 RectData 字段指定的目标矩形。 |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/srcunit/) { get; set; } | 获取或设置源单位，一个 32 位有符号整数，指定 SrcRect 字段的单位。它必须是 UnitType 枚举（第 2.1.1.33 节）中的 UnitTypePixel 成员。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


