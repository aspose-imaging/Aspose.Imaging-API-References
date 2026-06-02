---
title: "GifCommentBlock"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gif yorum bloğu."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

Gif yorum bloğu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | Yeni bir `GifCommentBlock` sınıfı örneği başlatır. |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | Yeni bir `GifCommentBlock` sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Gif yorum bloğu uzantı etiketi. |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Blok başlık boyutunu tanımlar. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getComment()](#getComment--) | Yorumu alır veya ayarlar. |
| [setComment(String value)](#setComment-java.lang.String-) | Yorumu alır veya ayarlar. |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


Yeni bir `GifCommentBlock` sınıfı örneği başlatır.

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


Yeni bir `GifCommentBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comment | java.lang.String | Yorum. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Gif yorum bloğu uzantı etiketi.

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Blok başlık boyutunu tanımlar.

### getComment() {#getComment--}
```
public String getComment()
```


Yorumu alır veya ayarlar. Not: yorum ASCII kodlamasını kullanmalı ve buna göre depolanacaktır.

Değer: Yorum.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Yorumu alır veya ayarlar. Not: yorum ASCII kodlamasını kullanmalı ve buna göre depolanacaktır.

Değer: Yorum.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

