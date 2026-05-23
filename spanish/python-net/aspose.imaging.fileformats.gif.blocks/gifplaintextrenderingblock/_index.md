---
title: "Clase GifPlainTextRenderingBlock"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Inicializa una nueva instancia de la clase [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Inicializa una nueva instancia de la clase [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | El tamaño total del bloque. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introducción de extensión. |
| EXTENSION_LABEL [static] | System.Byte | r | La etiqueta de extensión de texto sin formato. |
| SUB_BLOCK_SIZE [estático] | System.Byte | r | El tamaño del subbloque. |
| character_cell_height | System.Byte | r/w | Obtiene o establece la altura de la celda de carácter, en píxeles, de cada celda en la cuadrícula. |
| character_cell_width | System.Byte | r/w | Obtiene o establece el ancho de la celda de carácter, en píxeles, de cada celda en la cuadrícula. |
| is_changed | bool | r/w | Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado. |
| plain_text_data | System.Byte | r/w | Obtiene o establece los datos de texto sin formato. |
| text_background_color_index | System.Byte | r/w | Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el fondo del texto. |
| text_foreground_color_index | System.Byte | r/w | Obtiene o establece el índice del color en la paleta de colores global utilizada para dibujar el primer plano del texto. |
| text_grid_height | int | r/w | Obtiene o establece la altura de la cuadrícula de texto en píxeles |
| text_grid_left_position | int | r/w | Obtiene o establece la posición izquierda de la cuadrícula de texto. |
| text_grid_top_position | int | r/w | Obtiene o establece la posición superior de la cuadrícula de texto. |
| text_grid_width | int | r/w | Obtiene o establece el ancho de la cuadrícula de texto en píxeles |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda el bloque en el flujo especificado. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Inicializa una nueva instancia de la clase [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Inicializa una nueva instancia de la clase [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text_grid_left_position | int | La posición izquierda de la cuadrícula de texto. |
| text_grid_top_position | int | La posición superior de la cuadrícula de texto. |
| text_grid_width | int | El ancho de la cuadrícula de texto. |
| text_grid_height | int | La altura de la cuadrícula de texto. |
| character_cell_width | System.Byte | El ancho de la celda de carácter. |
| character_cell_height | System.Byte | La altura de la celda de carácter. |
| text_foreground_color_index | System.Byte | El índice de color de primer plano. |
| text_background_color_index | System.Byte | El índice de color de fondo. |
| datos | System.Byte | Los datos de texto sin formato. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos. |

