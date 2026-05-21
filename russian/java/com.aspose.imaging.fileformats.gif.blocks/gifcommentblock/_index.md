---
title: "GifCommentBlock"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Блок комментария Gif."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

Блок комментария Gif.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | Инициализирует новый экземпляр класса `GifCommentBlock`. |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | Инициализирует новый экземпляр класса `GifCommentBlock`. |
## Поля

| Поле | Описание |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Метка расширения блока комментариев GIF. |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Определяет размер заголовка блока. |
## Методы

| Метод | Описание |
| --- | --- |
| [getComment()](#getComment--) | Получает или задает комментарий. |
| [setComment(String value)](#setComment-java.lang.String-) | Получает или задает комментарий. |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


Инициализирует новый экземпляр класса `GifCommentBlock`.

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


Инициализирует новый экземпляр класса `GifCommentBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| comment | java.lang.String | Комментарий. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Метка расширения блока комментариев GIF.

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Определяет размер заголовка блока.

### getComment() {#getComment--}
```
public String getComment()
```


Получает или задает комментарий. Обратите внимание, что комментарий должен использовать ASCII‑кодировку и будет сохранён соответственно.

Значение: Комментарий.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Получает или задает комментарий. Обратите внимание, что комментарий должен использовать ASCII‑кодировку и будет сохранён соответственно.

Значение: Комментарий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

