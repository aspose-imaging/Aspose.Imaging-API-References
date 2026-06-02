---
title: "AsyncTaskFunc"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Delegat für langwierige Operationen der asynchronen Aufgabe mit generischem Rückgabetyp."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

Der Delegat für langwierige Operationen der asynchronen Aufgabe mit generischem Rückgabetyp.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | Der Delegat für langwierige Operationen der asynchronen Aufgabe mit generischem Rückgabetyp. |
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


Der Delegat für langwierige Operationen der asynchronen Aufgabe mit generischem Rückgabetyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | Zustand der asynchronen Aufgabe. |

**Returns:**
java.lang.Object – Ergebnis der langen Operation.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| Rückruf | com.aspose.ms.System.AsyncCallback |  |
| Zustand | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ergebnis | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
