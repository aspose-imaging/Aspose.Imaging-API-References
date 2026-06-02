---
title: "GifGraphicsControlBlock Classe"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Initialise une nouvelle instance de la [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) classe. |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Initialise une nouvelle instance de la [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) classe. |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Initialise une nouvelle instance de la [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) classe. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Spécifie la taille de l'en-tête du bloc. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduiseur d'extension. |
| EXTENSION_LABEL [statique] | System.Byte | r | Étiquette de l'extension. |
| SUB_BLOCK_SIZE [statique] | System.Byte | r | Obtient la taille du sous-bloc. |
| delay_time | int | r/w | Obtient ou définit le temps de retard de la trame exprimé en 1/100 de seconde. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | Obtient ou définit la méthode de disposition. |
| flags | System.Byte | r/w | Obtient ou définit les indicateurs. |
| has_transparent_color | bool | r/w | Obtient ou définit une valeur indiquant si le bloc de contrôle graphique possède une couleur transparente. |
| is_changed | bool | r/w | Obtient ou définit une valeur indiquant si le bloc a changé et nécessite une sauvegarde. |
| transparent_color_index | System.Byte | r/w | Obtient ou définit l'index de couleur transparente. |
| user_input_expected | bool | r/w | Obtient ou définit une valeur indiquant si une saisie utilisateur est attendue. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Crée les indicateurs. |
| [save(stream)](#save_stream_2) | Enregistre le bloc dans le flux spécifié. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Initialise une nouvelle instance de la [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) classe.

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Initialise une nouvelle instance de la [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) classe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| delay_time | int | Le temps de retard exprimé en 1/100 de seconde. |
| has_transparent_color | bool | si défini sur <c>true</c> l'_transparentColorIndex_ est valide. |
| transparent_color_index | System.Byte | L'index de couleur transparente. |
| requires_user_input | bool | si défini sur <c>true</c> la saisie utilisateur est attendue. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | La méthode de disposition. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Initialise une nouvelle instance de la [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) classe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flags | System.Byte | Les indicateurs. |
| delay_time | int | Le temps de retard exprimé en 1/100 de seconde. |
| transparent_color_index | System.Byte | L'index de couleur transparente. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Crée les indicateurs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| has_transparent_color | bool | si défini sur <c>true</c> le [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) a un index de couleur transparente valide. |
| requires_user_input | bool | si défini sur <c>true</c> la saisie utilisateur est attendue. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | La méthode de disposition. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Les indicateurs générés. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Enregistre le bloc dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données. |

