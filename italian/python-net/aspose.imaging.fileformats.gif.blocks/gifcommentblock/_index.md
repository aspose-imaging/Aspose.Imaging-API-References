---
title: "GifCommentBlock Classe"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Inizializza una nuova istanza della classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Inizializza una nuova istanza della classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Definisce la dimensione dell'intestazione del blocco. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduttore di estensione. |
| EXTENSION_LABEL [static] | System.Byte | r | Etichetta di estensione del blocco di commento Gif. |
| commento | string | r/w | Ottiene o imposta il commento. Nota che il commento deve utilizzare la codifica ASCII e sarà memorizzato di conseguenza. |
| is_changed | bool | r/w | Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [save(stream)](#save_stream_1) | Salva il blocco nello stream specificato. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Inizializza una nuova istanza della classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Inizializza una nuova istanza della classe [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| commento | string | Il commento. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Salva il blocco nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

