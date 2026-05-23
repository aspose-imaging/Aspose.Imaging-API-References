---
title: "Класс GifCommentBlock"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Инициализирует новый экземпляр класса [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Инициализирует новый экземпляр класса [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Определяет размер заголовка блока. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Ввод расширения. |
| EXTENSION_LABEL [static] | System.Byte | r | Метка расширения блока комментария Gif. |
| comment | string | r/w | Получает или задает комментарий. Обратите внимание, что комментарий должен использовать кодировку ASCII и будет сохранён соответственно. |
| is_changed | bool | r/w | Получает или задает значение, указывающее, изменён ли блок и требует ли сохранения. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет блок в указанный поток. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Инициализирует новый экземпляр класса [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Инициализирует новый экземпляр класса [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| comment | string | Комментарий. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет блок в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | The stream to save data to. |

