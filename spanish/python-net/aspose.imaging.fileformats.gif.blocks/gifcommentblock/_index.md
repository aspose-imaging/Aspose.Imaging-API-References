---
title: "GifCommentBlock Clase"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Inicializa una nueva instancia de la clase [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Inicializa una nueva instancia de la clase [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Define el tamaño del encabezado del bloque. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introducción de extensión. |
| EXTENSION_LABEL [static] | System.Byte | r | Etiqueta de extensión del bloque de comentario Gif. |
| comentario | string | r/w | Obtiene o establece el comentario. Tenga en cuenta que el comentario debe usar codificación ASCII y se almacenará en consecuencia. |
| is_changed | bool | r/w | Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda el bloque en el flujo especificado. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Inicializa una nueva instancia de la clase [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Inicializa una nueva instancia de la clase [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| comentario | string | El comentario. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo donde guardar los datos. |

