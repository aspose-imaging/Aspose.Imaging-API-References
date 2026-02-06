---
title: Class GifGraphicsControlBlock
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Gif.Blocks.GifGraphicsControlBlock class. Gif graphics control block
type: docs
weight: 6740
url: /net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
## GifGraphicsControlBlock class

Gif graphics control block.

```csharp
public class GifGraphicsControlBlock : GifBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor)() | Initializes a new instance of the `GifGraphicsControlBlock` class. |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor_1)(byte, ushort, byte) | Initializes a new instance of the `GifGraphicsControlBlock` class. |
| [GifGraphicsControlBlock](gifgraphicscontrolblock/#constructor_2)(ushort, bool, byte, bool, DisposalMethod) | Initializes a new instance of the `GifGraphicsControlBlock` class. |

## Properties

| Name | Description |
| --- | --- |
| [DelayTime](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/delaytime/) { get; set; } | Gets or sets the frame delay time expressed in 1/100 seconds. |
| [DisposalMethod](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/disposalmethod/) { get; set; } | Gets or sets the disposal method. |
| [Flags](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/flags/) { get; set; } | Gets or sets the flags. |
| [HasTransparentColor](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/hastransparentcolor/) { get; set; } | Gets or sets a value indicating whether graphics control block has transparent color. |
| [IsChanged](../../aspose.imaging.fileformats.gif/gifblock/ischanged/) { get; set; } | Gets or sets a value indicating whether block has changed and requires save. |
| [TransparentColorIndex](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/transparentcolorindex/) { get; set; } | Gets or sets the transparent color index. |
| [UserInputExpected](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/userinputexpected/) { get; set; } | Gets or sets a value indicating whether user input is expected. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/save/)(Stream) | Saves the block to the specified stream. |
| static [CreateFlags](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/createflags/)(bool, bool, DisposalMethod) | Creates the flags. |

## Fields

| Name | Description |
| --- | --- |
| const [BlockHeaderSize](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/blockheadersize/) | Specifies the block header size. |
| const [ExtensionLabel](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/extensionlabel/) | Extension label. |
| const [SubBlockSize](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/subblocksize/) | Gets the sub-block size. |

### See Also

* class [GifBlock](../../aspose.imaging.fileformats.gif/gifblock/)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../aspose.imaging.fileformats.gif.blocks/)
* assembly [Aspose.Imaging](../../)


