---
title: "类 GifGraphicsControlBlock"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Gif.Blocks.GifGraphicsControlBlock 类。Gif 图形控制块"
type: docs
weight: 6740
url: /zh/net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
## GifGraphicsControlBlock class

Gif 图形控制块。

```csharp
public class GifGraphicsControlBlock : GifBlock
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor)() | 初始化 `GifGraphicsControlBlock` 类的新实例。 |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor_1)(byte, ushort, byte) | 初始化 `GifGraphicsControlBlock` 类的新实例。 |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor_2)(ushort, bool, byte, bool, DisposalMethod) | 初始化 `GifGraphicsControlBlock` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DelayTime](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/delaytime/) { get; set; } | 获取或设置以 1/100 秒为单位的帧延迟时间。 |
| [DisposalMethod](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/disposalmethod/) { get; set; } | 获取或设置处置方法。 |
| [Flags](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/flags/) { get; set; } | 获取或设置标志。 |
| [HasTransparentColor](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/hastransparentcolor/) { get; set; } | 获取或设置指示图形控制块是否具有透明颜色的值。 |
| [IsChanged](../../aspose.imaging.fileformats.gif/gifblock/ischanged/) { get; set; } | 获取或设置一个值，指示块是否已更改并需要保存。 |
| [TransparentColorIndex](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/transparentcolorindex/) { get; set; } | 获取或设置透明颜色索引。 |
| [UserInputExpected](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/userinputexpected/) { get; set; } | 获取或设置指示是否期望用户输入的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/save/)(Stream) | 将块保存到指定的流。 |
| static [CreateFlags](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/createflags/)(bool, bool, DisposalMethod) | 创建标志。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [BlockHeaderSize](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/blockheadersize/) | 指定块头的大小。 |
| const [ExtensionLabel](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/extensionlabel/) | 扩展标签。 |
| const [SubBlockSize](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/subblocksize/) | 获取子块大小。 |

### 另请参见

* class [GifBlock](../../aspose.imaging.fileformats.gif/gifblock/)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../aspose.imaging.fileformats.gif.blocks/)
* assembly [Aspose.Imaging](../../)


