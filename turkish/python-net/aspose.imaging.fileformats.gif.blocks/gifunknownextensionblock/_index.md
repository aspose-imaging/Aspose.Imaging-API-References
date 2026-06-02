---
title: "GifUnknownExtensionBlock Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

**Summary:** Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__1) | Yeni bir [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) sınıfı örneği başlatır. |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_2) | Yeni bir [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Uzantı tanıtıcı. |
| extension_label | System.Byte | r/w | Bloğun uzantı etiketini alır veya ayarlar. |
| is_changed | bool | r/w | Blok değişti ve kaydedilmesi gerekiyor mu gösteren bir değeri alır veya ayarlar. |
| unknown_data | System.Byte | r/w | Bilinmeyen veriyi alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Bloğu belirtilen akışa kaydeder. |


### Constructor: GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__1}


```
 GifUnknownExtensionBlock() 
```

Yeni bir [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) sınıfı örneği başlatır.

### Constructor: GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_2}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

Yeni bir [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| extension_label | System.Byte | Uzantı etiketi. |
| veri | System.Byte | Blok verisi. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Bloğu belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Verinin kaydedileceği akış. |

