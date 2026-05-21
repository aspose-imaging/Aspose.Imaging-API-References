---
title: "AsyncTaskFunc"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le délégué d'opération longue pour la tâche asynchrone avec un résultat de type générique."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

Le délégué d'opération longue pour la tâche asynchrone avec un résultat de type générique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | Le délégué d'opération longue pour la tâche asynchrone avec un résultat de type générique. |
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


Le délégué d'opération longue pour la tâche asynchrone avec un résultat de type générique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | État de la tâche asynchrone. |

**Returns:**
java.lang.Object - Résultat de l'opération longue.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| résultat | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
