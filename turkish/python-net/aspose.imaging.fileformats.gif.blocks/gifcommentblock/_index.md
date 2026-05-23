---
title: "GifCommentBlock Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---

**Summary:** Gif comment block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifCommentBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GifCommentBlock()](#GifCommentBlock__1) | Yeni bir [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) sınıfı örneği başlatır. |
| [GifCommentBlock(comment)](#GifCommentBlock_comment_2) | Yeni bir [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Blok başlık boyutunu tanımlar. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Uzantı tanıtıcı. |
| EXTENSION_LABEL [static] | System.Byte | r | Gif yorum bloğu uzantı etiketi. |
| yorum | string | r/w | Yorumu alır veya ayarlar. Yorumun ASCII kodlaması kullanması gerektiğini ve buna göre saklanacağını unutmayın. |
| is_changed | bool | r/w | Blok değişti ve kaydedilmesi gerekiyor mu gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Bloğu belirtilen akışa kaydeder. |


### Constructor: GifCommentBlock() {#GifCommentBlock__1}


```
 GifCommentBlock() 
```

Yeni bir [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) sınıfı örneği başlatır.

### Constructor: GifCommentBlock(comment) {#GifCommentBlock_comment_2}


```
 GifCommentBlock(comment) 
```

Yeni bir [GifCommentBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifcommentblock/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yorum | string | Yorum. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Bloğu belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Verinin kaydedileceği akış. |

