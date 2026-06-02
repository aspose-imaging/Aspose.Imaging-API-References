---
title: "委托 CompleteCallback"
second_title: "Aspose.Imaging for .NET API 参考"
description: "接收任务完成事件的回调函数"
type: docs
weight: 90
url: /zh/net/aspose.imaging.asynctask/completecallback/
---
## CompleteCallback delegate

用于接收任务完成事件的回调函数。

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| task | IAsyncTask | 异步任务。 |
| wasCancelled | Boolean | 如果设置为 `true` [已取消]。 |
| error | Exception | 错误。 |

### 另请参见

* interface [IAsyncTask](../iasynctask/)
* namespace [Aspose.Imaging.AsyncTask](../../aspose.imaging.asynctask/)
* assembly [Aspose.Imaging](../../)


