---
title: "GifCommentBlock 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | 初始化 [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) 类的新实例。 |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | 初始化 [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | 定义块头部大小。 |
| EXTENSION_INTRODUCER [static] | System.Byte | r | 扩展引入器。 |
| EXTENSION_LABEL [static] | System.Byte | r | Gif 注释块扩展标签。 |
| 评论 | string | r/w | 获取或设置注释。请注意，注释必须使用 ASCII 编码，并将相应存储。 |
| is_changed | bool | r/w | 获取或设置一个值，指示块是否已更改并需要保存。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [save(stream)](#save_stream_1) | 将块保存到指定的流。 |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

初始化 [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) 类的新实例。

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

初始化 [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 评论 | string | 评论。 |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

将块保存到指定的流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存数据的流。 |

