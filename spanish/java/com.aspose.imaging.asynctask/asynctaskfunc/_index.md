---
title: "AsyncTaskFunc"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El delegado de operación larga para la tarea asíncrona con tipo de resultado genérico."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

El delegado de operación larga para la tarea asíncrona con tipo de resultado genérico.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | El delegado de operación larga para la tarea asíncrona con tipo de resultado genérico. |
| [beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### AsyncTaskFunc() {#AsyncTaskFunc--}
```
public AsyncTaskFunc()
```


### invoke(IAsyncTaskState taskState) {#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-}
```
public abstract Object invoke(IAsyncTaskState taskState)
```


El delegado de operación larga para la tarea asíncrona con tipo de resultado genérico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | Estado de la tarea asíncrona. |

**Returns:**
java.lang.Object - Resultado de la operación larga.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| estado | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resultado | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
