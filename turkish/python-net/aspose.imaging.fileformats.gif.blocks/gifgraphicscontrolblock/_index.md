---
title: "GifGraphicsControlBlock Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Yeni bir [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) sınıfı örneği başlatır. |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Yeni bir [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) sınıfı örneği başlatır. |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Yeni bir [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Blok başlık boyutunu belirtir. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Uzantı tanıtıcı. |
| EXTENSION_LABEL [static] | System.Byte | r | Uzantı etiketi. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Alt blok boyutunu alır. |
| delay_time | int | r/w | Kare gecikme süresini 1/100 saniye cinsinden alır veya ayarlar. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | İmha yöntemini alır veya ayarlar. |
| flags | System.Byte | r/w | Bayrakları alır veya ayarlar. |
| has_transparent_color | bool | r/w | Grafik kontrol bloğunun şeffaf renk içerip içermediğini gösteren değeri alır veya ayarlar. |
| is_changed | bool | r/w | Blok değişti ve kaydedilmesi gerekiyor mu gösteren bir değeri alır veya ayarlar. |
| transparent_color_index | System.Byte | r/w | Şeffaf renk indeksini alır veya ayarlar. |
| user_input_expected | bool | r/w | Kullanıcı girdisinin beklendiğini gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Bayrakları oluşturur. |
| [save(stream)](#save_stream_2) | Bloğu belirtilen akışa kaydeder. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Yeni bir [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) sınıfı örneği başlatır.

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Yeni bir [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| delay_time | int | Gecikme süresi, 1/100 saniye cinsinden ifade edilir. |
| has_transparent_color | bool | eğer <c>true</c> olarak ayarlanırsa _transparentColorIndex_ geçerlidir. |
| transparent_color_index | System.Byte | Şeffaf renk indeksi. |
| requires_user_input | bool | eğer <c>true</c> olarak ayarlanırsa kullanıcı girişi beklenir. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | İmha yöntemi. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Yeni bir [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| flags | System.Byte | Bayraklar. |
| delay_time | int | Gecikme süresi, 1/100 saniye cinsinden ifade edilir. |
| transparent_color_index | System.Byte | Şeffaf renk indeksi. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Bayrakları oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| has_transparent_color | bool | eğer <c>true</c> olarak ayarlanırsa [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) geçerli şeffaf renk indeksine sahiptir. |
| requires_user_input | bool | eğer <c>true</c> olarak ayarlanırsa kullanıcı girişi beklenir. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | İmha yöntemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Byte | Oluşturulan bayraklar. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Bloğu belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Verinin kaydedileceği akış. |

