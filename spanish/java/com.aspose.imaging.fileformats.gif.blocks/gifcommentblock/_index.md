---
title: "GifCommentBlock"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Bloque de comentario Gif."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

Bloque de comentario Gif.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | Inicializa una nueva instancia de la clase `GifCommentBlock`. |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | Inicializa una nueva instancia de la clase `GifCommentBlock`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etiqueta de extensión del bloque de comentario Gif. |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Define el tamaño del encabezado del bloque. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getComment()](#getComment--) | Obtiene o establece el comentario. |
| [setComment(String value)](#setComment-java.lang.String-) | Obtiene o establece el comentario. |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


Inicializa una nueva instancia de la clase `GifCommentBlock`.

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


Inicializa una nueva instancia de la clase `GifCommentBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comment | java.lang.String | El comentario. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Etiqueta de extensión del bloque de comentario Gif.

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Define el tamaño del encabezado del bloque.

### getComment() {#getComment--}
```
public String getComment()
```


Obtiene o establece el comentario. Tenga en cuenta que el comentario debe usar codificación ASCII y se almacenará en consecuencia.

Valor: El comentario.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Obtiene o establece el comentario. Tenga en cuenta que el comentario debe usar codificación ASCII y se almacenará en consecuencia.

Valor: El comentario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

