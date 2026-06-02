---
title: "EmfPlusDrawDriverString 类"
type: docs
weight: 110
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | 初始化一个新的 [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_id | int | r/w | 获取或设置画刷标识符<br/>            一个 32 位无符号整数，指定文本的前景颜色或图形画刷，取决于 Flags 中 S 标志的值。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | 获取或设置驱动字符串选项标志<br/>            一个 32 位无符号整数，指定字符串渲染的间距、方向和质量。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| glyph_count | int | r/w | 获取或设置字形计数<br/>            一个 32 位无符号整数，指定字符串中的字形数量。 |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | 获取或设置字形位置数组<br/>            一个 EmfPlusPointF 对象数组（章节 2.2.2.36），指定每个字符字形的输出位置。必须有 GlyphCount 个元素，它们与 Glyphs 数组中的元素一一对应。如果在 DriverStringOptions 标志中设置了 DriverStringOptionsRealizedAdvance 标志，则字形位置根据第一个字形的位置计算。在这种情况下，GlyphPos 仅指定第一个字形的位置。 |
| glyphs | int[] | r/w | 获取或设置字形数组<br/>            一个 16 位值数组，定义要绘制的文本字符串。如果在 DriverStringOptionsFlags 字段中设置了 DriverStringOptionsCmapLookup 标志，则此数组中的每个值指定一个 Unicode 字符。否则，每个值指定 EmfPlusFont 对象（由 Flags 字段中的 ObjectId 值指定）中的字符字形索引。 |
| is_color | bool | r/w | 获取或设置一个值，指示此实例是否为颜色。<br/>            此位指示 BrushId 字段中数据的类型。若设置，BrushId 指定 EmfPlusARGB 对象（章节 2.2.2.1）中的颜色值；若未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（章节 2.1.1）的索引。 |
| matrix_present | int | r/w | 获取或设置矩阵存在标志<br/>            一个 32 位无符号整数，指定 TransformMatrix 字段中是否存在变换矩阵。0 - 未存在矩阵。1 - 变换矩阵位于 TransformMatrix 字段中。 |
| object_id | System.Byte | r/w | 获取或设置对象标识符。<br/>            EMF+ 对象表中 ***EmfPlusFont*** 对象（章节 2.2.1.3）的索引，用于渲染文本。该值必须在 0 到 63（含）之间。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置变换矩阵<br/>            一个可选的 EmfPlusTransformMatrix 对象（章节 2.2.2.47），指定对文本数组中每个值应用的变换。该数据的存在性由 MatrixPresent 字段决定。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

初始化一个新的 [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

