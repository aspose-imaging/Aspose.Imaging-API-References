---
title: "فئة IMatchingAsyncTask"
type: docs
weight: 60
url: /ar/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_busy | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة تعمل حاليًا. |
| is_canceled | bool | r | يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة. |
| is_faulted | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد حدث فيها خطأ. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| abort() | يلغي هذه المهمة.<br/>            تُكمل المهمة فورًا، مع خطر عدم تحرير الموارد غير المُدارة الداخلية. |
| cancel() | يلغي هذه المهمة.<br/>            تُكمل المهمة بأمان عبر إيقاف الخوارزمية بشكل مُتحكم. |
| [get_error()](#get_error__1) | يرجع خطأً في عملية القناع |
| [get_masking_result()](#get_masking_result__2) | يرجع نتيجة عملية القناع |
| run_async() | يشغّل هذه المهمة. |
| wait_on_done() | ينتظر حتى تنتهي المهمة. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

يرجع خطأً في عملية القناع

**Returns**

| نوع | الوصف |
| :- | :- |
| string | خطأ المهمة. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

يرجع نتيجة عملية القناع

**Returns**

| نوع | الوصف |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | نتيجة هذه المهمة. |


