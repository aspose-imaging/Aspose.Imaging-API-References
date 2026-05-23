---
title: "Clase IMaskingAsyncTask"
type: docs
weight: 60
url: /es/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_busy | bool | r | Obtiene un valor que indica si esta tarea se está ejecutando actualmente. |
| is_canceled | bool | r | Obtiene un valor que indica si esta tarea fue cancelada. |
| is_faulted | bool | r | Obtiene un valor que indica si esta tarea falló. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| abort() | Aborta esta tarea.<br/>            La tarea se completa inmediatamente, con el riesgo de no liberar recursos internos no administrados. |
| cancel() | Cancela esta tarea.<br/>            La tarea se completa de forma segura mediante la detención controlada del algoritmo. |
| [get_error()](#get_error__1) | Devuelve un error de la operación de enmascarado |
| [get_masking_result()](#get_masking_result__2) | Devuelve el resultado de la operación de enmascarado |
| run_async() | Ejecuta esta tarea. |
| wait_on_done() | Espera hasta que la tarea termine. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Devuelve un error de la operación de enmascarado

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | El error de la tarea. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Devuelve el resultado de la operación de enmascarado

**Returns**

| Tipo | Descripción |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | El resultado de esta tarea. |


