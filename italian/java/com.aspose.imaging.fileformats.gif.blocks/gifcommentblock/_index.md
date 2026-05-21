---
title: "GifCommentBlock"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Blocco di commento Gif."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

Blocco di commento Gif.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | Inizializza una nuova istanza della classe `GifCommentBlock`. |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | Inizializza una nuova istanza della classe `GifCommentBlock`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etichetta di estensione del blocco commento Gif. |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Definisce la dimensione dell'intestazione del blocco. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getComment()](#getComment--) | Ottiene o imposta il commento. |
| [setComment(String value)](#setComment-java.lang.String-) | Ottiene o imposta il commento. |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


Inizializza una nuova istanza della classe `GifCommentBlock`.

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


Inizializza una nuova istanza della classe `GifCommentBlock`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| comment | java.lang.String | Il commento. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etichetta di estensione del blocco commento Gif.

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Definisce la dimensione dell'intestazione del blocco.

### getComment() {#getComment--}
```
public String getComment()
```


Ottiene o imposta il commento. Nota che il commento deve utilizzare la codifica ASCII e sarà memorizzato di conseguenza.

Valore: Il commento.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Ottiene o imposta il commento. Nota che il commento deve utilizzare la codifica ASCII e sarà memorizzato di conseguenza.

Valore: Il commento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

