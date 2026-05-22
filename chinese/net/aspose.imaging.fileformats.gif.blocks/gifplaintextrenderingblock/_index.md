---
title: "类 GifPlainTextRenderingBlock"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Gif.Blocks.GifPlainTextRenderingBlock 类。Gif 纯文本扩展块。该纯文本扩展包含文本数据以及将这些数据以简单图形形式呈现所需的参数。"
type: docs
weight: 6750
url: /zh/net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
## GifPlainTextRenderingBlock class

Gif 纯文本扩展块。该纯文本扩展包含文本数据以及将这些数据渲染为图形所需的参数，以简洁的形式呈现。

```csharp
public class GifPlainTextRenderingBlock : GifBlock
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GifPlainTextRenderingBlock](gifplaintextrenderingblock/#constructor)() | 初始化 `GifPlainTextRenderingBlock` 类的新实例。 |
| [GifPlainTextRenderingBlock](gifplaintextrenderingblock/#constructor_1)(ushort, ushort, ushort, ushort, byte, byte, byte, byte, byte[]) | 初始化 `GifPlainTextRenderingBlock` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CharacterCellHeight](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/charactercellheight/) { get; set; } | 获取或设置网格中每个单元格的字符单元高度（像素）。 |
| [CharacterCellWidth](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/charactercellwidth/) { get; set; } | 获取或设置网格中每个单元格的字符单元宽度（像素）。 |
| [IsChanged](../../aspose.imaging.fileformats.gif/gifblock/ischanged/) { get; set; } | 获取或设置一个值，指示块是否已更改并需要保存。 |
| [PlainTextData](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/plaintextdata/) { get; set; } | 获取或设置纯文本数据。 |
| [TextBackgroundColorIndex](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/textbackgroundcolorindex/) { get; set; } | 获取或设置用于绘制文本背景的全局颜色调色板中的颜色索引。 |
| [TextForegroundColorIndex](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/textforegroundcolorindex/) { get; set; } | 获取或设置用于绘制文本前景的全局颜色调色板中的颜色索引。 |
| [TextGridHeight](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/textgridheight/) { get; set; } | 获取或设置文本网格的高度（像素） |
| [TextGridLeftPosition](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/textgridleftposition/) { get; set; } | 获取或设置文本网格的左侧位置。 |
| [TextGridTopPosition](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/textgridtopposition/) { get; set; } | 获取或设置文本网格的顶部位置。 |
| [TextGridWidth](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/textgridwidth/) { get; set; } | 获取或设置文本网格的宽度（像素） |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/save/)(Stream) | 将块保存到指定的流。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [BlockSize](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/blocksize/) | 整体块大小。 |
| const [ExtensionLabel](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/extensionlabel/) | 纯文本扩展标签。 |
| const [SubBlockSize](../../aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/subblocksize/) | 子块的大小。 |

### 另请参见

* class [GifBlock](../../aspose.imaging.fileformats.gif/gifblock/)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../aspose.imaging.fileformats.gif.blocks/)
* assembly [Aspose.Imaging](../../)


