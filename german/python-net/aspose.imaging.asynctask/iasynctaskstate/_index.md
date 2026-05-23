---
title: "IAsyncTaskState Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.asynctask/iasynctaskstate/
---

**Summary:** Provides access to the state of the asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTaskState

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_canceled | bool | r | Ruft einen Wert ab, der angibt, ob die asynchrone Aufgabe abgebrochen wurde. |
| progress | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | r | Ruft den Fortschritt der asynchronen Aufgabe ab. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [increment_progress_max_value(value)](#increment_progress_max_value_value_1) | Erhöht den maximalen Fortschrittswert. |
| [indicate_progress(event_type)](#indicate_progress_event_type_2) | Setzt den Fortschritt der asynchronen Aufgabe. |


### Method: increment_progress_max_value(value) {#increment_progress_max_value_value_1}


```
 increment_progress_max_value(value) 
```

Erhöht den maximalen Fortschrittswert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | int | Der Erhöhungswert. |

### Method: indicate_progress(event_type) {#indicate_progress_event_type_2}


```
 indicate_progress(event_type) 
```

Setzt den Fortschritt der asynchronen Aufgabe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| event_type | [EventType](/imaging/python-net/aspose.imaging.progressmanagement/eventtype/) | Der Fortschrittsstatus. |

