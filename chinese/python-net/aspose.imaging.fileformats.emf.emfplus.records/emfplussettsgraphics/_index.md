---
title: "EmfPlusSetTsGraphics 类"
type: docs
weight: 580
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---

**Summary:** The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsGraphics

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusSetTsGraphics(source)](#EmfPlusSetTsGraphics_source_1) | 初始化 [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| anti_alias_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | 获取或设置一个 8 位无符号整数，用于指定线条渲染的质量，<br/>            包括线条抗锯齿的类型。它必须在 SmoothingMode<br/>            枚举（第 2.1.1.28 节）中定义。 |
| basic_vga_colors | bool | r | 获取一个值，指示是否为 [basic vga colors]。<br/>            如果设置，则调色板仅包含基本 VGA 颜色。 |
| compositing_mode | [EmfPlusCompositingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingmode/) | r/w | 获取或设置一个 8 位无符号整数，用于指定源颜色如何与背景颜色<br/>            合并。它必须是 CompositingMode<br/>            枚举（第 2.1.1.5 节）中的一个值。 |
| compositing_quality | [EmfPlusCompositingQuality](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/) | r/w | 获取或设置一个 8 位无符号整数，用于指定对线条、曲线以及填充区域边缘进行平滑处理的程度，以使其呈现更<br/>            连续或更清晰的效果。它必须是 CompositingQuality 枚举（第 2.1.1.6 节）中的一个值。 |
| data_size | int | r/w | 获取或设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位对齐字节数。<br/>            此数字不包括 12 字节的记录头。 |
| filter_type | [EmfPlusFilterType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/) | r/w | 获取或设置一个 8 位无符号整数，用于指定缩放（包括拉伸<br/>            和收缩）的执行方式。它必须是 FilterType 枚举（第 2.1.1.11 节）中的一个值。 |
| flags | int | r/w | 获取或设置一个 16 位无符号整数，包含关于某些记录的<br/>            操作方式以及记录结构的信息。 |
| have_palette | bool | r | 获取一个值，指示是否为 [have palette]。<br/>            如果设置，则此记录在图形状态数据之后的<br/>            Palette 字段中包含一个 EmfPlusPalette 对象（第 2.2.2.28 节）。 |
| palette | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | 获取或设置一个可选的 EmfPlusPalette 对象。 |
| pixel_offset | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | 获取或设置一个 8 位无符号整数，用于指定图像<br/>            和文本渲染过程的整体质量。它必须是 PixelOffsetMode 枚举（第 2.1.1.26 节）中的一个值。 |
| render_origin_x | int | r/w | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的<br/>            原点的水平坐标。 |
| render_origin_y | int | r/w | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的<br/>            原点的垂直坐标。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数<br/>            （包括 12 字节的记录头和特定于记录的数据）。 |
| text_contrast | int | r/w | 获取或设置一个 16 位无符号整数，用于指定用于渲染抗锯齿和 ClearType 文本的伽马校正值。<br/>            此值必须在 0 到 12（含）之间。 |
| text_render_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | 获取或设置一个 8 位无符号整数，用于指定文本<br/>            渲染的质量，包括文本抗锯齿的类型。它必须在 TextRenderingHint<br/>            枚举（第 2.1.1.32 节）中定义。 |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | 获取一个 16 位无符号整数，以标识记录类型。 |
| world_to_device | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个 192 位的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象<br/>            指定世界坐标空间到设备坐标空间的变换。 |


### Constructor: EmfPlusSetTsGraphics(source) {#EmfPlusSetTsGraphics_source_1}


```
 EmfPlusSetTsGraphics(source) 
```

初始化 [EmfPlusSetTsGraphics](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | 来源。 |

