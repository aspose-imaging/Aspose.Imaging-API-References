---
title: "GifPlainTextRenderingBlock 类"
type: docs
weight: 50
url: /zh/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | 初始化 [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) 类的新实例。 |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | 初始化 [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | 整体块大小。 |
| EXTENSION_INTRODUCER [static] | System.Byte | r | 扩展引入器。 |
| EXTENSION_LABEL [static] | System.Byte | r | 纯文本扩展标签。 |
| SUB_BLOCK_SIZE [static] | System.Byte | r | 子块的大小。 |
| character_cell_height | System.Byte | r/w | 获取或设置网格中每个单元格的字符单元高度（像素）。 |
| character_cell_width | System.Byte | r/w | 获取或设置网格中每个单元格的字符单元宽度（像素）。 |
| is_changed | bool | r/w | 获取或设置一个值，指示块是否已更改并需要保存。 |
| plain_text_data | System.Byte | r/w | 获取或设置纯文本数据。 |
| text_background_color_index | System.Byte | r/w | 获取或设置全局调色板中用于绘制文本背景的颜色索引。 |
| text_foreground_color_index | System.Byte | r/w | 获取或设置全局调色板中用于绘制文本前景的颜色索引。 |
| text_grid_height | int | r/w | 获取或设置文本网格的高度（像素） |
| text_grid_left_position | int | r/w | 获取或设置文本网格的左侧位置。 |
| text_grid_top_position | int | r/w | 获取或设置文本网格的顶部位置。 |
| text_grid_width | int | r/w | 获取或设置文本网格的宽度（像素） |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [save(stream)](#save_stream_1) | 将块保存到指定的流。 |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

初始化 [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) 类的新实例。

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

初始化 [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| text_grid_left_position | int | 文本网格左侧位置。 |
| text_grid_top_position | int | 文本网格顶部位置。 |
| text_grid_width | int | 文本网格宽度。 |
| text_grid_height | int | 文本网格高度。 |
| character_cell_width | System.Byte | 字符单元格宽度。 |
| character_cell_height | System.Byte | 字符单元格高度。 |
| text_foreground_color_index | System.Byte | 前景色索引。 |
| text_background_color_index | System.Byte | 背景色索引。 |
| 数据 | System.Byte | 纯文本数据。 |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

将块保存到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存数据的流。 |

