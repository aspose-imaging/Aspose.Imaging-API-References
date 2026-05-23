---
title: "Класс GifPlainTextRenderingBlock"
type: docs
weight: 50
url: /ru/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Инициализирует новый экземпляр класса [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Инициализирует новый экземпляр класса [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | Общий размер блока. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Ввод расширения. |
| EXTENSION_LABEL [static] | System.Byte | r | Метка расширения простого текста. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Размер субблока. |
| character_cell_height | System.Byte | r/w | Получает или задает высоту ячейки символа в пикселях для каждой ячейки в сетке. |
| character_cell_width | System.Byte | r/w | Получает или задает ширину ячейки символа в пикселях для каждой ячейки в сетке. |
| is_changed | bool | r/w | Получает или задает значение, указывающее, изменён ли блок и требует ли сохранения. |
| plain_text_data | System.Byte | r/w | Получает или задает данные простого текста. |
| text_background_color_index | System.Byte | r/w | Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки фона текста. |
| text_foreground_color_index | System.Byte | r/w | Получает или задает индекс цвета в глобальной палитре, используемый для отрисовки переднего плана текста. |
| text_grid_height | int | r/w | Получает или задает высоту текстовой сетки в пикселях |
| text_grid_left_position | int | r/w | Получает или задает левую позицию текстовой сетки. |
| text_grid_top_position | int | r/w | Получает или задает верхнюю позицию текстовой сетки. |
| text_grid_width | int | r/w | Получает или задает ширину текстовой сетки в пикселях |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет блок в указанный поток. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Инициализирует новый экземпляр класса [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Инициализирует новый экземпляр класса [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text_grid_left_position | int | Левая позиция текстовой сетки. |
| text_grid_top_position | int | Верхняя позиция текстовой сетки. |
| text_grid_width | int | Ширина текстовой сетки. |
| text_grid_height | int | Высота текстовой сетки. |
| character_cell_width | System.Byte | Ширина ячейки символа. |
| character_cell_height | System.Byte | Высота ячейки символа. |
| text_foreground_color_index | System.Byte | Индекс цвета переднего плана. |
| text_background_color_index | System.Byte | Индекс цвета фона. |
| данные | System.Byte | Данные простого текста. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет блок в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save data to. |

