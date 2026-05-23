---
title: "Classe IAsyncTaskState"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Restituisce un valore che indica se l'attività asincrona è annullata. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Restituisce l'avanzamento dell'attività asincrona. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | Incrementa il valore massimo dell'avanzamento. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Imposta l'avanzamento dell'attività asincrona. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

Incrementa il valore massimo dell'avanzamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | int | Il valore di incremento. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Imposta l'avanzamento dell'attività asincrona.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | Lo stato di avanzamento. |

