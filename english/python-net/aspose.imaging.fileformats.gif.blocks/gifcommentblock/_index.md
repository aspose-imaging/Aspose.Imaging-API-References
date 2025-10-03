---
title: GifCommentBlock Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class. |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Defines the block header size. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Extension introducer. |
| EXTENSION_LABEL [static] | System.Byte | r | Gif comment block extension label. |
| comment | string | r/w | Gets or sets the comment. Note that comment must use ASCII encoding and will be stored accordingly. |
| is_changed | bool | r/w | Gets or sets a value indicating whether block has changed and requires save. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the block to the specified stream. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class.

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Initializes a new instance of the [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| comment | string | The comment. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

