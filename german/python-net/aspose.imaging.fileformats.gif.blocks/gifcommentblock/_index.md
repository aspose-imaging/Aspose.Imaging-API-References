---
title: "GifCommentBlock Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Initialisiert eine neue Instanz der [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) Klasse. |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Initialisiert eine neue Instanz der [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [statisch] | int | r | Definiert die Blockkopfgröße. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Erweiterungs‑Einführer. |
| EXTENSION_LABEL [static] | System.Byte | r | Gif-Kommentarblock-Erweiterungslabel. |
| Kommentar | string | r/w | Liest oder setzt den Kommentar. Hinweis: Der Kommentar muss ASCII-codiert sein und wird entsprechend gespeichert. |
| is_changed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert den Block in den angegebenen Stream. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Initialisiert eine neue Instanz der [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) Klasse.

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Initialisiert eine neue Instanz der [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kommentar | string | Der Kommentar. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert den Block in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem Daten gespeichert werden. |

