---
title: "GifPlainTextRenderingBlock-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Initierar en ny instans av klassen [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Initierar en ny instans av klassen [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | Den totala blockstorleken. |
| EXTENSION_INTRODUCER [statisk] | System.Byte | r | Extension‑introducer. |
| EXTENSION_LABEL [statisk] | System.Byte | r | Etiketten för klartextutökning. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Storleken på delblocket. |
| character_cell_height | System.Byte | r/w | Hämtar eller anger teckencellens höjd i pixlar för varje cell i rutnätet. |
| character_cell_width | System.Byte | r/w | Hämtar eller anger teckencellens bredd i pixlar för varje cell i rutnätet. |
| is_changed | bool | r/w | Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning. |
| plain_text_data | System.Byte | r/w | Hämtar eller anger klartextdata. |
| text_background_color_index | System.Byte | r/w | Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textbakgrunden. |
| text_foreground_color_index | System.Byte | r/w | Hämtar eller anger index för färgen i den globala färgpaletten som används för att rita textförgrunden. |
| text_grid_height | int | r/w | Hämtar eller anger textrutnätets höjd i pixlar |
| text_grid_left_position | int | r/w | Hämtar eller anger textrutnätets vänstra position. |
| text_grid_top_position | int | r/w | Hämtar eller anger textrutnätets övre position. |
| text_grid_width | int | r/w | Hämtar eller anger textrutnätets bredd i pixlar |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar blocket till den angivna strömmen. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Initierar en ny instans av klassen [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Initierar en ny instans av klassen [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text_grid_left_position | int | Textrutnätets vänstra position. |
| text_grid_top_position | int | Textrutnätets övre position. |
| text_grid_width | int | Textrutnätets bredd. |
| text_grid_height | int | Textrutnätets höjd. |
| character_cell_width | System.Byte | Teckencellens bredd. |
| character_cell_height | System.Byte | Teckencellens höjd. |
| text_foreground_color_index | System.Byte | Index för förgrundsfärg. |
| text_background_color_index | System.Byte | Index för bakgrundsfärg. |
| data | System.Byte | Den rena textdata. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar blocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara data till. |

