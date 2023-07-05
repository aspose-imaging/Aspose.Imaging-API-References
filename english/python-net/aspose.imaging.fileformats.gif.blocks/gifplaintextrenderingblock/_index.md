---
title: GifPlainTextRenderingBlock Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Namespace:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Class Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Assembly:**  Aspose.Imaging Version: 23.6.0

The GifPlainTextRenderingBlock type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|GifPlainTextRenderingBlock()|Initializes a new instance of the [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) class.|
|GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)|Initializes a new instance of the GifPlainTextRenderingBlock class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|is_changed|Gets or sets a value indicating whether block has changed and requires save.|
|EXTENSION_INTRODUCER|Extension introducer.|
|text_foreground_color_index|Gets or sets the index of the color in the global color palette used to draw the text foreground.|
|text_background_color_index|Gets or sets the index of the color in the global color palette used to draw the text background.|
|character_cell_width|Gets or sets the character cell width, in pixels, of each cell in the grid.|
|character_cell_height|Gets or sets the character cell height, in pixels, of each cell in the grid.|
|text_grid_left_position|Gets or sets the text grid left position.|
|text_grid_top_position|Gets or sets the text grid top position.|
|text_grid_width|Gets or sets the text grid with in pixels|
|text_grid_height|Gets or sets the text grid height in pixels|
|plain_text_data|Gets or sets the plain text data.|
|EXTENSION_LABEL|The plain text extension label.|
|BLOCK_SIZE|The overall block size.|
|SUB_BLOCK_SIZE|The size of the sub block.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save(stream)|Saves the block to the specified stream.|
