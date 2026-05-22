---
title: "فئة GifPlainTextRenderingBlock"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---

**Summary:** Gif plain text extension block. The plain text extension contains textual data and the<br/>            parameters necessary to render that data as a graphic, in a simple form.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifPlainTextRenderingBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock__1) | ينشئ مثلاً جديداً من الفئة [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
| [GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data)](#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2) | ينشئ مثلاً جديداً من الفئة [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| BLOCK_SIZE [static] | System.Byte | r | الحجم الكلي للكتلة. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | مُدخل الامتداد. |
| EXTENSION_LABEL [static] | System.Byte | r | تسمية امتداد النص العادي. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | حجم الكتلة الفرعية. |
| character_cell_height | System.Byte | r/w | يحصل أو يعيّن ارتفاع خلية الحرف، بالبكسل، لكل خلية في الشبكة. |
| character_cell_width | System.Byte | r/w | يحصل أو يعيّن عرض خلية الحرف، بالبكسل، لكل خلية في الشبكة. |
| is_changed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الكتلة قد تغيرت وتحتاج إلى حفظ. |
| plain_text_data | System.Byte | r/w | يحصل أو يعيّن بيانات النص العادي. |
| text_background_color_index | System.Byte | r/w | يحصل أو يعيّن فهرس اللون في لوحة الألوان العامة المستخدمة لرسم خلفية النص. |
| text_foreground_color_index | System.Byte | r/w | يحصل أو يعيّن فهرس اللون في لوحة الألوان العامة المستخدمة لرسم مقدمة النص. |
| text_grid_height | int | r/w | يحصل أو يضبط ارتفاع شبكة النص بالبكسل |
| text_grid_left_position | int | r/w | يحصل أو يضبط موضع شبكة النص الأيسر. |
| text_grid_top_position | int | r/w | يحصل أو يضبط موضع شبكة النص العلوي. |
| text_grid_width | int | r/w | يحصل أو يضبط عرض شبكة النص بالبكسل |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ الكتلة إلى الدفق المحدد. |


### Constructor: GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock__1}


```
 GifPlainTextRenderingBlock() 
```

ينشئ مثلاً جديداً من الفئة [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

### Constructor: GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) {#GifPlainTextRenderingBlock_text_grid_left_position_text_grid_top_position_text_grid_width_text_grid_height_character_cell_width_character_cell_height_text_foreground_color_index_text_background_color_index_data_2}


```
 GifPlainTextRenderingBlock(text_grid_left_position, text_grid_top_position, text_grid_width, text_grid_height, character_cell_width, character_cell_height, text_foreground_color_index, text_background_color_index, data) 
```

ينشئ مثلاً جديداً من الفئة [GifPlainTextRenderingBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| text_grid_left_position | int | موضع شبكة النص الأيسر. |
| text_grid_top_position | int | موضع شبكة النص العلوي. |
| text_grid_width | int | عرض شبكة النص. |
| text_grid_height | int | ارتفاع شبكة النص. |
| character_cell_width | System.Byte | عرض خلية الحرف. |
| character_cell_height | System.Byte | ارتفاع خلية الحرف. |
| text_foreground_color_index | System.Byte | فهرس لون المقدمة. |
| text_background_color_index | System.Byte | فهرس لون الخلفية. |
| البيانات | System.Byte | بيانات النص العادي. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ الكتلة إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ البيانات فيه. |

