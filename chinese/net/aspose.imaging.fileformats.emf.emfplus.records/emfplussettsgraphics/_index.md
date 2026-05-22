---
title: "类 EmfPlusSetTsGraphics"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTsGraphics 类。EmfPlusSetTSGraphics 记录指定终端服务器的图形设备上下文状态"
type: docs
weight: 6530
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

EmfPlusSetTSGraphics 记录指定终端服务器的图形设备上下文的状态。

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics/)(EmfPlusRecord) | 初始化 `EmfPlusSetTsGraphics` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode/) { get; set; } | 获取或设置一个 8 位无符号整数，指定线条渲染的质量，包括线条抗锯齿的类型。它必须在 SmoothingMode 枚举中定义（第 2.1.1.28 节）。 |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors/) { get; } | 获取一个值，指示是否为 [basic vga colors]。如果设置，则调色板仅包含基本 VGA 颜色。 |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode/) { get; set; } | 获取或设置一个 8 位无符号整数，指定源颜色如何与背景颜色组合。它必须是 CompositingMode 枚举中的一个值（第 2.1.1.5 节）。 |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality/) { get; set; } | 获取或设置一个 8 位无符号整数，指定对线条、曲线以及填充区域边缘进行平滑处理的程度，使其看起来更连续或更清晰。它必须是 CompositingQuality 枚举中的一个值（第 2.1.1.6 节）。 |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | 获取或设置一个 32 位无符号整数，必须定义随后 RecordData 字段中数据的 32 位对齐字节数。此数字不包括 12 字节的记录头。 |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype/) { get; set; } | 获取或设置一个 8 位无符号整数，指定如何执行缩放，包括拉伸和收缩。它必须是 FilterType 枚举中的一个值（第 2.1.1.11 节）。 |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | 获取或设置一个 16 位无符号整数，包含某些记录的操作执行方式及记录结构的信息。 |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette/) { get; } | 获取一个值，指示是否 [have palette]。如果设置，则此记录在图形状态数据之后的 Palette 字段中包含一个 EmfPlusPalette 对象（第 2.2.2.28 节）。 |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette/) { get; set; } | 获取或设置一个可选的 EmfPlusPalette 对象。 |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset/) { get; set; } | 获取或设置一个 8 位无符号整数，指定图像和文本渲染过程的整体质量。它必须是 PixelOffsetMode 枚举中的一个值（第 2.1.1.26 节）。 |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx/) { get; set; } | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点水平坐标。 |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy/) { get; set; } | 获取或设置一个 16 位有符号整数，表示用于渲染半色调和抖动矩阵的原点垂直坐标。 |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | 获取或设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast/) { get; set; } | 获取或设置一个 16 位无符号整数，指定用于渲染抗锯齿和 ClearType 文本的伽马校正值。该值必须在 0 到 12（含）之间。 |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint/) { get; set; } | 获取或设置一个 8 位无符号整数，指定文本渲染的质量，包括文本抗锯齿的类型。它必须在 TextRenderingHint 枚举中定义（第 2.1.1.32 节）。 |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | 获取一个 16 位无符号整数，标识记录类型。 |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice/) { get; set; } | 获取或设置一个 192 位 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定世界空间到设备空间的变换。 |

### 另请参见

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


