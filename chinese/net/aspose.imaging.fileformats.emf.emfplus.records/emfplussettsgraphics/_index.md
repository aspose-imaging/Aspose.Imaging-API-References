---
title: EmfPlusSetTsGraphics
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusSetTSGraphics 记录指定终端服务器的图形设备上下文的状态
type: docs
weight: 6410
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

EmfPlusSetTSGraphics 记录指定终端服务器的图形设备上下文的状态。

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | 初始化[`EmfPlusSetTsGraphics`](../emfplussettsgraphics)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | 获取或设置一个 8 位无符号整数，指定线条渲染的质量， 包括线条抗锯齿的类型。它必须在 SmoothingMode 枚举（第 2.1.1.28 节）中定义。 |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | 获取一个值，该值指示是否[基本vga颜色]。 如果设置，调色板只包含基本的 VGA 颜色。 |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | 获取或设置一个 8 位无符号整数，该整数指定源颜色 与背景颜色的组合方式。它必须是 CompositingMode 枚举（第 2.1.1.5 节）中的一个值。 |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | 获取或设置一个 8 位无符号整数，指定应用于直线、曲线和填充区域边缘的 平滑度使它们看起来更 连续或明确定义。它必须是 CompositingQuality 枚举中的一个值（第 2.1.1.6 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在 RecordData 字段中定义 32 位对齐的 数据字节数跟随。这个数字不包括 12 字节的记录头。 |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | 获取或设置一个 8 位无符号整数，指定如何执行缩放，包括拉伸 和收缩。它必须是 FilterType 枚举中的一个值（第 2.1.1.11 节）。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | 获取或设置一个 16 位无符号整数，该整数包含有关如何执行 操作和结构的一些记录的信息记录。 |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | 获取是否[有调色板]的值。 如果设置，则此记录在图形状态数据之后的 Palette 字段中包含 EmfPlusPalette 对象（第 2.2.2.28 节）。 |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | 获取或设置可选的 EmfPlusPalette 对象。 |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | 获取或设置一个 8 位无符号整数，指定图像 和文本渲染过程的整体质量。它必须是 PixelOffsetMode 枚举中的一个值（第 2.1.1.26 节）。 |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | 获取或设置一个 16 位有符号整数，它是 原点的水平坐标，用于渲染半色调和抖动矩阵。 |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | 获取或设置一个 16 位有符号整数，它是原点的垂直坐标 用于渲染半色调和抖动矩阵。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整条记录中的 32 位对齐字节数 ，包括 12 -byte 记录头和特定于记录的数据。 |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | 获取或设置一个 16 位无符号整数，指定伽马校正值 用于呈现抗锯齿和 ClearType 文本。此值必须在 0 到 12 的范围内，包括 0 到 12。 |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | 获取或设置一个 8 位无符号整数，指定文本 渲染的质量，包括文本抗锯齿的类型。它必须在 TextRenderingHint 枚举（第 2.1.1.32 节）中定义。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | 获取或设置一个 192 位 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象 指定世界空间到设备空间的转换。 |

### 也可以看看

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->