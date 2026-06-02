---
title: "AsyncTaskFunc"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "带有泛型结果类型的异步任务长操作委托。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

带有泛型结果类型的异步任务长操作委托。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | 带有泛型结果类型的异步任务长操作委托。 |
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


带有泛型结果类型的异步任务长操作委托。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | 异步任务的状态。 |

**Returns:**
java.lang.Object - 长时间操作的结果。
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| 回调 | com.aspose.ms.System.AsyncCallback |  |
| 状态 | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 结果 | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
