---
title: "Класс IAsyncTaskState"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Получает значение, указывающее, отменена ли асинхронная задача. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Получает прогресс асинхронной задачи. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | Увеличивает максимальное значение прогресса. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Устанавливает прогресс асинхронной задачи. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

Увеличивает максимальное значение прогресса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | int | Значение увеличения. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Устанавливает прогресс асинхронной задачи.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | Состояние прогресса. |

