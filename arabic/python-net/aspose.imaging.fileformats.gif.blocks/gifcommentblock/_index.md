---
title: "فئة GifCommentBlock"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | ينشئ مثيلًا جديدًا من الفئة [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | ينشئ مثيلًا جديدًا من الفئة [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | يحدد حجم رأس الكتلة. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | مُدخل الامتداد. |
| EXTENSION_LABEL [static] | System.Byte | r | تسمية امتداد كتلة تعليق Gif. |
| تعليق | string | r/w | يحصل أو يعيّن التعليق. لاحظ أن التعليق يجب أن يستخدم ترميز ASCII وسيتم تخزينه وفقًا لذلك. |
| is_changed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الكتلة قد تغيرت وتحتاج إلى حفظ. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ الكتلة إلى الدفق المحدد. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

ينشئ مثيلًا جديدًا من الفئة [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

ينشئ مثيلًا جديدًا من الفئة [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| تعليق | string | التعليق. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ الكتلة إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ البيانات فيه. |

