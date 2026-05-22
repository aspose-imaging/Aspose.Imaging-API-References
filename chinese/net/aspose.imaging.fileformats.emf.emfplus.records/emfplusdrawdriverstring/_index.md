---
title: "类 EmfPlusDrawDriverString"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawDriverString 类。EmfPlusDrawDriverString 记录指定带有字符位置的文本输出。"
type: docs
weight: 6060
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

EmfPlusDrawDriverString 记录指定带有字符位置的文本输出。

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring/)(EmfPlusRecord) | 初始化 `EmfPlusDrawDriverString` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid/) { get; set; } | 获取或设置画笔标识符，一个 32 位无符号整数，根据 Flags 中的 S 标志的值指定文本的前景颜色或图形画刷。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags/) { get; set; } | 获取或设置驱动字符串选项标志，一个 32 位无符号整数，指定字符串的间距、方向和渲染质量。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount/) { get; set; } | 获取或设置字形计数，一个 32 位无符号整数，指定字符串中的字形数量。 |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos/) { get; set; } | 获取或设置字形位置数组，一个 EmfPlusPointF 对象数组（第 2.2.2.36 节），用于指定每个字符字形的输出位置。必须有 GlyphCount 个元素，这些元素与 Glyphs 数组中的元素一一对应。如果在 DriverStringOptions 标志中设置了 DriverStringOptionsRealizedAdvance 标志，则字形位置从第一个字形的位置计算。在这种情况下，GlyphPos 仅指定第一个字形的位置。 |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs/) { get; set; } | 获取或设置字形数组，一个 16 位值的数组，定义要绘制的文本字符串。如果在 DriverStringOptionsFlags 字段中设置了 DriverStringOptionsCmapLookup 标志，则数组中的每个值表示一个 Unicode 字符。否则，每个值表示在 Flags 字段的 ObjectId 值指定的 EmfPlusFont 对象中的字符字形索引。 |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor/) { get; set; } | 获取或设置一个值，指示此实例是否为颜色。此位指示 BrushId 字段中数据的类型。如果设置，则 BrushId 指定 EmfPlusARGB 对象（第 2.2.2.1 节）中的颜色值。如果未设置，则 BrushId 包含 EmfPlusBrush 对象（第 2.2.1.1 节）的 EMF+ 对象表索引。 |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent/) { get; set; } | 获取或设置矩阵存在标志，一个 32 位无符号整数，指定 TransformMatrix 字段中是否存在变换矩阵。0 - 未存在矩阵。1 - 变换矩阵位于 TransformMatrix 字段。 |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid/) { get; set; } | 获取或设置对象标识符。用于渲染文本的 [EmfPlusFont](EmfPlusFont) 对象（第 2.2.1.3 节）的 EMF+ 对象表索引。该值必须在 0 到 63（含）之间。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix/) { get; set; } | 获取或设置变换矩阵，一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定要应用于文本数组中每个值的变换。该数据的存在性由 MatrixPresent 字段决定。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |

### 另请参见

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


