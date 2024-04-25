---
title: AsyncTaskFunc
second_title: Aspose.Imaging for Java API Reference
description: The long operation delegate for the asynchronous task with generic type result.
type: docs
weight: 12
url: /com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

The long operation delegate for the asynchronous task with generic type result.
## Constructors

| Constructor | Description |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | The long operation delegate for the asynchronous task with generic type result. |
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


The long operation delegate for the asynchronous task with generic type result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | State of the asynchronous task. |

**Returns:**
java.lang.Object - Result of the long operation.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
