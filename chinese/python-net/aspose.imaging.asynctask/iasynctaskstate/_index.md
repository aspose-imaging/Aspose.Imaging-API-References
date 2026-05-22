---
title: "IAsyncTaskState 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| is_canceled | bool | r | 获取一个值，指示异步任务是否已取消。 |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | 获取异步任务的进度。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | 递增进度的最大值。 |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | 设置异步任务的进度。 |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

递增进度的最大值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | int | 增加值。 |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

设置异步任务的进度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | 进度状态。 |

