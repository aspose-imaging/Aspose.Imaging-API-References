---
title: "GifCommentBlock-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Initierar en ny instans av klassen [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Initierar en ny instans av klassen [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Definierar blockhuvudets storlek. |
| EXTENSION_INTRODUCER [statisk] | System.Byte | r | Extension‑introducer. |
| EXTENSION_LABEL [statisk] | System.Byte | r | Gif-kommentarblockets förlängningsetikett. |
| kommentar | string | r/w | Hämtar eller anger kommentaren. Observera att kommentaren måste använda ASCII-kodning och kommer att lagras därefter. |
| is_changed | bool | r/w | Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Sparar blocket till den angivna strömmen. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Initierar en ny instans av klassen [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Initierar en ny instans av klassen [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kommentar | string | Kommentaren. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Sparar blocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara data till. |

