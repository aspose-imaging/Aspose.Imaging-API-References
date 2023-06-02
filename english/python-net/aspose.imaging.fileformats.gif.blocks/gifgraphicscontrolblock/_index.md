---
title: GifGraphicsControlBlock Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

Gif graphics control block.

**Namespace:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Class Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Assembly:**  Aspose.Imaging Version: 23.5.0

The GifGraphicsControlBlock type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|GifGraphicsControlBlock()|Initializes a new instance of the [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) class.|
|GifGraphicsControlBlock(flags, delay_time, transparent_color_index)|Initializes a new instance of the GifGraphicsControlBlock class|
|GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)|Initializes a new instance of the GifGraphicsControlBlock class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|is_changed|Gets or sets a value indicating whether block has changed and requires save.|
|EXTENSION_INTRODUCER|Extension introducer.|
|delay_time|Gets or sets the frame delay time expressed in 1/100 seconds.|
|flags|Gets or sets the flags.|
|transparent_color_index|Gets or sets the transparent color index.|
|disposal_method|Gets or sets the disposal method.|
|user_input_expected|Gets or sets a value indicating whether user input is expected.|
|has_transparent_color|Gets or sets a value indicating whether graphics control block has transparent color.|
|BLOCK_HEADER_SIZE|Specifies the block header size.|
|EXTENSION_LABEL|Extension label.|
|SUB_BLOCK_SIZE|Gets the sub-block size.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save(stream)|Saves the block to the specified stream.|
|create_flags(has_transparent_color, requires_user_input, disposal_method)|Creates the flags.|
