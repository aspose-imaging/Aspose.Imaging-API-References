---
title: "GifCommentBlock"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Bloc de commentaire Gif."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

Bloc de commentaire Gif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | Initialise une nouvelle instance de la classe `GifCommentBlock`. |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | Initialise une nouvelle instance de la classe `GifCommentBlock`. |
## Champs

| Champ | Description |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Étiquette d'extension du bloc de commentaire Gif. |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Définit la taille de l'en-tête du bloc. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getComment()](#getComment--) | Obtient ou définit le commentaire. |
| [setComment(String value)](#setComment-java.lang.String-) | Obtient ou définit le commentaire. |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


Initialise une nouvelle instance de la classe `GifCommentBlock`.

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


Initialise une nouvelle instance de la classe `GifCommentBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| comment | java.lang.String | Le commentaire. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Étiquette d'extension du bloc de commentaire Gif.

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Définit la taille de l'en-tête du bloc.

### getComment() {#getComment--}
```
public String getComment()
```


Obtient ou définit le commentaire. Notez que le commentaire doit utiliser l'encodage ASCII et sera stocké en conséquence.

Valeur : le commentaire.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Obtient ou définit le commentaire. Notez que le commentaire doit utiliser l'encodage ASCII et sera stocké en conséquence.

Valeur : le commentaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

