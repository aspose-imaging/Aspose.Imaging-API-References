---
title: "GifCommentBlock"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كتلة تعليق Gif."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

كتلة تعليق Gif.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | ينشئ مثيلًا جديدًا من الفئة `GifCommentBlock`. |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة `GifCommentBlock`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | تسمية امتداد كتلة تعليق GIF. |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | يحدد حجم رأس الكتلة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getComment()](#getComment--) | يحصل أو يضبط التعليق. |
| [setComment(String value)](#setComment-java.lang.String-) | يحصل أو يضبط التعليق. |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


ينشئ مثيلًا جديدًا من الفئة `GifCommentBlock`.

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


ينشئ مثيلًا جديدًا من الفئة `GifCommentBlock`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تعليق | java.lang.String | التعليق. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


تسمية امتداد كتلة تعليق GIF.

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


يحدد حجم رأس الكتلة.

### getComment() {#getComment--}
```
public String getComment()
```


يحصل أو يضبط التعليق. لاحظ أن التعليق يجب أن يستخدم ترميز ASCII وسيتم تخزينه وفقًا لذلك.

القيمة: التعليق.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


يحصل أو يضبط التعليق. لاحظ أن التعليق يجب أن يستخدم ترميز ASCII وسيتم تخزينه وفقًا لذلك.

القيمة: التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

