---
title: "Clase IAsyncTaskState"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Obtiene un valor que indica si la tarea asíncrona está cancelada. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Obtiene el progreso de la tarea asíncrona. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | Incrementa el valor máximo del progreso. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Establece el progreso de la tarea asíncrona. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

Incrementa el valor máximo del progreso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valor | int | El valor de incremento. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Establece el progreso de la tarea asíncrona.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | El estado del progreso. |

