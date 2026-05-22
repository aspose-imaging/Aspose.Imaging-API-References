---
title: "فئة IAsyncTaskState"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_canceled | bool | r | يحصل على قيمة تشير إلى ما إذا كانت المهمة غير المتزامنة ملغاة. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | يحصل على تقدم المهمة غير المتزامنة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | يزيد من قيمة الحد الأقصى للتقدم. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | يضبط تقدم المهمة غير المتزامنة. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

يزيد من قيمة الحد الأقصى للتقدم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | int | قيمة الزيادة. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

يضبط تقدم المهمة غير المتزامنة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | حالة التقدم. |

