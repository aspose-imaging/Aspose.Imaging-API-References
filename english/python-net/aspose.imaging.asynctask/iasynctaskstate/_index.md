---
title: IAsyncTaskState Class
type: docs
weight: 40
url: /python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Gets a value indicating whether the asynchronous task is canceled. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Gets the progress of the asynchronous task. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | Increments the progress maximum value. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Sets the progress of the asynchronous task. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

Increments the progress maximum value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | int | The increase value. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Sets the progress of the asynchronous task.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | The progress state. |

