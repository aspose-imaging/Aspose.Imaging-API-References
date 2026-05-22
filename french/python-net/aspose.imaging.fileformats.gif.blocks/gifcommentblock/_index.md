---
title: "Classe GifCommentBlock"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Initialise une nouvelle instance de la classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Initialise une nouvelle instance de la classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Définit la taille de l'en-tête du bloc. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduiseur d'extension. |
| EXTENSION_LABEL [statique] | System.Byte | r | Étiquette d'extension du bloc de commentaire Gif. |
| commentaire | string | r/w | Obtient ou définit le commentaire. Notez que le commentaire doit utiliser l'encodage ASCII et sera stocké en conséquence. |
| is_changed | bool | r/w | Obtient ou définit une valeur indiquant si le bloc a changé et nécessite une sauvegarde. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Enregistre le bloc dans le flux spécifié. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Initialise une nouvelle instance de la classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Initialise une nouvelle instance de la classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| commentaire | string | Le commentaire. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Enregistre le bloc dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données. |

