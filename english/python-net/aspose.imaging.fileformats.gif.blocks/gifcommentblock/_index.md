---
title: GifCommentBlock Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

**Aspose.Imaging Version:** 23.6

The GifCommentBlock type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__0) | Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class. |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_1) | Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
| EXTENSION_INTRODUCER [static] | byte | r | Extension introducer. |
| comment | string | r/w | Gets or sets the comment. Note that comment must use ASCII encoding and will be stored accordingly. |
| EXTENSION_LABEL [static] | byte | r | Gif comment block extension label. |
| BLOCK_HEADER_SIZE [static] | int | r | Defines the block header size. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_2) | Saves the block to the specified stream. |

### GifCommentBlock() {#GifCommentBlock__0}


```
 GifCommentBlock() 
```

Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class.

### GifCommentBlock(comment) {#GifCommentBlock_comment_1}


```
 GifCommentBlock(comment) 
```

Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| comment | string | The comment. |

### save(stream) {#save_stream_2}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

