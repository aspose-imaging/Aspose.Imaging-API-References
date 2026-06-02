---
title: "IAsyncTaskState-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Hämtar ett värde som indikerar om den asynkrona uppgiften är avbruten. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Hämtar framstegen för den asynkrona uppgiften. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | Ökar det maximala värdet för framsteg. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Anger framstegen för den asynkrona uppgiften. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

Ökar det maximala värdet för framsteg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | int | Ökningsvärdet. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Anger framstegen för den asynkrona uppgiften.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | Framstegstillståndet. |

