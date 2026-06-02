---
title: "IAsyncTask"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "异步任务。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

异步任务。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | 获取异步任务的进度事件处理程序。 |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | 设置异步任务的进度事件处理程序。 |
| [isBusy()](#isBusy--) | 获取指示此任务当前是否正在运行的值。 |
| [isCanceled()](#isCanceled--) | 获取指示此任务是否已取消的值。 |
| [isFaulted()](#isFaulted--) | 获取指示此任务是否已出错的值。 |
| [getError()](#getError--) | 获取任务错误，该错误在任务完成后可用。 |
| [getResult()](#getResult--) | 获取此任务的结果。 |
| [runAsync()](#runAsync--) | 运行此任务。 |
| [runAsync(int priority)](#runAsync-int-) | 运行此任务。 |
| [cancel()](#cancel--) | 取消此任务。 |
| [abort()](#abort--) | 中止此任务。 |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | 设置完成回调委托。 |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


获取异步任务的进度事件处理程序。

值：异步任务的进度事件处理程序。

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


设置异步任务的进度事件处理程序。

值：异步任务的进度事件处理程序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | 异步任务的进度事件处理程序。 |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


获取指示此任务当前是否正在运行的值。

值：`true` 表示此任务当前正在运行；否则为 `false`。

**Returns:**
boolean - 指示此任务当前是否正在运行的值。
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


获取指示此任务是否已取消的值。

值：`true` 表示此任务已被取消；否则为 `false`。

**Returns:**
boolean - 一个指示此任务是否已取消的值。
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


获取指示此任务是否已出错的值。

值：如果此任务出现错误，则为 `true`；否则为 `false`。

**Returns:**
boolean - 一个指示此任务是否出现错误的值。
### getError() {#getError--}
```
public abstract Throwable getError()
```


获取任务错误，该错误在任务完成后可用。

值：任务错误。

**Returns:**
java.lang.Throwable - 任务完成后可用的任务错误。
### getResult() {#getResult--}
```
public abstract Object getResult()
```


获取此任务的结果。

值：此任务的结果。

**Returns:**
java.lang.Object - 此任务的结果。
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


运行此任务。

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


运行此任务。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 优先级 | int | 线程的优先级。 |

### cancel() {#cancel--}
```
public abstract void cancel()
```


取消此任务。该任务通过受控停止算法安全完成。

### abort() {#abort--}
```
public abstract void abort()
```


中止此任务。该任务会立即完成，但可能无法释放内部非托管资源。

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


设置完成回调委托。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | 完成回调。 |

