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
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | 初始化[`EmfPlusSetTsGraphics`](../emfplussettsgraphics)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | 获取或设置一个 8 位无符号整数，指定线条渲染的质量， 包括线条抗锯齿的类型。它必须在 SmoothingMode 枚举（第 2.1.1.28 节）中定义。 |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | 获取一个值，指示是否 [基本 vga 颜色]。 如果设置，则调色板仅包含基本 VGA 颜色。 |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | 获取或设置一个 8 位无符号整数，该整数指定源颜色是 与背景颜色的组合方式。它必须是 CompositingMode 枚举（第 2.1.1.5 节）中的一个值。 |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | 获取或设置一个 8 位无符号整数，该整数指定应用于线条、曲线和填充区域边缘的 平滑度，以使它们看起来更加连续或清晰。它必须是 CompositingQuality 枚举中的一个值（第 2.1.1.6 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | 获取或设置一个 32 位无符号整数，该整数必须在随后的 RecordData 字段中定义 32 位对齐的 字节数据。这个数字不包括 12 字节的记录头。 |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | 获取或设置一个 8 位无符号整数，指定如何执行缩放，包括拉伸 和收缩。它必须是 FilterType 枚举中的一个值（第 2.1.1.11 节）。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | 获取或设置一个 16 位无符号整数，其中包含一些记录的信息，关于如何执行 操作以及记录的结构。 |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | 获取一个值，指示是否[有调色板]。 如果设置，则此记录在图形状态数据之后的 调色板字段中包含 EmfPlusPalette 对象（第 2.2.2.28 节）。 |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | 获取或设置一个可选的 EmfPlusPalette 对象。 |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | 获取或设置一个 8 位无符号整数，用于指定 image 和文本渲染过程的整体质量。它必须是 PixelOffsetMode 枚举（第 2.1.1.26 节）中的一个值。 |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | 获取或设置一个16位有符号整数，即 原点的水平坐标，用于渲染半色调和抖动矩阵。 |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | 获取或设置一个 16 位有符号整数，即渲染半色调和抖动矩阵的 origin 的垂直坐标。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录中 32 位对齐的字节数 ，包括 12 字节的记录头和特定于记录的数据。 |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | 获取或设置一个 16 位无符号整数，该整数指定用于渲染抗锯齿和 ClearType 文本的 gamma 校正值 。该值必须在 0 到 12 的范围内，包括 0 到 12。 |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | 获取或设置一个 8 位无符号整数，指定 text 渲染的质量，包括文本抗锯齿的类型。它必须在 TextRenderingHint 枚举（第 2.1.1.32 节）中定义。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | 获取标识记录类型的 16 位无符号整数。 |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | 获取或设置一个 192 位 EmfPlusTransformMatrix 对象（第 2.2.2.47 节）， 指定世界空间到设备空间的转换。 |

### 也可以看看

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
