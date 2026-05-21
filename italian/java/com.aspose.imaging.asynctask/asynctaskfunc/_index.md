---
title: "AsyncTaskFunc"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il delegato di operazione lunga per il task asincrono con risultato di tipo generico."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

Il delegato di operazione lunga per il task asincrono con risultato di tipo generico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | Il delegato di operazione lunga per il task asincrono con risultato di tipo generico. |
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


Il delegato di operazione lunga per il task asincrono con risultato di tipo generico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | Stato dell'operazione asincrona. |

**Returns:**
java.lang.Object - Risultato dell'operazione lunga.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| stato | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| risultato | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
