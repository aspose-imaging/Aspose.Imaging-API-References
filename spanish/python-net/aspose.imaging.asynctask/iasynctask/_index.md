---
title: "Clase IAsyncTask"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_busy | bool | r | Obtiene un valor que indica si esta tarea se está ejecutando actualmente. |
| is_canceled | bool | r | Obtiene un valor que indica si esta tarea fue cancelada. |
| is_faulted | bool | r | Obtiene un valor que indica si esta tarea falló. |
| result | System.Object | r | Obtiene el resultado de esta tarea. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| abort() | Aborta esta tarea.<br/>            La tarea se completa inmediatamente, con el riesgo de no liberar recursos internos no administrados. |
| cancel() | Cancela esta tarea.<br/>            La tarea se completa de forma segura mediante la detención controlada del algoritmo. |
| run_async() | Ejecuta esta tarea. |
| wait_on_done() | Espera hasta que la tarea termine. |


