---
title: Delegate CompleteCallback
second_title: Aspose.Imaging for .NET API Reference
description: Callback function to receive task completion event
type: docs
weight: 90
url: /net/aspose.imaging.asynctask/completecallback/
---
## CompleteCallback delegate

Callback function to receive task completion event.

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| Parameter | Type | Description |
| --- | --- | --- |
| task | IAsyncTask | The asynchronous task. |
| wasCancelled | Boolean | if set to `true` [was cancelled]. |
| error | Exception | The error. |

### See Also

* interface [IAsyncTask](../iasynctask/)
* namespace [Aspose.Imaging.AsyncTask](../../aspose.imaging.asynctask/)
* assembly [Aspose.Imaging](../../)


