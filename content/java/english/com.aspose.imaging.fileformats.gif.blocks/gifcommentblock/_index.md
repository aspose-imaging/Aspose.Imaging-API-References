---
title: GifCommentBlock
second_title: Aspose.Imaging for Java API Reference
description: Gif comment block.
type: docs
weight: 11
url: /com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

Gif comment block.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | Initializes a new instance of the `GifCommentBlock` class. |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | Initializes a new instance of the `GifCommentBlock` class. |
## Fields

| Field | Description |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Gif comment block extension label. |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Defines the block header size. |
## Methods

| Method | Description |
| --- | --- |
| [getComment()](#getComment--) | Gets or sets the comment. |
| [setComment(String value)](#setComment-java.lang.String-) | Gets or sets the comment. |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


Initializes a new instance of the `GifCommentBlock` class.

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


Initializes a new instance of the `GifCommentBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | java.lang.String | The comment. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Gif comment block extension label.

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Defines the block header size.

### getComment() {#getComment--}
```
public String getComment()
```


Gets or sets the comment. Note that comment must use ASCII encoding and will be stored accordingly.

Value: The comment.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Gets or sets the comment. Note that comment must use ASCII encoding and will be stored accordingly.

Value: The comment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

