---
title: "CompleteCallback"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Функция обратного вызова для получения события завершения задачи."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.asynctask/completecallback/
---```
public interface CompleteCallback
```

Callback function to receive task completion event.
## Methods

| Method | Description |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.imaging.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Callback function to receive task completion event. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.imaging.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Callback function to receive task completion event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) | The asynchronous task. |
| wasCancelled | boolean | if set to `true` [was cancelled]. |
| error | java.lang.Throwable | The error. |

