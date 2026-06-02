---
title: "GifGraphicsControlBlock فئة"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | ينشئ مثيلاً جديداً من الفئة [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | ينشئ مثيلاً جديداً من الفئة [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | ينشئ مثيلاً جديداً من الفئة [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | يحدد حجم رأس الكتلة. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | مُدخل الامتداد. |
| EXTENSION_LABEL [static] | System.Byte | r | تسمية الامتداد. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | يحصل على حجم الكتلة الفرعية. |
| delay_time | int | r/w | يحصل أو يضبط زمن تأخير الإطار معبرًا عنه بالجزء من مئة ثانية. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | يحصل أو يعيّن طريقة التخلص. |
| العلامات | System.Byte | r/w | يحصل أو يضبط العلامات. |
| has_transparent_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان كتلة التحكم الرسومية تحتوي على لون شفاف. |
| is_changed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الكتلة قد تغيرت وتحتاج إلى حفظ. |
| transparent_color_index | System.Byte | r/w | يحصل أو يضبط فهرس اللون الشفاف. |
| user_input_expected | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان إدخال المستخدم متوقعًا. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | ينشئ العلامات. |
| [save(stream)](#save_stream_2) | يحفظ الكتلة إلى الدفق المحدد. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

ينشئ مثيلاً جديداً من الفئة [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

ينشئ مثيلاً جديداً من الفئة [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| delay_time | int | وقت التأخير معبرًا عنه بوحدات 1/100 ثانية. |
| has_transparent_color | bool | إذا تم تعيينه إلى <c>true</c> فإن _transparentColorIndex_ صالح. |
| transparent_color_index | System.Byte | فهرس اللون الشفاف. |
| requires_user_input | bool | إذا تم تعيينه إلى <c>true</c> فإن إدخال المستخدم متوقع. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | طريقة التخلص. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

ينشئ مثيلاً جديداً من الفئة [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| العلامات | System.Byte | الأعلام. |
| delay_time | int | وقت التأخير معبرًا عنه بوحدات 1/100 ثانية. |
| transparent_color_index | System.Byte | فهرس اللون الشفاف. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

ينشئ العلامات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| has_transparent_color | bool | إذا تم تعيينه إلى <c>true</c> فإن [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) يحتوي على فهرس لون شفاف صالح. |
| requires_user_input | bool | إذا تم تعيينه إلى <c>true</c> فإن إدخال المستخدم متوقع. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | طريقة التخلص. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | الأعلام المُولَّدة. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

يحفظ الكتلة إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ البيانات فيه. |

