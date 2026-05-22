---
title: "فئة GifUnknownExtensionBlock"
type: docs
weight: 60
url: /ar/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/
---

**Summary:** Gif Unknown Extension Block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifUnknownExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GifUnknownExtensionBlock()](#GifUnknownExtensionBlock__1) | ينشئ مثلاً جديداً من الفئة [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
| [GifUnknownExtensionBlock(extension_label, data)](#GifUnknownExtensionBlock_extension_label_data_2) | ينشئ مثلاً جديداً من الفئة [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| EXTENSION_INTRODUCER [static] | System.Byte | r | مُدخل الامتداد. |
| extension_label | System.Byte | r/w | يحصل أو يعيّن تسمية امتداد الكتلة. |
| is_changed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الكتلة قد تغيرت وتحتاج إلى حفظ. |
| unknown_data | System.Byte | r/w | يحصل أو يعيّن البيانات غير المعروفة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ الكتلة إلى الدفق المحدد. |


### Constructor: GifUnknownExtensionBlock() {#GifUnknownExtensionBlock__1}


```
 GifUnknownExtensionBlock() 
```

ينشئ مثلاً جديداً من الفئة [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

### Constructor: GifUnknownExtensionBlock(extension_label, data) {#GifUnknownExtensionBlock_extension_label_data_2}


```
 GifUnknownExtensionBlock(extension_label, data) 
```

ينشئ مثلاً جديداً من الفئة [GifUnknownExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifunknownextensionblock/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| extension_label | System.Byte | تسمية الامتداد. |
| البيانات | System.Byte | بيانات الكتلة. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ الكتلة إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ البيانات فيه. |

