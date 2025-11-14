---
title: GifPlainTextRenderingBlock Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Initializes a new instance of the [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) class. |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Initializes a new instance of the [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | The overall block size. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Extension introducer. |
| EXTENSION_LABEL [static] | System.Byte | r | The plain text extension label. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | The size of the sub block. |
| character_cell_height | System.Byte | r/w | Gets or sets the character cell height, in pixels, of each cell in the grid. |
| character_cell_width | System.Byte | r/w | Gets or sets the character cell width, in pixels, of each cell in the grid. |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
| plain_text_data | System.Byte | r/w | Gets or sets the plain text data. |
| text_background_color_index | System.Byte | r/w | Gets or sets the index of the color in the global color palette used to draw the text background. |
| text_foreground_color_index | System.Byte | r/w | Gets or sets the index of the color in the global color palette used to draw the text foreground. |
| text_grid_height | int | r/w | Gets or sets the text grid height in pixels |
| text_grid_left_position | int | r/w | Gets or sets the text grid left position. |
| text_grid_top_position | int | r/w | Gets or sets the text grid top position. |
| text_grid_width | int | r/w | Gets or sets the text grid with in pixels |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the block to the specified stream. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Initializes a new instance of the [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) class.

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Initializes a new instance of the [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| text_grid_left_position | int | The text grid left position. |
| text_grid_top_position | int | The text grid top position. |
| text_grid_width | int | The text grid width. |
| text_grid_height | int | The text grid height. |
| character_cell_width | System.Byte | The character cell width. |
| character_cell_height | System.Byte | The character cell height. |
| text_foreground_color_index | System.Byte | The foreground color index. |
| text_background_color_index | System.Byte | The background color index. |
| data | System.Byte | The plain text data. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

