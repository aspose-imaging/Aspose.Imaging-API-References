---
title: "فئة IMaskingSession"
type: docs
weight: 80
url: /ar/python-net/aspose.imaging.masking/imaskingsession/
---

**Summary:** The masking session

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingSession

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [decompose()](#decompose__1) | ينفّذ العملية الأولى للتفكيك التقريبي |
| [decompose_async()](#decompose_async__2) | ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ العملية الأولى للتفكيك التقريبي |
| [improve_decomposition(masking_arguments)](#improve_decomposition_masking_arguments_3) | ينفذ عملية فك التجميع لإعادة التدريب |
| [improve_decomposition_async(masking_arguments)](#improve_decomposition_async_masking_arguments_4) | ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ عملية فك التجميع لإعادة التدريب |
| [save(file_path)](#save_file_path_5) | يحفظ حالة الجلسة إلى الملف المحدد. |
| [save(stream)](#save_stream_6) | احفظ حالة الجلسة إلى الدفق المحدد. |


### Method: decompose() {#decompose__1}


```
 decompose() 
```

ينفّذ العملية الأولى للتفكيك التقريبي

**Returns**

| نوع | الوصف |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | نتيجة عملية القناع كمصفوفة من مزودي صور القطاعات. |


### Method: decompose_async() {#decompose_async__2}


```
 decompose_async() 
```

ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ العملية الأولى للتفكيك التقريبي

**Returns**

| نوع | الوصف |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | مهمة فك التجميع غير المتزامنة |


### Method: improve_decomposition(masking_arguments) {#improve_decomposition_masking_arguments_3}


```
 improve_decomposition(masking_arguments) 
```

ينفذ عملية فك التجميع لإعادة التدريب

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | معاملات القناع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | نتيجة عملية القناع كمصفوفة من مزودي صور القطاعات. |


### Method: improve_decomposition_async(masking_arguments) {#improve_decomposition_async_masking_arguments_4}


```
 improve_decomposition_async(masking_arguments) 
```

ينشئ المهمة غير المتزامنة التي يمكنها تنفيذ عملية فك التجميع لإعادة التدريب

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| masking_arguments | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs/) | معاملات القناع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IMaskingAsyncTask](/imaging/python-net/aspose.imaging.masking/imaskingasynctask/) | مهمة فك التجميع غير المتزامنة |


### Method: save(file_path) {#save_file_path_5}


```
 save(file_path) 
```

يحفظ حالة الجلسة إلى الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

احفظ حالة الجلسة إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | الدفق. |

