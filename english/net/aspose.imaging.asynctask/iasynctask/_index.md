---
title: Interface IAsyncTask
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.AsyncTask.IAsyncTask interface. The asynchronous task
type: docs
weight: 100
url: /net/aspose.imaging.asynctask/iasynctask/
---
## IAsyncTask interface

The asynchronous task.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Error](../../aspose.imaging.asynctask/iasynctask/error/) { get; } | Gets the task error which is available after the task is completed. |
| [IsBusy](../../aspose.imaging.asynctask/iasynctask/isbusy/) { get; } | Gets a value indicating whether this task is currently running. |
| [IsCanceled](../../aspose.imaging.asynctask/iasynctask/iscanceled/) { get; } | Gets a value indicating whether this task was canceled. |
| [IsFaulted](../../aspose.imaging.asynctask/iasynctask/isfaulted/) { get; } | Gets a value indicating whether this task was faulted. |
| [ProgressEventHandler](../../aspose.imaging.asynctask/iasynctask/progresseventhandler/) { get; set; } | Gets or sets the progress event handler of the asynchronous task. |
| [Result](../../aspose.imaging.asynctask/iasynctask/result/) { get; } | Gets the result of this task. |

## Methods

| Name | Description |
| --- | --- |
| [Abort](../../aspose.imaging.asynctask/iasynctask/abort/)() | Aborts this task. The task is completed immediately, with the risk of not freeing internal unmanaged resources. |
| [Cancel](../../aspose.imaging.asynctask/iasynctask/cancel/)() | Cancels this task. The task is completed safely by the controlled stopping of the algorithm. |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync/#runasync)() | Runs this task. |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Runs this task. |
| [SetCompleteCallback](../../aspose.imaging.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Sets the complete callback delegate. |

### See Also

* namespace [Aspose.Imaging.AsyncTask](../../aspose.imaging.asynctask/)
* assembly [Aspose.Imaging](../../)


