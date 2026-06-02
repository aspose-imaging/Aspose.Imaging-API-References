---
title: "接口 IAsyncTask"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.AsyncTask.IAsyncTask 接口。异步任务"
type: docs
weight: 100
url: /zh/net/aspose.imaging.asynctask/iasynctask/
---
## IAsyncTask interface

异步任务。

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Error](../../aspose.imaging.asynctask/iasynctask/error/) { get; } | 获取任务错误，该错误在任务完成后可用。 |
| [IsBusy](../../aspose.imaging.asynctask/iasynctask/isbusy/) { get; } | 获取一个值，指示此任务当前是否正在运行。 |
| [IsCanceled](../../aspose.imaging.asynctask/iasynctask/iscanceled/) { get; } | 获取一个值，指示此任务是否已取消。 |
| [IsFaulted](../../aspose.imaging.asynctask/iasynctask/isfaulted/) { get; } | 获取一个值，指示此任务是否已出现错误。 |
| [ProgressEventHandler](../../aspose.imaging.asynctask/iasynctask/progresseventhandler/) { get; set; } | 获取或设置异步任务的进度事件处理程序。 |
| [Result](../../aspose.imaging.asynctask/iasynctask/result/) { get; } | 获取此任务的结果。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Abort](../../aspose.imaging.asynctask/iasynctask/abort/)() | 中止此任务。任务会立即完成，但可能无法释放内部非托管资源。 |
| [Cancel](../../aspose.imaging.asynctask/iasynctask/cancel/)() | 取消此任务。通过受控停止算法安全地完成任务。 |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync/#runasync)() | 运行此任务。 |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | 运行此任务。 |
| [SetCompleteCallback](../../aspose.imaging.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | 设置完成回调委托。 |

### 另请参见

* namespace [Aspose.Imaging.AsyncTask](../../aspose.imaging.asynctask/)
* assembly [Aspose.Imaging](../../)


