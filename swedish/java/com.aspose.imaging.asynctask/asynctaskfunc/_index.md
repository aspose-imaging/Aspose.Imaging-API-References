---
title: "AsyncTaskFunc"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den långa operationsdelegaten för den asynkrona uppgiften med generisk typresultat."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

Den långa operationsdelegaten för den asynkrona uppgiften med generisk typresultat.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | Den långa operationsdelegaten för den asynkrona uppgiften med generisk typresultat. |
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


Den långa operationsdelegaten för den asynkrona uppgiften med generisk typresultat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | Tillstånd för den asynkrona uppgiften. |

**Returns:**
java.lang.Object – Resultatet av den långa operationen.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| återanrop | com.aspose.ms.System.AsyncCallback |  |
| tillstånd | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resultat | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
