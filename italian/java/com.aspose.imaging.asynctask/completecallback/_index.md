---
title: "CompleteCallback"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Funzione di callback per ricevere l'evento di completamento del task."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.asynctask/completecallback/
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

