---
title: "Classe IAsyncTaskState"
type: docs
weight: 40
url: /fr/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Obtient une valeur indiquant si la tâche asynchrone est annulée. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Obtient la progression de la tâche asynchrone. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | Incrémente la valeur maximale de la progression. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Définit la progression de la tâche asynchrone. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

Incrémente la valeur maximale de la progression.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| value | int | La valeur d'augmentation. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Définit la progression de la tâche asynchrone.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | L'état de la progression. |

