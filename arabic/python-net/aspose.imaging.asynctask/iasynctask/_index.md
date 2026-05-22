---
title: "فئة IAsyncTask"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_busy | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة تعمل حاليًا. |
| is_canceled | bool | r | يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة. |
| is_faulted | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد حدث فيها خطأ. |
| result | System.Object | r | يحصل على نتيجة هذه المهمة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| abort() | يلغي هذه المهمة.<br/>            تُكمل المهمة فورًا، مع خطر عدم تحرير الموارد غير المُدارة الداخلية. |
| cancel() | يلغي هذه المهمة.<br/>            تُكمل المهمة بأمان عبر إيقاف الخوارزمية بشكل مُتحكم. |
| run_async() | يشغّل هذه المهمة. |
| wait_on_done() | ينتظر حتى تنتهي المهمة. |


