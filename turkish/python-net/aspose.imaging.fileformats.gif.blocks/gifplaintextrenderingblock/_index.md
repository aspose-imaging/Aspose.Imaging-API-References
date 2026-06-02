---
title: "GifPlainTextRenderingBlock Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | Yeni bir [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) sınıfı örneği başlatır. |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | Yeni bir [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | Toplam blok boyutu. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Uzantı tanıtıcı. |
| EXTENSION_LABEL [static] | System.Byte | r | Düz metin uzantı etiketi. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Alt bloğun boyutu. |
| character_cell_height | System.Byte | r/w | Izgaradaki her hücrenin piksel cinsinden karakter hücresi yüksekliğini alır veya ayarlar. |
| character_cell_width | System.Byte | r/w | Izgaradaki her hücrenin piksel cinsinden karakter hücresi genişliğini alır veya ayarlar. |
| is_changed | bool | r/w | Blok değişti ve kaydedilmesi gerekiyor mu gösteren bir değeri alır veya ayarlar. |
| plain_text_data | System.Byte | r/w | Düz metin verisini alır veya ayarlar. |
| text_background_color_index | System.Byte | r/w | Metin arka planını çizmeye kullanılan küresel renk paletindeki rengin indeksini alır veya ayarlar. |
| text_foreground_color_index | System.Byte | r/w | Metin ön planını çizmeye kullanılan küresel renk paletindeki rengin indeksini alır veya ayarlar. |
| text_grid_height | int | r/w | Metin ızgarasının yüksekliğini piksel cinsinden alır veya ayarlar |
| text_grid_left_position | int | r/w | Metin ızgarasının sol konumunu alır veya ayarlar. |
| text_grid_top_position | int | r/w | Metin ızgarasının üst konumunu alır veya ayarlar. |
| text_grid_width | int | r/w | Metin ızgarasının genişliğini piksel cinsinden alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream)](#save_stream_1) | Bloğu belirtilen akışa kaydeder. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

Yeni bir [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) sınıfı örneği başlatır.

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

Yeni bir [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| text_grid_left_position | int | Metin ızgarasının sol konumu. |
| text_grid_top_position | int | Metin ızgarasının üst konumu. |
| text_grid_width | int | Metin ızgarasının genişliği. |
| text_grid_height | int | Metin ızgarasının yüksekliği. |
| character_cell_width | System.Byte | Karakter hücresinin genişliği. |
| character_cell_height | System.Byte | Karakter hücresinin yüksekliği. |
| text_foreground_color_index | System.Byte | Ön plan renk indeksi. |
| text_background_color_index | System.Byte | Arka plan renk indeksi. |
| veri | System.Byte | Düz metin verisi. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Bloğu belirtilen akışa kaydeder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Verinin kaydedileceği akış. |

