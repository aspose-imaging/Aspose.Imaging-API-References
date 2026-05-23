---
title: "IAsyncTaskState Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Asenkron görevin iptal edilip edilmediğini gösteren bir değeri alır. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Asenkron görevin ilerlemesini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | İlerleme maksimum değerini artırır. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Asenkron görevin ilerlemesini ayarlar. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

İlerleme maksimum değerini artırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | int | Artış değeri. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Asenkron görevin ilerlemesini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | İlerleme durumu. |

