---
title: "GifPlainTextRenderingBlock Classe"
type: docs
weight: 50
url: /fr/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Initialise une nouvelle instance de la classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Initialise une nouvelle instance de la classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | La taille globale du bloc. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduiseur d'extension. |
| EXTENSION_LABEL [statique] | System.Byte | r | Le libellé d'extension du texte brut. |
| SUB_BLOCK_SIZE [statique] | System.Byte | r | La taille du sous-bloc. |
| character_cell_height | System.Byte | r/w | Obtient ou définit la hauteur de la cellule de caractères, en pixels, de chaque cellule de la grille. |
| character_cell_width | System.Byte | r/w | Obtient ou définit la largeur de la cellule de caractères, en pixels, de chaque cellule de la grille. |
| is_changed | bool | r/w | Obtient ou définit une valeur indiquant si le bloc a changé et nécessite une sauvegarde. |
| plain_text_data | System.Byte | r/w | Obtient ou définit les données du texte brut. |
| text_background_color_index | System.Byte | r/w | Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner l'arrière-plan du texte. |
| text_foreground_color_index | System.Byte | r/w | Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner le premier plan du texte. |
| text_grid_height | int | r/w | Obtient ou définit la hauteur de la grille de texte en pixels |
| text_grid_left_position | int | r/w | Obtient ou définit la position gauche de la grille de texte. |
| text_grid_top_position | int | r/w | Obtient ou définit la position supérieure de la grille de texte. |
| text_grid_width | int | r/w | Obtient ou définit la largeur de la grille de texte en pixels |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc dans le flux spécifié. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Initialise une nouvelle instance de la classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Initialise une nouvelle instance de la classe [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| text_grid_left_position | int | La position gauche de la grille de texte. |
| text_grid_top_position | int | La position supérieure de la grille de texte. |
| text_grid_width | int | La largeur de la grille de texte. |
| text_grid_height | int | La hauteur de la grille de texte. |
| character_cell_width | System.Byte | La largeur de la cellule de caractère. |
| character_cell_height | System.Byte | La hauteur de la cellule de caractère. |
| text_foreground_color_index | System.Byte | L'index de couleur de premier plan. |
| text_background_color_index | System.Byte | L'index de couleur d'arrière-plan. |
| données | System.Byte | Les données de texte brut. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données. |

