---
title: "فئة ImageMasking"
type: docs
weight: 90
url: /ar/python-net/aspose.imaging.masking/imagemasking/
---

**Summary:** Provides image masking operations

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.ImageMasking

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ImageMasking(source_image)](#ImageMasking_source_image_1) | يُهيئ نسخة جديدة من الفئة [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/) |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [apply_mask(target_image, mask, masking_options)](#apply_mask_target_image_mask_masking_options_1) | يطبق القناع على الصورة المصدر المحددة. |
| [create_session(options)](#create_session_options_2) | ينشئ جلسة القناع التي يمكنها تنفيذ عمليات فك التجميع لإعادة التدريب. |
| [decompose(options)](#decompose_options_3) | ينفذ عملية فك التجميع باستخدام خيارات القناع المحددة |
| [decompose_async(options)](#decompose_async_options_4) | ينشئ مهمة فك التجميع غير المتزامنة باستخدام خيارات القناع المحددة. |
| [load_session(file_path)](#load_session_file_path_5) | حمّل الجلسة من الملف المحدد. |
| [load_session(stream)](#load_session_stream_6) | حمّل الجلسة من الدفق المحدد. |
| [load_session_from_stream(stream)](#load_session_from_stream_stream_7) | حمّل الجلسة من الدفق المحدد. |


### Constructor: ImageMasking(source_image) {#ImageMasking_source_image_1}


```
 ImageMasking(source_image) 
```

يُهيئ نسخة جديدة من الفئة [ImageMasking](/imaging/python-net/aspose.imaging.masking/imagemasking/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة المصدر. |

### Method: apply_mask(target_image, mask, masking_options)  [static] {#apply_mask_target_image_mask_masking_options_1}


```
 apply_mask(target_image, mask, masking_options) 
```

يطبق القناع على الصورة المصدر المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| target_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | الصورة الهدف. |
| mask | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | صورة القناع للتطبيق. |
| masking_options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | خيارات القناع. |

### Method: create_session(options) {#create_session_options_2}


```
 create_session(options) 
```

ينشئ جلسة القناع التي يمكنها تنفيذ عمليات فك التجميع لإعادة التدريب.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | الخيارات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | جلسة القناع التي يمكنها تنفيذ عمليات فك التجميع لإعادة التدريب. |


### Method: decompose(options) {#decompose_options_3}


```
 decompose(options) 
```

ينفذ عملية فك التجميع باستخدام خيارات القناع المحددة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | خيارات القناع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | نتيجة عملية القناع كمصفوفة من مزودي صور القطاعات. |


### Method: decompose_async(options) {#decompose_async_options_4}


```
 decompose_async(options) 
```

ينشئ مهمة فك التجميع غير المتزامنة باستخدام خيارات القناع المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [MaskingOptions](/imaging/python-net/aspose.imaging.masking.options/maskingoptions/) | خيارات القناع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | مهمة فك التجميع غير المتزامنة |


### Method: load_session(file_path) {#load_session_file_path_5}


```
 load_session(file_path) 
```

حمّل الجلسة من الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | جلسة القناع التي يمكنها تنفيذ عمليات فك التجميع لإعادة التدريب. |


### Method: load_session(stream) {#load_session_stream_6}


```
 load_session(stream) 
```

حمّل الجلسة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | جلسة القناع التي يمكنها تنفيذ عمليات فك التجميع لإعادة التدريب. |


### Method: load_session_from_stream(stream) {#load_session_from_stream_stream_7}


```
 load_session_from_stream(stream) 
```

حمّل الجلسة من الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IMaskingSession](/imaging/python-net/aspose.imaging.masking/imaskingsession/) | جلسة القناع التي يمكنها تنفيذ عمليات فك التجميع لإعادة التدريب. |


