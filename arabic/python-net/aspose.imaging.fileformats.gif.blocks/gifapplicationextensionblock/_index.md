---
title: "GifApplicationExtensionBlock فئة"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/
---

**Summary:** Gif application extension block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifApplicationExtensionBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GifApplicationExtensionBlock()](#GifApplicationExtensionBlock__1) | ينشئ مثالا جديدًا من الفئة [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
| [GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data)](#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2) | ينشئ مثالا جديدًا من الفئة [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| APPLICATION_AUTHENTICATION_CODE_SIZE [static] | int | r | يحدد حجم رمز المصادقة للتطبيق. |
| APPLICATION_IDENTIFIER_SIZE [static] | int | r | يحدد حجم معرف التطبيق. |
| BLOCK_HEADER_SIZE [static] | int | r | يحدد حجم رأس الكتلة. |
| BLOCK_SIZE [static] | System.Byte | r | حجم اسم الامتداد + كتلة الإصدار |
| EXTENSION_INTRODUCER [static] | System.Byte | r | مُدخل الامتداد. |
| EXTENSION_LABEL [static] | System.Byte | r | تسمية الامتداد. |
| application_authentication_code | System.Byte | r/w | يحصل أو يضبط رمز المصادقة للتطبيق. |
| application_data | System.Byte | r/w | يحصل أو يضبط بيانات التطبيق. |
| application_identifier | string | r/w | يحصل أو يضبط معرف التطبيق. |
| is_changed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الكتلة قد تغيرت وتحتاج إلى حفظ. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ الكتلة إلى الدفق المحدد. |


### Constructor: GifApplicationExtensionBlock() {#GifApplicationExtensionBlock__1}


```
 GifApplicationExtensionBlock() 
```

ينشئ مثالا جديدًا من الفئة [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

### Constructor: GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) {#GifApplicationExtensionBlock_application_identifier_application_authentication_code_application_data_2}


```
 GifApplicationExtensionBlock(application_identifier, application_authentication_code, application_data) 
```

ينشئ مثالا جديدًا من الفئة [GifApplicationExtensionBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifapplicationextensionblock/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| application_identifier | string | معرف التطبيق. |
| application_authentication_code | System.Byte | رمز المصادقة للتطبيق. |
| application_data | System.Byte | بيانات التطبيق. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ الكتلة إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق لحفظ البيانات فيه. |

