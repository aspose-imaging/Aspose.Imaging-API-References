---
title: "GifPlainTextRenderingBlock Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Initialisiert eine neue Instanz der [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) Klasse. |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Initialisiert eine neue Instanz der [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| BLOCK_SIZE [statisch] | System.Byte | r | Die gesamte Blockgröße. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Erweiterungs‑Einführer. |
| EXTENSION_LABEL [static] | System.Byte | r | Das Klartext-Erweiterungslabel. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Die Größe des Unterblocks. |
| character_cell_height | System.Byte | r/w | Liest oder setzt die Zeichenzellenhöhe in Pixeln für jede Zelle im Raster. |
| character_cell_width | System.Byte | r/w | Liest oder setzt die Zeichenzellenbreite in Pixeln für jede Zelle im Raster. |
| is_changed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss. |
| plain_text_data | System.Byte | r/w | Liest oder setzt die Klartextdaten. |
| text_background_color_index | System.Byte | r/w | Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Texthintergrunds verwendet wird. |
| text_foreground_color_index | System.Byte | r/w | Liest oder setzt den Index der Farbe in der globalen Farbpalette, die zum Zeichnen des Textvordergrunds verwendet wird. |
| text_grid_height | int | r/w | Liest oder setzt die Höhe des Textrasters in Pixeln. |
| text_grid_left_position | int | r/w | Liest oder setzt die linke Position des Textrasters. |
| text_grid_top_position | int | r/w | Liest oder setzt die obere Position des Textrasters. |
| text_grid_width | int | r/w | Liest oder setzt die Breite des Textrasters in Pixeln. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Block in den angegebenen Stream. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Initialisiert eine neue Instanz der [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) Klasse.

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Initialisiert eine neue Instanz der [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text_grid_left_position | int | Die linke Position des Textrasters. |
| text_grid_top_position | int | Die obere Position des Textrasters. |
| text_grid_width | int | Die Breite des Textrasters. |
| text_grid_height | int | Die Höhe des Textrasters. |
| character_cell_width | System.Byte | Die Breite der Zeichenzelle. |
| character_cell_height | System.Byte | Die Höhe der Zeichenzelle. |
| text_foreground_color_index | System.Byte | Der Index der Vordergrundfarbe. |
| text_background_color_index | System.Byte | Der Index der Hintergrundfarbe. |
| Daten | System.Byte | Die unformatierten Textdaten. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Block in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem Daten gespeichert werden. |

