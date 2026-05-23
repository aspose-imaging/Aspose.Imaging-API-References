---
title: "GifPlainTextRenderingBlock Classe"
type: docs
weight: 50
url: /it/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Inizializza una nuova istanza della classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Inizializza una nuova istanza della classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | La dimensione complessiva del blocco. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduttore di estensione. |
| EXTENSION_LABEL [static] | System.Byte | r | L'etichetta di estensione del testo semplice. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | La dimensione del sotto-blocco. |
| character_cell_height | System.Byte | r/w | Ottiene o imposta l'altezza della cella di carattere, in pixel, di ogni cella nella griglia. |
| character_cell_width | System.Byte | r/w | Ottiene o imposta la larghezza della cella di carattere, in pixel, di ogni cella nella griglia. |
| is_changed | bool | r/w | Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio. |
| plain_text_data | System.Byte | r/w | Ottiene o imposta i dati del testo semplice. |
| text_background_color_index | System.Byte | r/w | Ottiene o imposta l'indice del colore nella tavolozza globale dei colori usata per disegnare lo sfondo del testo. |
| text_foreground_color_index | System.Byte | r/w | Ottiene o imposta l'indice del colore nella tavolozza globale dei colori usata per disegnare il primo piano del testo. |
| text_grid_height | int | r/w | Ottiene o imposta l'altezza della griglia di testo in pixel |
| text_grid_left_position | int | r/w | Ottiene o imposta la posizione sinistra della griglia di testo. |
| text_grid_top_position | int | r/w | Ottiene o imposta la posizione superiore della griglia di testo. |
| text_grid_width | int | r/w | Ottiene o imposta la larghezza della griglia di testo in pixel |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco nello stream specificato. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Inizializza una nuova istanza della classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Inizializza una nuova istanza della classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text_grid_left_position | int | La posizione sinistra della griglia di testo. |
| text_grid_top_position | int | La posizione superiore della griglia di testo. |
| text_grid_width | int | La larghezza della griglia di testo. |
| text_grid_height | int | L'altezza della griglia di testo. |
| character_cell_width | System.Byte | La larghezza della cella del carattere. |
| character_cell_height | System.Byte | L'altezza della cella del carattere. |
| text_foreground_color_index | System.Byte | L'indice del colore di primo piano. |
| text_background_color_index | System.Byte | L'indice del colore di sfondo. |
| dati | System.Byte | I dati di testo semplice. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

