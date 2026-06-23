---
title: "AsyncTask"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于创建异步任务的静态工厂类"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

用于创建异步任务的静态工厂类
## 方法

| 方法 | 描述 |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | 创建不返回结果的异步任务。 |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | 创建带有泛型结果的异步任务。 |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


创建不返回结果的异步任务。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | 任务操作。 |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


创建带有泛型结果的异步任务。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | 任务函数。 |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
